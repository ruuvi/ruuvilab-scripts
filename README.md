# ruuvilab-scripts
Scripts which can be run on RuuviTag. 
These are generally Espruino Scripts made by community. Take a look at 
[RuuviLab](lab.ruuvi.com) ideas for use cases of these scripts as well as
to check out what has been proposed. We offer RuuviTags as a reward for some scipt implementations.

# How to contribute
Check out RuuviLab for ideas on new scripts, and open pull request if you want to contribute
your work or improvements to existing scripts. 

A new script should have at least following things:
 * A new folder which contains the work.
 * Script file with a descriptive name, for example "fridge_monitor.js"
 * Usage instructions on a separate README, as well as a note on which versions(s) of firmware the script has been tested.
 * License, BSD-3 is preferred, but any permissive license such as MIT or WTFPL is ok. In particular GPL is not compatible with the Nordic SDK license used with nRF52 due to linked binary software radio with no sources and restrictions on usage (as far as we know, open issue if you disagree).

 We'll review the pull request as soon as possible, preferably under a week. While reviewing we power profile the application, generally the power 
 consumption should be at most 100 µA on average to provide at least one year battery life. We'll help with power optimization if needed.