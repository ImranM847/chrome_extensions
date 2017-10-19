<h1><img src="resources/icon.png" height="64" width="64"/> Chrome-Extension-History-API-Disabler</h1>

<h3><em>★★★★★ Disable's HTML5's History API. Most WebSites That Uses SPF Or JS-Navigation Will Fallback To Standard-Page Loading.</em></h3>

<img width="0" height="0" src="resources/screenshot_1.png"/>

<hr/>

This Solution Is A Bit <strong>Overkill</strong> (But It Will Work...)<br/>
For Disabling SPF, JS-Navigation and other dynamic page loading that uses the History-API (<strong>And Checks For Fallback..</strong>).

<pre>
Developer's HUB / Changelog

1.0.3.4
+ inject script, has content set by inner-html instead of a text-node child which won't work in early loading stages (before body loads..).
* trying to delete references first (of history-related objects).

1.0.1.1
* improved removing of History class and history instance, along with history state event of frame. On YouTube you will see SPF.JS errors on the main console, that is because the developers of SPF havn't verified History class exist before using it. Everything should work fine though, plus now you can block all 'spf.js' and 'lazy.min.js' instances with uBlock/AdBlock.

1.0.0.7
* invalidate History/history under main scope.

1.0.0.5
* changed to blocking code-block, to halt-rendering until executed (very early..)

1.0.0.3
+ initial.
</pre>

<br/>

<!-- <a href="https://paypal.me/e1adkarak0"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal Donation"></a> -->