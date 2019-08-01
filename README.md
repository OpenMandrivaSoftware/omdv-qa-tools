# omdv-qa-tools
Various scripts for QA to check repositories
check_build_completion: A small script that checks the content of the repos for build completion of the more major system 
package sets. 
Depending on command line options checks will be run for Qt, kf, kapps and plasma desktopp (pd) filesets for designated 
repositories.
This provides a simple check on whether a package set has been fully built. The script can also checks for duplicates 
and with the use of the --ver= option is capable of producing a list of duplicates that can be used to remove any 
rogue files that may be present in the repository.

TO DO:
Create a separate list for akonadi which uses different version numbers to the other KF5 libs. It may be necessary to use combined lists under the --kf flag to pick these up. Needs some thought
