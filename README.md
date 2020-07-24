# Converting ArcGIS Symbology Labels to CSV
ArcGIS does not have a built-in feature for exporting symbology unique value classes and their correspondent text labels onto a tabular format. This tool allows you to convert a layer file with .lyrx extension to CSV.

## Instructions
1. In the contents pane, right-click on the feature layer, choose **Sharing** and then **Save as Layer File**
2. Save a new layer file
3. Call the **symbToCSV** function in the attached jupyter notebook, pass the following arguments:
    1. inputLyrx (str): Input ArcGIS synbology file name, lyrx file extension included.
    2. outputCSV (str): Output CSV file name, csv file extension included.
