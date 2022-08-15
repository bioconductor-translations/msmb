# msmb
Rmd + msmbstyle version of Modern Statistics for Modern Biology

## build

```
install.packages("devtools")
install.packages("bookdown")
devtools::install_github("grimbough/msmbstyle")
bookdown::render_book('index.Rmd', output_dir = 'docs')
```
