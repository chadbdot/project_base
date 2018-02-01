#### -- Run custom settings, if present. -- ####
# R only loads one .Rprofile file, and we want to keep this one clean so that
#   it may be used as a generic starting point for new users. To add custom
#   settings, create '.custom.Rprofile' in the top-level directory.
# Remember: Don't include anything in custom.Rprofile that is required to run
#   scripts, as this file is NOT part of the project!

if (file.exists(".custom.Rprofile")) {
  message("'custom.Rprofile' found. Loading...")
  source(".custom.Rprofile")
  # source(".Rprofile.user")
}

#### -- Packrat Autoloader (version 0.4.8-1) -- ####
if (file.exists(".custom.Rprofile")) {
  source("packrat/init.R")
} else {
  packrat::init()
}
#### -- End Packrat Autoloader -- ####

