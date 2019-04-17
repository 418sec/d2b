> [d2b](../README.md) › **Chart Axis**

<!-- ![Local Image](../gifs/chart-axis.gif) -->

# {#generator}
[#](#generator) d2b.**chartAxis**()

Constructs a new axis chart generator with the default settings.

When using the d2b-axis generator you can draw an axis chart onto each element in the selection.

# {#apply}
[#](#apply) *axis.advanced*(*context*)

Render the axis chart(s) to the given *context*, which may be either a [d3-selection](https://github.com/d3/d3-selection) of html containers (e.g. div) or a corresponding [d3-transition](https://github.com/d3/d3-transition). 

> Note: The *advanced* mode is new in d2b > 1.0.0. In *advanced* mode all of axis chart [configuration properties](#properties) will be available with the input datum.

# {#basic_line}
### [#](#basic_line) Line Chart

<figure class="axis_basic">
  <iframe
    src="https://codesandbox.io/embed/github/d2bjs/demos/tree/master/charts/axis/basic-line?runonclick=0" 
    frameborder="0" 
    allowfullscreen="true" 
    mozallowfullscreen="true" 
    webkitallowfullscreen="true"
  ></iframe>
</figure>

# {#annotation}
### [#](#annotation) Annotation

<figure class="axis_annotation">
  <iframe 
    src="https://codesandbox.io/embed/github/d2bjs/demos/tree/master/charts/axis/annotation?runonclick=0" 
    frameborder="0" 
    allowfullscreen="true" 
    mozallowfullscreen="true" webkitallowfullscreen="true"
  ></iframe>
</figure>

# {#basic}
### [#](#basic) Basic

<figure class="axis_basic">
  <iframe 
    src="https://codesandbox.io/embed/github/d2bjs/demos/tree/master/charts/axis/axes-basic?runonclick=0" 
    frameborder="0" 
    allowfullscreen="true" 
    mozallowfullscreen="true" 
    webkitallowfullscreen="true"
  ></iframe>
</figure>

# {#groups}
### [#](#groups) Groups

<figure class="axis_groups">
  <iframe 
    src="https://codesandbox.io/embed/github/d2bjs/demos/tree/master/charts/axis/groups?runonclick=0" 
    frameborder="0" 
    allowfullscreen="true" 
    mozallowfullscreen="true" 
    webkitallowfullscreen="true"
  ></iframe>
</figure>

# {#legend}
### [#](#legend) Legend

<figure class="axis_legend">
  <iframe 
    src="https://codesandbox.io/embed/github/d2bjs/demos/tree/master/charts/axis/legend?runonclick=0" 
    frameborder="0" 
    allowfullscreen="true" 
    mozallowfullscreen="true" 
    webkitallowfullscreen="true"
  ></iframe>
</figure>

# {#padding}
### [#](#padding) Padding

<figure class="axis_padding">
  <iframe 
    src="https://codesandbox.io/embed/github/d2bjs/demos/tree/master/charts/axis/basic-line?runonclick=0" 
    frameborder="0" 
    allowfullscreen="true" 
    mozallowfullscreen="true" 
    webkitallowfullscreen="true"
  ></iframe>
</figure>

# {#scale}
### [#](#scale) Scale

<figure class="axis_scale">
  <iframe 
    src="https://codesandbox.io/embed/github/d2bjs/demos/tree/master/charts/axis/axes-scale?runonclick=0" 
    frameborder="0" 
    allowfullscreen="true" 
    mozallowfullscreen="true" 
    webkitallowfullscreen="true"
  ></iframe>
</figure>

# {#typescript}
### [#](#typescript) Typescript

<figure class="axis_typscript">
  <iframe 
    src="https://codesandbox.io/embed/github/d2bjs/demos/tree/master/charts/axis/typescript?runonclick=0" 
    frameborder="0" 
    allowfullscreen="true" 
    mozallowfullscreen="true" 
    webkitallowfullscreen="true"
  ></iframe>
</figure>

# {#properties}
### [#](#properties) Properties

This is a complete list of properties that may be supplied to the axis chart datum. **Bold** properties are required.

{% include "./axisProperties.md" %}