<h1><strong>(FOR DEVELOPERS)</strong></h1>
<h2>Here is a little <em>help</em>, describing to what you'll find in this folder.</h>

<ul>
  <li>
    <code>at_document_start.css</code> will load-up as soon as possible,
    it includes the "heavy" stuff, which is properly assemble from Google-Fonts,
    and me disassembling the original glyphs, to get the undocumented content, including the desirable unicode-range,
    that newer-browsers and newer-Noto distributions supports, for better loading/fallbacking the correct font-face.
  </li>
  <li>
    <code>at_document_idle.css</code> will when the page will finish "text-loading" (a.k.a DOM-Ready),
    and it overrides (...but not too forcefully.. ) the default font-family rule for standard/code containers.
    <code>at_document_idle.css</code> also has few other minor-definitions to help the overall look&&feel,
    allowing you to have a more clear character-readability.
  </li>
  <li>
    <code>at_document_end.css</code> has nothing.
    The reason it is here, is since it is a part of an efficient-template design, where the file name/exist status,
    is preety much the same, together with their definition at the manifest file, which results in a consistent "just the code matters" design-pattern.
  </li>
</ul>
