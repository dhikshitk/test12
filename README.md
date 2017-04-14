# Microsoft Power BI visuals plus custom visuals by MAQ Software

The Microsoft Power BI visuals project provides high quality data visualizations that you can use to extend [Power BI](https://powerbi.microsoft.com/).  The project contains over 20 visualization types plus custom visuals by MAQ Software, the framework to run them, and the testing infrastructure that enables you to build high quality visualizations.  The framework provides all the interfaces you need to integrate fully with Power BI's selection, filtering, and other UI experiences.  The code is written in [TypeScript](http://www.typescriptlang.org/) so it's easier to build and debug. Everything compiles down to JavaScript and runs in modern web browsers.  The visuals are built using [D3](http://d3js.org/) but you can use your favorite technology like [WebGL](https://en.wikipedia.org/wiki/WebGL), [Canvas](https://en.wikipedia.org/wiki/Canvas_element), or [SVG](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics). This gives you everything you need to build custom visualizations for Power BI.


# Custom Visuals

<br />
<br />

| [Circular Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/circularGauge.ts)   |      [Linear Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/linearGauge.ts)     |  [Brick Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/Brickchart.ts) |
|----------|------------|------|
| IIllustrate headway toward goals in &nbsp;<br /> either a pie or a donut chart &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> format. One color illustrates actual <br /> progress and the other displays the <br /> target. The percentage shown tracks <br /> progress. Text size and ring size &nbsp;&nbsp;<br /> are customizable. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />![Circular Gauge](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Circular%20Gauge/Images/screenshot.png) | Create at-a-glance visualization to <br /> compare your progress against &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> identified goals and warning zones. <br /> By allowing you to include multiple <br /> data points, the component provides <br /> the ability to illustrate trend &nbsp;&nbsp;&nbsp;&nbsp;<br /> details, such as monthly or &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> year-to-date completion rates. The &nbsp;<br /> pointer notes targets and the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> colored bar shows the current &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> progress toward those goals. &nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> ![Linear Gauge](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Linear%20Gauge/Images/screenshot.png) | Brick Chart consists of 100 squares <br /> that are colored according to the &nbsp;&nbsp;<br /> percentage breakdown of your &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> datasets. Hover your mouse over a &nbsp;&nbsp;<br /> square to bring up a tooltip. The &nbsp;&nbsp;<br /> tooltip indicates which dataset the <br /> color represents and the percentage <br /> value of that category. An optional <br /> legend above the chart identifies &nbsp;&nbsp;<br /> which datasets correspond with which <br /> colors. You may tailor the legend’s <br /> title, size and color. You may also <br /> customize the chart’s width and &nbsp;&nbsp;&nbsp;&nbsp;<br /> height. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />  ![Brick Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Brick%20Chart/Images/screenshot.png) |

<br />
<br />

| [Stock Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/stockChart.ts)   |      [Bowtie Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/BowtieChart/BowtieChart.ts)     |  [Horizontal Funnel](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/horizontalFunnel/HorizontalFunnel.ts) |
|----------|------------|------|
| Stock Chart displays significant &nbsp;&nbsp;&nbsp;<br /> stock price points as colored &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> vertical bars. Low and high price &nbsp;&nbsp;<br /> values are represented by grey bars. <br /> Open and close price values are &nbsp;&nbsp;&nbsp;&nbsp;<br /> shown as either red or green bars, &nbsp;<br /> which are superimposed over the low <br /> and high values. If a stock’s price <br /> dropped the bar will be red, and if <br /> the price rose the bar will be &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> green. Prices are listed on the &nbsp;&nbsp;&nbsp;&nbsp;<br /> vertical axis and time increments &nbsp;&nbsp;<br /> are listed on the horizontal axis. &nbsp;<br /> The ranges for prices and time &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> increments are customizable. &nbsp;&nbsp;&nbsp;&nbsp;<br /> ![Stock Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Trading%20Chart/Images/TradingChart_Screenshot_410_424.png) | Bowtie Chart displays categorization <br /> of a value by branching out smooth <br /> interpolated nodes. The thickness of <br /> the branch indicates the weightage &nbsp;<br /> of the category. You can display &nbsp;&nbsp;&nbsp;<br /> Half Bowtie or Full Bowtie by &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> providing source category or both &nbsp;&nbsp;<br /> source and destination categories &nbsp;&nbsp;<br /> respectively. Used for displaying &nbsp;&nbsp;<br /> the categorization of an aggregated <br /> value. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> ![Bowtie Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Bowtie%20Chart/Images/BowtieChart_Screenshot_410_424.png) | Horizontal Funnel allows you to &nbsp;&nbsp;&nbsp;&nbsp;<br /> visualize a customizable primary &nbsp;&nbsp;&nbsp;<br /> measure as colored bars. Use this to <br /> display a number of metric types, &nbsp;&nbsp;<br /> such as sales stages, time or &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> geographic locations. A second &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> customizable value is displayed &nbsp;&nbsp;&nbsp;&nbsp;<br /> beneath the colored bars. This &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> feature provides you the ability to <br /> track an additional metric against &nbsp;<br /> your primary measure. The component <br /> includes the option to create a tool <br /> tip, which you may tailor to your &nbsp;&nbsp;<br /> specific needs. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />![Horizontal Funnel](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Horizontal%20Funnel/Images/HorizontalFunnel_Screenshot_410_424.png) |

<br />
<br />

| [Donut Chart(GMO)](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/donutChart(GMO)/donutChart(GMO).ts)   |      [JSON Grid](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/grid/GridNode/src/jsonGrid.js)     |  [Thermometer](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/thermometer/Thermometer/src/visual.ts) |
|----------|------------|------|
| A doughnut charts represent data as <br /> slices, where the size of each slice <br /> is determined by the slice value &nbsp;&nbsp;&nbsp;<br /> relative to the sum of the values of <br /> all slices. Each data series that &nbsp;&nbsp;<br /> you plot in a doughnut chart adds a <br /> ring to the chart. These rings have <br /> different colors for easy &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> representation of the data slices in <br /> doughnut. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />![Donut Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Ring%20Chart/Images/RingChart_Screenshot_410_424.png) | Grid allows you to add a paginated &nbsp;<br /> grid on the report. It allows you to <br /> specify on which column should the &nbsp;<br /> grid be sorted by default and in &nbsp;&nbsp;&nbsp;<br /> which order. It also allows you to &nbsp;<br /> call an API on any column if further <br /> processing needs to be done. &nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> ![Grid](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/JSON%20Grid/Images/screenshot.png) | Thermometer is used to represent &nbsp;&nbsp;&nbsp;<br /> data in thermometer. It could be a &nbsp;<br /> good way to represent data when you <br /> have the actual value and the target <br /> value (maximum threshold). needs. <br /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />![Thermometer](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Thermometer/Images/Thermometer_icon_424_410.jpg) |


<br />
<br />
<br />
<br />
<br />

| [Text Wrapper](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Text%20Wrapper/src/visual.ts)   |
|----------|
| Text Wrapper wrap a static text &nbsp;&nbsp;&nbsp;&nbsp;<br /> string (Statement) along with a &nbsp;&nbsp;&nbsp;&nbsp;<br /> dynamic text field value which was &nbsp;<br /> taken as an input from the dataset. <br /> This dynamic field value will update <br /> according to the selected &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> filter/slicer keeping the static &nbsp;&nbsp;&nbsp;<br /> text intact. The static string needs <br /> to be provided by the user which &nbsp;&nbsp;&nbsp;<br /> will be appended as “ : <>” after &nbsp;&nbsp;<br /> the dynamic field value in the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> visual resulting the final value in <br /> the visual as: “<> : <>” &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br /> ![Text Wrapper](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Text%20Wrapper/Images/Screenshot.png ) | 

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
![](https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png | width=100)
![](https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png =250x250)
See the [LICENSE](/LICENSE) file for license rights and limitations (MIT).
