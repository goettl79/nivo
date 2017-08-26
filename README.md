<img alt="nivo" src="https://raw.githubusercontent.com/plouc/nivo/master/nivo.png" width="216" height="68" />

[![License][license-image]][license-url]
[![Travis CI][travis-image]][travis-url]
[![NPM version][npm-image]][npm-url]
[![Dependencies][gemnasium-image]][gemnasium-url]

**nivo** provides supercharged React components to easily build dataviz apps,
it's built on top of d3.

Several libraries already exist for React d3 integration, but just a few provide server side rendering ability and fully declarative charts.

## Features

- supports [d3 v4](https://github.com/d3/d3/blob/master/CHANGES.md)
- composable
- [responsive charts](http://nivo.rocks/#/components?term=responsive) (`<Responsive* />` components)
- highly customizable
- motion/transitions, even the non-d3 based components (DOM managed by React) support transitions within the help of [react-motion](https://github.com/chenglou/react-motion)
- [component playground](http://nivo.rocks)
- [exhaustive documentation](http://nivo.rocks)
- isomorphic rendering
- support for SVG and [HTML](http://nivo.rocks/#/components?term=html) (I'm also considering canvas support)
- [placeholder components](http://nivo.rocks/#/components?term=placeholder) for advanced customization (`<*Placeholders />` components)
- [server side rendering API](https://github.com/plouc/nivo-api)

## Components

- Bar
    - [`<Bar />`](http://nivo.rocks/#/bar)
    - [`<ResponsiveBar />`](http://nivo.rocks/#/bar)
- Bubble
    - [`<Bubble />`](http://nivo.rocks/#/bubble)
    - [`<ResponsiveBubble />`](http://nivo.rocks/#/bubble)
    - [`<BubblePlaceholders />`](http://nivo.rocks/#/bubble/placeholders)
    - [`<ResponsiveBubblePlaceholders />`](http://nivo.rocks/#/bubble/placeholders)
- Calendar
    - [`<Calendar />`](http://nivo.rocks/#/calendar)
    - [`<ResponsiveCalendar />`](http://nivo.rocks/#/calendar)
- Chord
    - [`<Chord />`](http://nivo.rocks/#/chord)
    - [`<ResponsiveChord />`](http://nivo.rocks/#/chord)
- HeatMap
    - [`<HeatMap />`](http://nivo.rocks/#/heatmap)
    - [`<ResponsiveHeatMap />`](http://nivo.rocks/#/heatmap)                
- Line
    - [`<Line />`](http://nivo.rocks/#/line)
    - [`<ResponsiveLine />`](http://nivo.rocks/#/line)
- Pie
    - [`<Pie />`](http://nivo.rocks/#/pie)
    - [`<ResponsivePie />`](http://nivo.rocks/#/pie)
- Radar
    - [`<Radar />`](http://nivo.rocks/#/radar)
    - [`<ResponsiveRadar />`](http://nivo.rocks/#/radar)
- Sankey
    - [`<Sankey />`](http://nivo.rocks/#/sankey)
    - [`<ResponsiveSankey />`](http://nivo.rocks/#/sankey)               
- Stream
    - [`<Stream />`](http://nivo.rocks/#/stream)
    - [`<ResponsiveStream />`](http://nivo.rocks/#/stream)           
- Sunburst
    - [`<Sunburst />`](http://nivo.rocks/#/sunburst)
    - [`<ResponsiveSunburst />`](http://nivo.rocks/#/sunburst)  
- TreeMap
    - [`<TreeMap />`](http://nivo.rocks/#/treemap)
    - [`<ResponsiveTreeMap />`](http://nivo.rocks/#/treemap)
    - [`<TreeMapHTML />`](http://nivo.rocks/#/treemap/html)
    - [`<ResponsiveTreeMapHTML />`](http://nivo.rocks/#/treemap/html)
    - [`<TreeMapPlaceholders />`](http://nivo.rocks/#/treemap/placeholders)
    - [`<ResponsiveTreeMapPlaceholders />`](http://nivo.rocks/#/treemap/placeholders)
- Voronoi `experimental`
    - [`<Voronoi />`](http://nivo.rocks/#/voronoi)
    - [`<ResponsiveVoronoi />`](http://nivo.rocks/#/voronoi)            

## [HTTP API](https://github.com/plouc/nivo-api)

- [`<Bar />`](https://nivo-api.herokuapp.com/samples/bar.svg)
- [`<Bubble />`](https://nivo-api.herokuapp.com/samples/bubble.svg)
- [`<Chord />`](https://nivo-api.herokuapp.com/samples/chord.svg)
- [`<HeatMap />`](https://nivo-api.herokuapp.com/samples/heatmap.svg)
- [`<Line />`](https://nivo-api.herokuapp.com/samples/line.svg)
- [`<Pie />`](https://nivo-api.herokuapp.com/samples/pie.svg)
- [`<Radar />`](https://nivo-api.herokuapp.com/samples/radar.svg)
- [`<Sankey />`](https://nivo-api.herokuapp.com/samples/sankey.svg)
- [`<Sunburst />`](https://nivo-api.herokuapp.com/samples/sunburst.svg)
- [`<TreeMap />`](https://nivo-api.herokuapp.com/samples/treemap.svg)

## Guides
    
- [colors](http://nivo.rocks/#/guides/colors)    

## Repositories

- [nivo](https://github.com/plouc/nivo) - the nivo library
- [nivo-api](https://github.com/plouc/nivo-api) - the nivo http api
- [nivo-api-docker](https://github.com/plouc/nivo-api-docker) - a Docker image for the nivo http api
- [nivo-generators](https://github.com/plouc/nivo-generators) - the data generators used for nivo-website and http API samples
- [nivo-website](https://github.com/plouc/nivo-website) - the source for the nivo website

## Credits

- [d3](https://d3js.org/)
- [react](https://facebook.github.io/react/)
- [react-motion](https://github.com/chenglou/react-motion)
- …

[license-image]: https://img.shields.io/github/license/plouc/nivo.svg?style=flat-square
[license-url]: https://github.com/plouc/nivo/blob/master/LICENSE.md
[npm-image]: https://img.shields.io/npm/v/nivo.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/nivo
[travis-image]: https://img.shields.io/travis/plouc/nivo.svg?style=flat-square
[travis-url]: https://travis-ci.org/plouc/nivo
[gemnasium-image]: https://img.shields.io/gemnasium/plouc/nivo.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/plouc/nivo
