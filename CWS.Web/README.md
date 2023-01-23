git config --global protocol.file.allow always
git config --global status.submodulesummary 1
git config push.recurseSubmodules on-demand

- add
git submodule add -b "master" "C:/_GIT/CWS.SubRoot/modules/CWS.DemoLib1" "external/CWS.DemoLib1"
--
git submodule add -b "master" "https://github.com/orest/CWS.DemoLib2.git" "../CWS.DemoLib"            


-- update 
git submodule update --init --recursive


-- check all 
git submodules foreach 'cat .gitmodules'


-- sync CONFIG 
git submodule sync --recursive
