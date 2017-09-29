# goapp-config

##Easy to use config helper for golang application

###Write the code:

import (
  "github.com/AlexeySpiridonov/goapp-config"
)

param := config.Get("param")


###Create the config file in the config dir( ./config ):

> ./config/dev.conf


param:  somevalue


###Run the apllication


./yourApp   -  run in default mode (dev.conf)
./yourApp  prod  - run with prod.conf

P.S. don't use other runtime arguments :( 
