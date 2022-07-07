# Piping %>%

R comes with an interesting way to "pipe" together multiple commands. 

%>% is read as "and then"

Example code block:

```r
dataset %>%
  filter(x > 1oo) %>%
  arrange(desc(x)) %>%
  head(5)
```


There are times when piping is not the best approach. Such as when there are so many commands in the pipe that the result gets disorganized.

#general-knowledge#piping
