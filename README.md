# MiniAODexamples
## Intructions to run the examples.
```
source /cvmfs/cms.cern.ch/cmsset_default.sh 
export SCRAM_ARCH=slc6_amd64_gcc530
cmsrel CMSSW_9_2_10
cd CMSSW_9_2_10/src/
cmsenv
voms-proxy-init -voms cms -valid 192:00
git clone git@github.com:jmejiagu/MiniAODexamples.git
scram b
cd MiniAODexamples/DemoAnalyzer/test
cmsRun DemoTrackAnalyzer_cfg.py
```
