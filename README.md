# Microsoft Power BI visuals plus custom visuals by MAQ Software

The Microsoft Power BI visuals project provides high quality data visualizations that you can use to extend [Power BI](https://powerbi.microsoft.com/).  The project contains over 20 visualization types plus custom visuals by MAQ Software, the framework to run them, and the testing infrastructure that enables you to build high quality visualizations.  The framework provides all the interfaces you need to integrate fully with Power BI's selection, filtering, and other UI experiences.  The code is written in [TypeScript](http://www.typescriptlang.org/) so it's easier to build and debug. Everything compiles down to JavaScript and runs in modern web browsers.  The visuals are built using [D3](http://d3js.org/) but you can use your favorite technology like [WebGL](https://en.wikipedia.org/wiki/WebGL), [Canvas](https://en.wikipedia.org/wiki/Canvas_element), or [SVG](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics). This gives you everything you need to build custom visualizations for Power BI.


# Custom Visuals

<br />
<br />

| [Circular Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/circularGauge.ts)   |      [Linear Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/linearGauge.ts)     |  [Brick Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/Brickchart.ts) |
|----------|------------|------|
| IIllustrate headway toward goals in &nbsp;<br /> either a pie or a donut chart &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> format. One color illustrates actual <br /> progress and the other displays the <br /> target. The percentage shown tracks <br /> progress. Text size and ring size &nbsp;&nbsp;<br /> are customizable. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />![Circular Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/circularGauge/Images/screenshot.png) | Create at-a-glance visualization to <br /> compare your progress against &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> identified goals and warning zones. <br /> By allowing you to include multiple <br /> data points, the component provides <br /> the ability to illustrate trend &nbsp;&nbsp;&nbsp;&nbsp;<br /> details, such as monthly or &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> year-to-date completion rates. The &nbsp;<br /> pointer notes targets and the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> colored bar shows the current &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> progress toward those goals. &nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> ![Linear Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/linearGauge/Images/screenshot.png) | Brick Chart consists of 100 squares <br /> that are colored according to the &nbsp;&nbsp;<br /> percentage breakdown of your &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> datasets. Hover your mouse over a &nbsp;&nbsp;<br /> square to bring up a tooltip. The &nbsp;&nbsp;<br /> tooltip indicates which dataset the <br /> color represents and the percentage <br /> value of that category. An optional <br /> legend above the chart identifies &nbsp;&nbsp;<br /> which datasets correspond with which <br /> colors. You may tailor the legend’s <br /> title, size and color. You may also <br /> customize the chart’s width and &nbsp;&nbsp;&nbsp;&nbsp;<br /> height. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />  ![Brick Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/Images/Brick%20Chart/BrickChart_Screenshot_410_424.png) |

<br />
<br />

| [Stock Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/stockChart.ts)   |      [Bowtie Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/BowtieChart/BowtieChart.ts)     |  [Horizontal Funnel](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/horizontalFunnel/HorizontalFunnel.ts) |
|----------|------------|------|
| Stock Chart displays significant &nbsp;&nbsp;&nbsp;<br /> stock price points as colored &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> vertical bars. Low and high price &nbsp;&nbsp;<br /> values are represented by grey bars. <br /> Open and close price values are &nbsp;&nbsp;&nbsp;&nbsp;<br /> shown as either red or green bars, &nbsp;<br /> which are superimposed over the low <br /> and high values. If a stock’s price <br /> dropped the bar will be red, and if <br /> the price rose the bar will be &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> green. Prices are listed on the &nbsp;&nbsp;&nbsp;&nbsp;<br /> vertical axis and time increments &nbsp;&nbsp;<br /> are listed on the horizontal axis. &nbsp;<br /> The ranges for prices and time &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> increments are customizable. &nbsp;&nbsp;&nbsp;&nbsp;<br /> ![Stock Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/Images/Stock%20Chart/StockChart_Screenshot_410_424.png) | Bowtie Chart displays categorization <br /> of a value by branching out smooth <br /> interpolated nodes. The thickness of <br /> the branch indicates the weightage &nbsp;<br /> of the category. You can display &nbsp;&nbsp;&nbsp;<br /> Half Bowtie or Full Bowtie by &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> providing source category or both &nbsp;&nbsp;<br /> source and destination categories &nbsp;&nbsp;<br /> respectively. Used for displaying &nbsp;&nbsp;<br /> the categorization of an aggregated <br /> value. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> ![Bowtie Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/BowtieChart/Images/BowtieChart_Screenshot_410_424.png) | Horizontal Funnel allows you to &nbsp;&nbsp;&nbsp;&nbsp;<br /> visualize a customizable primary &nbsp;&nbsp;&nbsp;<br /> measure as colored bars. Use this to <br /> display a number of metric types, &nbsp;&nbsp;<br /> such as sales stages, time or &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> geographic locations. A second &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> customizable value is displayed &nbsp;&nbsp;&nbsp;&nbsp;<br /> beneath the colored bars. This &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> feature provides you the ability to <br /> track an additional metric against &nbsp;<br /> your primary measure. The component <br /> includes the option to create a tool <br /> tip, which you may tailor to your &nbsp;&nbsp;<br /> specific needs. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />![Horizontal Funnel](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/src/Clients/CustomVisuals/visuals/horizontalFunnel/Images/HorizontalFunnel_Screenshot_410_424.png) |

<br />
<br />

| [Donut Chart(GMO)](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/donutChart(GMO)/donutChart(GMO).ts)   |      [JSON Grid](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/grid/GridNode/src/jsonGrid.js)     |  [Thermometer](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/thermometer/Thermometer/src/visual.ts) |
|----------|------------|------|
| A doughnut charts represent data as slices, where the size of each slice is determined by the slice value relative to the sum of the values of all slices. Each data series that you plot in a doughnut chart adds a ring to the chart. These rings have different colors for easy representation of the data slices in doughnut chart.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />![Donut Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/src/Clients/CustomVisuals/visuals/donutChart(GMO)/Images/DonutChart_Screenshot_410_424.png) | Grid allows you to add a paginated grid on the report. It allows you to specify on which column should the grid be sorted by default and in which order. It also allows you to call an API on any column if further processing needs to be done. goals.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /><br /><br /><br />![Grid](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/grid/GridNode/assets/screenshot.png) | Thermometer is used to represent data in thermometer. It could be a good way to represent data when you have the actual value and the target value (maximum threshold). needs.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /><br /><br /><br /><br />![Thermometer](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/thermometer/Images/Thermometer_icon_424_410.jpg) |


<br />
<br />
<br />
<br />
<br />

| [Text Wrapper](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Text%20Wrapper/src/visual.ts)   |
|----------|
| Text Wrapper wrap a static text <br />string (Statement) along with a <br />dynamic text (field value which <br />was taken as an input (from the <br />dataset. This dynamic field <br />(value will update according to<br /> the selected (filter/slicer keeping the<br /> static text intact.( The static<br /> string needs to be provided by <br />the (user which will be appended<br /> as “ : <>” after the (dynamic field<br /> value in the visual resulting the<br /> final value( in the visual <br />as: “<> : <>” | 

<br />
<br />

# PowerBI Visual Tools (pbiviz) - Installation

Before you can get started you'll need to install the tools. This should only take a few seconds.

## Dependencies

Before you can run (or install) the command line tools you must install NodeJS.

* NodeJS 4.0+ Required (5.0 recommended) - [Download NodeJS](https://nodejs.org)


## Installation
[![Npm Version](https://img.shields.io/npm/v/powerbi-visuals-tools.svg?style=flat)](https://www.npmjs.com/package/powerbi-visuals-tools)
[![Npm Downloads](https://img.shields.io/npm/dm/powerbi-visuals-tools.svg?style=flat)](https://www.npmjs.com/package/powerbi-visuals-tools)  
To install the command line tools simply run the following command

```bash
npm install -g powerbi-visuals-tools
```

To confirm it was installed correctly you can run the command without any paremeters which should display the help screen.

```bash
pbiviz
```

## Server certificate setup

To enable live preview visual assets need to be served on a trusted https server so before you can start you need to install an ssl certificate which will allow visual asssets to load in your web browser. This is a one time setup.

* [How to install the local SSL certificates](https://github.com/Microsoft/PowerBI-visuals/blob/master/tools/CertificateSetup.md) 

## Enable developer visual

To view/test your visual in PowerBI you need to enable the development visual and then you can add it to any report.

* [How to enable the developer visual in PowerBI](https://github.com/Microsoft/PowerBI-visuals/blob/master/tools/DebugVisualSetup.md)

# Running the visuals in this repository 
Select the visual you want to run. Navigate to the root of visual project (the directory containing `pbiviz.json`). Simply run the following commands

```bash
#This will install modules listed in package.json
npm install 

#This will install type definitions listed in typings.json
typings install 

#To run the visual
pbiviz start
```

That's it you are good to go. You can see that the visual is running.

### Copyrights

Copyright (c) 2017 Microsoft and MAQ Software

See the [LICENSE](/LICENSE) file for license rights and limitations (MIT).
