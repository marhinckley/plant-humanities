<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Datura"
       author="Marlis Hinckley"
       banner="https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/Datura_quercifolia_flower.jpg/800px-Datura_quercifolia_flower.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->
<param ve-entity eid="Q60"> <!-- New York City -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference. Information about <span data-click-image-zoomto="100,100,1000,1000">image interactions</span> can be found [here](https://github.com/JSTOR-Labs/juncture/wiki/Visual-Essay-Image-Tag).

<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Hyacinthus orientalis_ is a garden ornamental distinguish by its columnar spike of waxy flowers. Much of the hyacinth’s story, however, actually revolves around its bulb. Reconstructing this narrative reveals how the hyacinth bulb contributed to the plant’s survival in its native range over millennia, enabled its mobility in trade networks under the Ottoman Empire, and culminated in its use for forcing indoors at the French court from the mid-1740s. Today, this story can also raise awareness of the environmental impact of the Dutch flower bulb trade and the need for sustainable solutions in modern flower gardening.[^1]
<param ve-image 
       label="Hyacinth" 
       description="flower" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">
       <param ve-entity eid="Q157428"> <!-- Hyacinthus orientalis -->

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

The Frick Collection in New York City has four paintings by Vermeer. Unlike  _Girl with a Pearl Earring_, the Frick Vermeers are genre scenes. In addition to these paintings by Vermeer, the Frick Collection has works by Frans Hals, Rembrandt, and Meyndert Hobbema.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://ids.si.edu/ids/manifest/ark:/65665/m38a15fc9191b5454e993a795fe8a3710b">
<param ve-map center="Q60" zoom="8">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)

