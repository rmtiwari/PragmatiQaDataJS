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
I needed to provide some basic/partial support in <a href="https://chrome.google.com/webstore/detail/xodata/hpooflanfopjepihkcjjfeonlnhfnmpp">XOData : OData Visualizer and Explorer" Chrome App</a> for OData V4 *along-side* other versions. The Chrome App is an improved version of the tool that was originally introduced through a blog post on <a href="http://www.odata.org/blog/online-visualizationexploration-of-odata-services-xodata/"> OData.org </a>.

You can take a "Free Trial of App" to explore example V4 services provided by OData.org. Those are available in the service list drop-down in Chrome App. After checking, if you think this adapted version of dataJS could be useful for your simple applications/OData services till a JavaScript library for proper V4 support is available, then feel free to modify/use it as per the original license.

If you want to compare prag-datajs with original dataJS to see the code change - Please see the version history - Original dataJS ( but renamed ) was commited as initial version so you can easily compere the changes with the version with basic OData V4 support. Also changes are marked with PragmatiQa(Ram) .

