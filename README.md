# mydsb2023


#[Project description]

install.packages("blogdown")
library(blogdown)
install_hugo()
hugo_version()

blogdown::new_site(theme = "MarcusVirg/forty",
  sample = TRUE,
  theme_example = TRUE,
  empty_dirs = TRUE,
  to_yaml = TRUE)
  