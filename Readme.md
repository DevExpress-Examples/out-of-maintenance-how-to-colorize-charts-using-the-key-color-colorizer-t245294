<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/KeyColorColorizer/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/KeyColorColorizer/MainWindow.xaml))**
<!-- default file list end -->
# How to colorize charts using the Key-Color Colorizer


This example demonstrates how to colorize the GDP bar chart by a country region using the Key-Color colorizer.


<h3>Description</h3>

To configure and use the Key-Color colorizer, perform the following steps.<br />- Create a <strong>KeyColorColorizer</strong> object and assign it to the <strong>Series.Colorizer</strong> property.<br />- Populate the&nbsp;<strong>KeyColorColorizer.Keys</strong>&nbsp;collection.<br />- Specify the&nbsp;<strong>ChartPaletteColorizerBase.Palette</strong>&nbsp;property if you want to use a non-default palette to colorize your data.<br />- In addition, it's possible to specify the&nbsp;<strong>KeyColorColorizer.KeyProvider</strong>&nbsp;property to change the way you used to provide keys based on the color data source member.

<br/>


