<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128568803/16.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T463166)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [ImageDataModel.cs](./CS/ImageFillStyleHeightMap/Model/ImageDataModel.cs) (VB: [ImageDataModel.vb](./VB/ImageFillStyleHeightMap/Model/ImageDataModel.vb))
* **[MainWindow.xaml](./CS/ImageFillStyleHeightMap/View/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/ImageFillStyleHeightMap/View/MainWindow.xaml))**
* [HeightMapViewModel.cs](./CS/ImageFillStyleHeightMap/ViewModel/HeightMapViewModel.cs) (VB: [HeightMapViewModel.vb](./VB/ImageFillStyleHeightMap/ViewModel/HeightMapViewModel.vb))
<!-- default file list end -->
# How to: Bind manually created series to arguments and value arrays


This example demonstrates how to automatically populate manually created series with points generated from arguments and value arrays.


<h3>Description</h3>

This example uses the following classes and properties.<br>- <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsChart3DControl_SeriesSourcetopic">Chart3DControl.SeriesSource</a>&nbsp;- the series source of the Chart3D control.<br>- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsSeries3DStoragetopic">Series3DStrage</a>&nbsp;-&nbsp;the storage of manually created&nbsp;series.<br>- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsSeries3Dtopic">Series3D</a>&nbsp;- an individual series.<br>- <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsSeries3DBase_Viewtopic">Series3D.View</a>&nbsp;- the view of the series.<br>- <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsSeries3D_PointSourcetopic">Series3D.PointSource</a>&nbsp;- the source of series points.<br>- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsSeriesPoint3DMatrixAdaptertopic">SeriesPoint3DMatrixAdapter</a>&nbsp;- creates series points from arguments and value arrays.<br>- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsSurfaceSeriesViewtopic">SurfaceSeriesView</a>&nbsp;- the&nbsp;<strong>Surface</strong>&nbsp;series view.

<br/>


