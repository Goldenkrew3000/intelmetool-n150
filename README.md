# Intelmetool for Alderlake & N150
Intelmetool patched to work with the Alderlake & N150 HECI

# What is this?
Intelmetool by default does not work with newer hardware, and requires patching to add support, and this is that.<br>
This is pulled directly from the coreboot source tree (Commit ```ec49a5556e572990f552fe98c84f55f8e4ddcc63```) and is can be built externally.<br>
The source code is at ```util/intelmetool``` and can be built by running ```make```.<br>

# Tested Devices
- Chuwi Hi10 Max N150 ```(00:16.0 0780: 8086:54e0)```
- Thinkpad E14 Gen 4 ```(00:16.0 0780: 8086:51e0)```
