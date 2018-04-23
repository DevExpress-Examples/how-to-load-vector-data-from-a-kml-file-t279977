# How to: Load vector data from a KML file


This example demonstrates how to load vector data from a KML file.


<h3>Description</h3>

To load vector data from a KML file, do the following.<br />1. Create a&nbsp;<strong>VectorFileLayer</strong> object and add it&nbsp;to the&nbsp;<strong>MapControl.Layers</strong> collection.<br />2. Create an instance of the&nbsp;<strong>KmlReader</strong> class and assign&nbsp;the instance&nbsp;to the&nbsp;<strong>VectorFileLayer.FileReader</strong> property.<br />3. Create&nbsp;a&nbsp;<strong>MapFileSourceBase</strong> class descendant object, configure it&nbsp;and assign to the&nbsp;<strong>FileSource</strong> property of the instance.

<br/>

