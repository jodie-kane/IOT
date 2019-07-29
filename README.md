## README

In Our Time Podcast CLI Script Suite.
 
A script suite to parse / download / play episodes from the public InOurTime Podcast Website.

Dependencies: 
 - fzf (https://github.com/junegunn/fzf)
 - fmt
 - vlc 
 - curl 
 - wget 

# fetch an episode
shell> IOTFetch 

# incremental update of iot.db 
shell> IOTFetch -u 

# full update of iot.db
shell> IOTFetch -u 0

# Play an episode with vlc
sheel> IOTPlay

TODO:
 make vlc -> xdg-open 
 perhaps consolidate wget into curl to reduce dependencies
 maybe remove fzf dependency...
