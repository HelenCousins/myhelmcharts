This creates a Deployment with 2 containers, one for Rshiny and one for 
Rstudio, they mount the same volume.

It is compulsory to provide

studio.password

It is permitted to provide

studio.user
volume (it's name)
studio.image
shiny.image

(the default user is 'user', the default volume name is 'arrr' and it is 
not created, the default images are rocker/rstudio:latest and 
gcr.io/gcer-public/shiny-googleauthrdemo:latest)
