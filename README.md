PragmatiQaDataJS:
=====================

This is an adapted version of <a href="http://datajs.codeplex.com/">OData parsing JavaScript library DataJS version 1.1.1</a> to make it play a bit with OData V4 metadata and query results. To clairfy, the changes are mainly to adjust the namespaces based on OData Version (available from HTTP response header) and it's not a complete adaptation for V4. In short, it will work for upto OData V3 as standard with some added partial support for V4.

For OData V4:
<ul>
 <li> Metadata parsing should not fail though navigational aspects are not taken cae of.</li>
 <li> ATOM and JSONLight GET query response parsing for simple V4 Services should work. </li>
 <li> JSON Verbose query response is yet to be adapted. </li>
</ul>

<h3>Why PragmatiQaDataJS ?</h3>
------------------------------------------------------------------------------------------------------------------------
I needed to provide a basic/partial support in <a href="https://chrome.google.com/webstore/developer/stats/hpooflanfopjepihkcjjfeonlnhfnmpp">XOData : OData Visualizer and Explorer" Chrome App.</a> .You can take a "Free Trial of App" to explore example V4 services provided by OData.org. Those are available in the service list drop-down in Chrome App. After checking, if you think this adapted version of dataJS could be useful for your simple applications/OData services till a JavaScript library for proper V4 support is available, then feel free to use it.

