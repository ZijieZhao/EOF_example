# EOF example - a small tutorial based on a case study for climatological precipitation over Central America and Southern Mexico

Empirical Orthogonal Function (EOF) is a dimensionality reduction method, which has been used in a wide range of research associated with climatology and oceanography. In terms of reducing data's size to make it more visualized and  analysable, EOF actually does a similar job as Principal Component Analysis (PCA), except it tends to decompose datasets in both temporal and spatial dimensions. 

Traditionally, EOF is mostly used to determine the dominant modes of variables and their associated explained variance. 

Let's see an example. Consider a dataset containing annual climatology of precipitation during 1979 to 2017 over Central America and Mexico.

`%% Load the data
load('eof_example');
size(precip_clim);

% Have a look of a time series
see=squeeze(precip_clim(48,29,:));
plot(1:366,see,'linewidth',2);
`



