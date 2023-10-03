#Assessment - Reading questions
## Bryan (2017)

1. setwd() is highly specific to your device- collaborators will have to change this code, which is cumbersome.

2. rm(list=ls()) clears objects in the environment. It does not clear setting choices that may support code running correctly. After restarting R session, these will be reset, potentially causing your code to not run. Code will run differently on collaborators' sessions if their settings are configured differently.

##Bryan (2018)

3. 'Commmit' is a local command, while 'push' and 'pull' occur between a local system and the repo (remotely).

4. Word docs are in binary, so diffs would not be readable to humans.

5. Markdown is useful because it includes not only code, but comments to make it more readable. It can easily be knitted(?) to make it more readable, while still being usable code. 