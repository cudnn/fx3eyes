# fx3eyes

## makefile

FX3FWROOT need a path which is under `xxx/Cypress/cyfx3sdk`
You should add a line is FX3FWROOT = xxx/Cypress/cyfx3sdk

## mkcompile.sh

compile mkcompile.sh need module `git`,you can use follow command to install :

`sudo apt-get install git`

## bulid.sh

This shell also need FX3FWROOT,FX3FWROOT is `xxx/Cypress/cyfx3sdk`,
You can also add a line is FX3FWROOT = xxx/Cypress/cyfx3sdk

## Compile Firmware ##
- If everything is all set, you can run `./build.sh` within `fx3eyes/firmware`, which generates  `cyfxuvc_baidu.img`.


