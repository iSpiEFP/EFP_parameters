# EFP_parameters
Repository with official EFP parameters

## ExtractMetaModified.py

### Description

Refer to the README within the iSpiEFP/scripts directory for a full description of the original file; the file here is meant to be its near-clone. The difference in functionality is that iSpiEFP/scripts/extractMeta.py generates fileName.json from some fileName.efp, whereas the script here iSpiEFP/EFP_parameters/extractMetaModified.py will append the JSON format of .efp files into libraryMeta.json. The script still takes in one .efp argument at a time, and does not remove libraryMeta.json itself if necessary (see the Actions tab on gitHub to see how automated daily builds are currently being handled).
