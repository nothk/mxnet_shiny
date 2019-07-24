# Image Classification using MXNetR

To run this shiny app:

```r
install.packages("shiny", repos="https://cran.rstudio.com")
install.packages("imager", repos="https://cran.rstudio.com")
shiny::runGitHub("thirdwing/mxnet_shiny")
```

# 20190724
# by nothk

in file server.r

code:
download.file("http://data.dmlc.ml/mxnet/models/imagenet/inception-bn.tar.gz", destfile = "inception-bn.tar.gz")

old URL for download model is invalid,
use new URL instead: http://data.mxnet.io.s3-website-us-west-1.amazonaws.com/mxnet/data/Inception.zip
