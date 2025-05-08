### valencia-descriptive3 ###

The following are the comments included in the valencia-entry7.R file's code that were removed. With each, an explanation will be included.

### Setup with packages and working directory
  The tidyverse and ggplot2 packages were loaded into R, and the working directory was set up with setwd(). 

### Loading Data
  The data was taken using the link from Levshina's original data report. The data was not dowloaded and then loaded into R, but happened using the link to the data itself.

### Subsetting Data to remove "press" genre
  The "press" genre was removed to match Levshina's own graph. As the assignment was to recreate the graph, such was done.

### Separating the frequency data based on color for later
  The frequency data for each color was seperated out and given its own name in accordance with said color. This was used to
  assign the frequencies to the color later on.

### Shifting the genres to a single column
  As the original data had multiple values in one cell, a new column was made titled "genre" which the genre name would now
  be.

### Creating a new column for color association
  Another new column was made titled "color" with the starting default entries of "seagreen". This was done to change the row
  names to its own column. The color "seagreen" was chosen as to be distinct against the other colors which would eventually
  be inserted there. This is important so that any potential errors can be caught.

### Identifying the data with its coordinating color
  Using the previously collected subset color-frequency data, the frequency number and color were aligned appropriately.
  As such, the color and frequency from before can now be properly aligned in the "color" column.

### Column Names

### First few rows

### Creating the A6 Figure

