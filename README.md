# ipr-master-diff
A repo for showing master databases differences between version changes of IDOLY PRIDE

## Artifacts
See [Actions page](https://github.com/Stilamcat/ipr-master-diff/actions).

Each commit that changes `!version.txt` will create a zipped artifact which contains all database files.  
You can get it by using [Github Artifacts API](https://docs.github.com/en/rest/actions/artifacts).

Note that due to `Reward.json` has reached GitHub file size limitation, I but have to make it compressed. This can be somehow inconvenient when you are going to compare what were changing between versions, but let's say better less than never. 
