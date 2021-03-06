# my little interactive visualization gallery

In this project I collect some example code snippets that demonstrate various
visualizations that may be useful for cell-based high throughput screening data analysis,
such as plateviewers, scatterplots with links to images etc.

Most of them are based on holoviews and/or bokeh. Much of this is just copied and pasted from example code from their respective documenatiion with only minor modifications.

This is also meant for code snippets and animated gifs to illustrate questions on the gitter/bokeh channels or issues in their repositories.

volker dot hilsenstein at embl de

## Gallery

### Plateviewer

Select different 
* plates
* values / features
* colormap
* percentile ranges

Use custom tooltips to link back to source images
from which the features were derived.
![](./Plateviewer/Plateview_demo.gif)

### Thumbnails and values in a HTML Div update by selection in scatterplot

![](./DivFromSelection/GalleryFromScatterPlotgif.gif)

![](./DivFromSelection/selection_from_scatter.gif)


### Slice through time/volume series dimensions, adjust colormap and value range

![](./Images_with_interactors/dynamic_map_interact_zt_cmap_vmin_vmax.gif)


### Ipyvolume bokeh linked selection demo

This is just a slight modification of the example provided by the developer of `ipyvolume` at https://ipyvolume.readthedocs.io/en/latest/bokeh.html

![](./3DScatterPlots/bokeh_ipyvolume.gif)
