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
  

#general-knowledge#piping
