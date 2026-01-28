# Plot GDIS 3D plot

This function plots a GDIS visualization based on GDIS parameters.

## Usage

``` r
GDIS_plot_3D(
  input_triangle_parameters,
  show.rendering = TRUE,
  show.names = TRUE,
  webversion = FALSE
)
```

## Arguments

- input_triangle_parameters:

  the path to the RData GDIS output, which ends with
  3D.triangle_parameters.RData

- show.rendering:

  option to show the rendering of the plot in an external window,
  default is TRUE

- show.names:

  option to show the names of the groups, default is TRUE

- webversion:

  needs to stay on FALSE
