# Multipart Sankey Diagrams

Extended from Mike Bostock's original d3.sankey.

[Demo](http://bl.ocks.org/emeeks/1dd092dadc02a93cdebc)

```js
var sankey = d3.sankey()
    .size([width, height])
    .nodeWidth(15)
    .nodePadding(10)
    .nodes(energy.nodes)
    .links(energy.links)
    .layout(32);
```

```
var path = sankey.link();
```
