# Microsoft Power BI visuals plus custom visuals by MAQ Software

The Microsoft Power BI visuals project provides high quality data visualizations that you can use to extend [Power BI](https://powerbi.microsoft.com/).  The project contains over 20 visualization types plus custom visuals by MAQ Software, the framework to run them, and the testing infrastructure that enables you to build high quality visualizations.  The framework provides all the interfaces you need to integrate fully with Power BI's selection, filtering, and other UI experiences.  The code is written in [TypeScript](http://www.typescriptlang.org/) so it's easier to build and debug. Everything compiles down to JavaScript and runs in modern web browsers.  The visuals are built using [D3](http://d3js.org/) but you can use your favorite technology like [WebGL](https://en.wikipedia.org/wiki/WebGL), [Canvas](https://en.wikipedia.org/wiki/Canvas_element), or [SVG](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics). This gives you everything you need to build custom visualizations for Power BI.


# Custom Visuals

<br />
<br />

| [Circular Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/circularGauge.ts)   |      [Linear Gauge](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/linearGauge.ts)     |  [Brick Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/Brickchart.ts) |
|----------|------------|------|
|IIllustrate headway toward goals in <br />either a pie or a donut chart <br />format. One color illustrates <br />actual progress and the other <br />displays the target. The <br />percentage shown tracks progress. <br />Text size and ring size are <br />customizable. <br /><br /><br /><br /><br /><br /><br /><br /> ![Circular Gauge](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Circular%20Gauge/Images/screenshot.png) | Create at-a-glance visualization <br />to compare your progress against <br />identified goals and warning <br />zones. By allowing you to include <br />multiple data points, the <br />component provides the ability to <br />illustrate trend details, such as <br />monthly or year-to-date completion <br />rates. The pointer notes targets <br />and the colored bar shows the <br />current progress toward those <br />goals. <br /><br /><br /><br />![Linear Gauge](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Linear%20Gauge/Images/screenshot.png) | Brick Chart consists of 100 <br />squares that are colored according <br />to the percentage breakdown of <br />your datasets. Hover your mouse <br />over a square to bring up a <br />tooltip. The tooltip indicates <br />which dataset the color represents <br />and the percentage value of that <br />category. An optional legend above <br />the chart identifies which <br />datasets correspond with which <br />colors. You may tailor the <br />legend’s title, size and color. <br />You may also customize the chart’s <br />width and height. <br />  ![Brick Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Brick%20Chart/Images/screenshot.png) |

<br />
<br />

| [Stock Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/Visuals/visuals/stockChart.ts)   |      [Bowtie Chart](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/BowtieChart/BowtieChart.ts)     |  [Horizontal Funnel](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/horizontalFunnel/HorizontalFunnel.ts) |
|----------|------------|------|
| Stock Chart displays significant <br />stock price points as colored <br />vertical bars. Low and high price <br />values are represented by grey <br />bars. Open and close price values <br />are shown as either red or green <br />bars, which are superimposed over <br />the low and high values. If a <br />stock’s price dropped the bar will <br />be red, and if the price rose the <br />bar will be green. Prices are <br />listed on the vertical axis and <br />time increments are listed on the <br />horizontal axis. The ranges for <br />prices and time increments are <br />customizable. <br />  ![Stock Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Trading%20Chart/Images/TradingChart_Screenshot_410_424.png) | Bowtie Chart displays <br />categorization of a value by <br />branching out smooth interpolated <br />nodes. The thickness of the branch <br />indicates the weightage of the <br />category. You can display Half <br />Bowtie or Full Bowtie by providing <br />source category or both source and <br />destination categories <br />respectively. Used for displaying <br />the categorization of an <br />aggregated value. <br /><br /><br /><br /><br /> ![Bowtie Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Bowtie%20Chart/Images/BowtieChart_Screenshot_410_424.png) |Horizontal Funnel allows you to <br />visualize a customizable primary <br />measure as colored bars. Use this <br />to display a number of metric <br />types, such as sales stages, time <br />or geographic locations. A second <br />customizable value is displayed <br />beneath the colored bars. This <br />feature provides you the ability <br />to track an additional metric <br />against your primary measure. The <br />component includes the option to <br />create a tool tip, which you may <br />tailor to your specific needs. <br /> <br /><br />![Horizontal Funnel](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Horizontal%20Funnel/Images/HorizontalFunnel_Screenshot_410_424.png) |

<br />
<br />

| [Donut Chart(GMO)](https://github.com/maqsoftware/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/donutChart(GMO)/donutChart(GMO).ts)   |      [JSON Grid](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/grid/GridNode/src/jsonGrid.js)     |  [Thermometer](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Clients/CustomVisuals/visuals/thermometer/Thermometer/src/visual.ts) |
|----------|------------|------|
| A doughnut charts represent data <br />as slices, where the size of each <br />slice is determined by the slice <br />value relative to the sum of the <br />values of all slices. Each data <br />series that you plot in a doughnut <br />chart adds a ring to the chart. <br />These rings have different colors <br />for easy representation of the <br />data slices in doughnut chart. <br />![Donut Chart](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Ring%20Chart/Images/RingChart_Screenshot_410_424.png) | Grid allows you to add a paginated <br />grid on the report. It allows you <br />to specify on which column should <br />the grid be sorted by default and <br />in which order. It also allows you <br />to call an API on any column if <br />further processing needs to be <br />done. <br /> ![Grid](https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/JSON%20Grid/Images/screenshot.png) | Thermometer is used to represent <br />data in thermometer. It could be a <br />good way to represent data when <br />you have the actual value and the <br />target value (maximum threshold). <br /><img src="https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Thermometer/Images/Thermometer_icon_424_410.jpg" alt="Thermometer" height="268" width="268"> |


<br />
<br />

| [Text Wrapper](https://github.com/bandaruabinash/PowerBI-visuals/blob/master/src/Text%20Wrapper/src/visual.ts)   |
|----------|
| Text Wrapper wrap a static text <br />string (Statement) along with a <br />dynamic text field value which was <br />taken as an input from the <br />dataset. This dynamic field value <br />will update according to the <br />selected filter/slicer keeping the <br />static text intact. The static <br />string needs to be provided by the <br />user which will be appended as “ : <br /><>” after the dynamic field value <br />in the visual resulting the final <br />value in the visual as: “<> : <>” <br /><img src="https://raw.githubusercontent.com/maqsoftware/PowerBI-visuals/master/documents/Text%20Wrapper/Images/Screenshot.png" alt="Text wrapper" height="268" width="268"> | 

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
