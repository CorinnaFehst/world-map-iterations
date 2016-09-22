## 06 linear breaks, quantiles scale

this iteration uses a [quantile](https://github.com/d3/d3-scale/blob/master/README.md#quantile-scales) scale with naive linear breaks to map values in the data to colors on the choropleth map

the remaining examples in this design study also use a [quantile](https://github.com/d3/d3-scale/blob/master/README.md#quantile-scales) scale to map data thresholds to discrete colors.

🎩 [@adamrpearce](https://twitter.com/adamrpearce) for [suggesting](https://d3js.slack.com/archives/help/p1474482256000307) a [quantile](https://github.com/d3/d3-scale/blob/master/README.md#quantile-scales) scale over in the [#help](https://d3js.slack.com/messages/help/) channel of the [d3js slack](https://d3-slackin.herokuapp.com/)

📄 [http://roadtolarissa.com/blog/2015/01/04/coloring-maps-with-d3/](http://roadtolarissa.com/blog/2015/01/04/coloring-maps-with-d3/)

do check out the other examples in this `world map` series:  

[world map 00 original example](https://bl.ocks.org/jeremycflin/b43ab253f3ae02dced07)  
[world map 01 fix tooltip value](https://bl.ocks.org/micahstubbs/01529b106c93f9b649c4006de5c79b80)  
[world map 02 d3 v4](https://bl.ocks.org/micahstubbs/8e15870eb432a21f0bc4d3d527b2d14f)  
[world map 03 es2015 + update code style](https://bl.ocks.org/micahstubbs/281d7b7a7e39a9b59cf80f1b8bd41a72)  
[world map 04 manual breaks + threshold scale](https://bl.ocks.org/micahstubbs/535e57a3a2954a129c13701fe61c681d)  
[world map 05 linear breaks + quantize scale](https://bl.ocks.org/micahstubbs/c14d8bda8e337da6c836a526ad1a7c5a)  
**world map 06 linear breaks + quantiles scale**  
[world map 07 Jenks natural breaks](https://bl.ocks.org/micahstubbs/8fc2a6477f5d731dc97887a958f6826d)  
[world map 08 ckmeans cluster max breaks](https://bl.ocks.org/micahstubbs/9c2397c1da11c7b5d331653bcd475c1f)  
[world map 09 ckmeans cluster min breaks](https://bl.ocks.org/micahstubbs/c7f17dcbdc728e0d579d84e47c33dfa6)  