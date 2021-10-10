<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571850/21.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T232417)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MapProjections/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MapProjections/MainWindow.xaml))
<!-- default file list end -->
# How to specify a map projection


<p>This example demonstrates how to specify a map projection that is used to display geographical data for a Map Control.<br />One of the following predefined map projections can be used:</p>
- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapBraunStereographicProjectiontopic">Braun stereographic projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapEllipticalMercatorProjectiontopic">Elliptical Mercator projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapEqualAreaProjectiontopic">Equal-area projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapEquidistantProjectiontopic">Equidistant projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapEquirectangularProjectiontopic">Equirectangular projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapKavrayskiyProjectiontopic">Kavrayskiy projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapLambertCylindricalEqualAreaProjectiontopic">Lambert Cylindrical Equal-area projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapMillerProjectiontopic">Miller projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapSinusoidalProjectiontopic">Sinusoidal projection</a>;<br />- <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapSphericalMercatorProjectiontopic">Spherical Mercator projection</a>.


<h3>Description</h3>

To specify a map projection use the <a href="https://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapGeoMapCoordinateSystem_Projectiontopic">GeoMapCoordinateSystem.Projection</a>&nbsp;property of the object assigned to the <a href="https://documentation.devexpress.com/#WindowsForms/DevExpressXtraMapMapControl_CoordinateSystemtopic">MapControl.CoordinateSystem</a>&nbsp;property.

<br/>


