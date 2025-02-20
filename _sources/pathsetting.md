# Path Setting

When conducting your data analysis project you will want to keep all of your files organised. We  suggest you set up a directory (folder) to store all of your files (data and outputs) and name it appropriately e.g. DataProject. Download the `sleep.csv` file from GALEN and place it in this directory. 

It may be useful to determine your working directory (or path) for R and then set it to be the directory you have created for your data project. This means when pointing to files e.g. `sleep.csv` you can keep your path short.

```{code-block}
# Determine working directory
getwd()

# Set working directory
setwd("~/Documents/DataProject")
```


