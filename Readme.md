<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128568855/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T245294)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/KeyColorColorizer/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/KeyColorColorizer/MainWindow.xaml))**
<!-- default file list end -->
# How to colorize charts using the Key-Color Colorizer


This example demonstrates how to colorize the GDP bar chart by a country region using the Key-Color colorizer.


<h3>Description</h3>

To configure and use the Key-Color colorizer, perform the following steps.<br />- Create a <strong>KeyColorColorizer</strong> object and assign it to the <strong>Series.Colorizer</strong> property.<br />- Populate the&nbsp;<strong>KeyColorColorizer.Keys</strong>&nbsp;collection.<br />- Specify the&nbsp;<strong>ChartPaletteColorizerBase.Palette</strong>&nbsp;property if you want to use a non-default palette to colorize your data.<br />- In addition, it's possible to specify the&nbsp;<strong>KeyColorColorizer.KeyProvider</strong>&nbsp;property to change the way you used to provide keys based on the color data source member.

<br/>


