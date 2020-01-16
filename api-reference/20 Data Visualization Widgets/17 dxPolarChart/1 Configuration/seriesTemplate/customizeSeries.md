---
type: function(seriesName)
---
---
##### shortDescription
Specifies a callback function that returns a [series](/api-reference/20%20Data%20Visualization%20Widgets/17%20dxPolarChart/1%20Configuration/series '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Configuration/series/') object with individual series settings.

##### param(seriesName): string
The name of the series to be customized.

##### return: Series configuration
A configuration object for the series.

---
Use this option to specify individual settings for a particular series.

To determine the series to which the function's return value will be applied, use the function's parameter. The parameter is set to the series name that is specified in the data source's field.