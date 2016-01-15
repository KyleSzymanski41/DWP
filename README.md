# Deployment of Web Applications 
##### _Week 2 Assignment: Your Portfolio, Live to the World!
Kyle Szymanski | Full Sail University  201601-01 Online

## Single-Tier Server Architecture Requirements
* Linux Ubuntu v12.04.5 LTS
* Git v1.7.9.5 
* Apache v2.4.16
* PHP v5.5.30


## Version Numbering
* When releasing new versions the pattern to follow is Release Version (dot) Production Release ++ (dot) Staged Release ++. (v##.##.##)
* Each time a new feature is promoted to the staging server increment the Staged Release value by one.
* Each time a Production promotion occurs increment the Production Release Value by one.
* Additionally on Production Promotions reset the Staged Release value to zero.

##Example:

*Staged Release: v0.1.13 turns into v0.1.14
*Production Release: v0.1.14 turns into v0.2.0

## Branched Development
* When adding a new feature, use a seperate and unique branch that's not the master branch.
* Once you're new feature is complete and has been thoroughly tested, you can marge this feature branch into the master branch. 
