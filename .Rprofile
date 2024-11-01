options(
  languageserver.formatting_style = function(options) {
    styler::tidyverse_style(indent_by = 2)
  }
)

source("renv/activate.R")
if (interactive() && Sys.getenv("RSTUDIO") == "") {
  source(file.path(Sys.getenv(if (.Platform$OS.type == "windows") "USERPROFILE" else "HOME"), ".vscode-R", "init.R"))
}
