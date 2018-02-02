# R-57

### Function summary

```R
str()
summary()
sapply(data.frame, typeof)
View()
```

```R
as.numeric()
```

- Good habits
```R
ls() # Environment
rm(list = ls())
```

### Notes

- data.frame

```R
data.frame$colnames

data.frame[, colnames] # , aka python : # will return vector
data.frame["colnames"] # will return a data frame

data.frame[rownames, colnames]
```
