# Title: human Genome Variation Tutorial


### Step 1: Loaded packages
```r
library(maps)
library(mapdata)
library(scales)
library(mapplots)
```

## Step 2: World Map Layer

```
map('worldHires', xlim=c(-120,142), ylim=c(-12,72), col='gray', fill=FALSE)
```

```r
map('worldHires', xlim=c(-120,142), ylim=c(-12,72), col='gray', fill=FALSE)
	
	points(freq$long, freq$lat, pch=16, col="salmon")
	
	box()
```



