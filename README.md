# Snapshot of CA Dept. of Education SAT, ACT, AP Test Results Page

See the mirror at: http://wgetsnaps.github.io/state.gov--socialmedia

This repository is a mirror of the following site:

|        Key         |                           Value                           |
|--------------------|-----------------------------------------------------------|
| Site title         | Global Social Media Presence |
| Original publisher | U.S. Department of State                        |
| URL                | http://www.state.gov/r/pa/ode/socialmedia/                           |
| Mirrored at        | 2016-01-11 08:54:44                                       |



# Bash and wget commands

To create this mirror:

~~~sh
wget --page-requisites \
     --no-directories \
     --adjust-extension \
     --convert-links \
     --backup-converted \
     http://www.state.gov/r/pa/ode/socialmedia/ |
     tee ./wget.log
~~~     
