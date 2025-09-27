## Replication:

Open MTGECON_603.Rproj. This will prompt you to install renv (if you don't) have
it installed already.

You can load any dependencies with:

```r
renv::restore()
```

(These might change week to week). 

By and large, I will try to keep the data in the respective pset's folder, but 
if there are large datasets, I may .gitignore them and require that you put them
into the pset folder yourself. I'll try to write an informative error message
in R if that's not the case.

To run the code, you can open up that week's pset .Rmd and knit it or run chunks
individually. If you have problems feel free to email me (or raise an issue on git).