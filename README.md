Raster to Vector Mini Pipeline
This mini pipeline demonstrates basic geospatial data handling using Python libraries — Rasterio and GeoPandas. The goal is to read a raster image, extract its metadata (like bounding box & CRS), convert it to a GeoDataFrame, and export it as a Shapefile.
Workflow
1. Read a raster (`.tif`) using Rasterio
2. Extract metadata (CRS, bounds)
3. Create a GeoDataFrame with GeoPandas
4. Save as `raster_extent.shp`

Tools Used
- Python
- Rasterio
- GeoPandas
- Jupyter Notebook
- Git & GitHub

Output
- Shapefile: `raster_extent.shp` (shows bounding box of the raster)

Skills Demonstrated
- Geospatial data processing
- Linking raster + vector concepts
- File handling in Python
- GitHub version control

```bash
git clone https://github.com/mandritadutta/raster-vector-pipeline.git
cd raster-vector-pipeline
jupyter notebook raster-to-vector.ipynb
