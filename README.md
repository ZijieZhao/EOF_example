# EOF_example
`% EOF1
figure();
m_contourf(lon_sst,lat_sst,EOF_1_plot',-0.035:0.0001:0.035,'linestyle','none');
m_grid;
m_coast();
colormap(color_here);
colorbar();
caxis([-0.035 0.035]);`
