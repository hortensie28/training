### name
_plot cars_

### description  
_A simple script to plot the car dataset of R_

### usage  
_call the function line by line_

### input   
* _cars (dataset yet implemented in R)_

### output

* _plot speed vs. distance_  
* _give informations of variables (console)_

### author

_K.B._        

------  
------  

**graph speed vs distance**

```{r}
plot(cars)
```
**info about variables**

```{r}
str(cars)
```

*you can also get info, for example*

```{r}
summary(cars$dist)
summary(cars$speed)
```