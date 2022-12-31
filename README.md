# graph-animation
Creates motion to graphs and letters with Matplotlib's scatter plots. Subsequently, builds a GIF from binary images.

Adapted from Thiagobc23/Scatter-Letters

A script to write letters with Matplotlib's scatter plots, create transitions from one plot to the other and build a GIF.  

Libraries:
scatter_letters, OpenCV, Matplotlib and ImageIO.  

## Require  
`pip install scatter_letters`

## Usage

    from scatter_letters import sl
    sl.text_to_gif('data_')
