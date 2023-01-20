git config --global protocol.file.allow always
git config --global status.submodulesummary 1
git config push.recurseSubmodules on-demand

- add
git submodule add -b "master" "C:/_GIT/CWS.SubRoot/modules/CWS.DemoLib1" "external/CWS.DemoLib1"              
--