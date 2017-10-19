<h1><img src="resources/icon.png" height="64" width="64"/> Chrome-Extension-012MobileLoader</h1>

- versions   <code>1.0.0.1</code>-<code>1.0.0.3</code> Keeps loop checking for a non-repeative number: 054-231-7896/054-213-6887/...
- version(s) <code>2.0.0.*</code> look for numbers with four repeative digits: 054-222-2896/054-213-9999/... (since the non-repeative rule is so rare..)
- version(s) <code>3.0.0.*</code> look for five repeating digits: 054-222-2296/054-219-9999/... (since the four repeating actually found few matches quite early..)
- version(s) <code>4.0.0.*</code> look for '5555' in the number
- version(s) <code>5.0.0.*</code> look for multiple "nice patterns" (more efficient matching).

<hr/>

- The page will show a match/no match using each phone-number's span-container-background-color.
- main-logic will keep refreshing the page until at-least one-match were found.
- sometimes the page will get-stuck, this always happens in automated-real web "test-like" pages, global TIMEOUT is set to fix that.

<hr/>

<h2>012Mobile uses unique-user-identification which is stored on the sessionStorage,
or in-case of non-sessionStorage supporting browsers, it will fallback to using cookie instead,
in that case that cookie IS JavaScript accessible.</h2>

<pre>
Developer's HUB / Changelog

5.0.0.4
* engine update, when restart is needed it executes asynchronously, with engine-processing stop.

5.0.0.1
* efficient multi-match each number to list of "nice number" patterns, instead of single one (logic upgrade).

4.0.0.1
* changed condition to number containing '5555'.

3.0.0.2
+ adding restart points if important-elements from the work-phase are missing.

3.0.0.1
* changing the condition: looking for repeating of 5 digits.. 054-444-4123

2.0.0.3
+ adding status on document.title, helps to verbose state when window is minimized.

2.0.0.2
+ top frame (window) only.

2.0.0.1
+ notification by background color, using CSS (faster rendering).
* engine update (setTimeout is embedding-internally on click-emulation method(s), and on DOM-related-method(s), just a wrap).
* rule update.
* meaning commenting (Hebrew).

1.0.0.3
+ fail-safe reload after 30sec of inactivity, when there are no "nice numbers" found..

1.0.0.2
+ delay after DOM changes

1.0.0.1
+ initial
</pre>

<!-- <a href="https://paypal.me/e1adkarak0"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal Donation"></a> -->