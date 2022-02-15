# USAGE
#### see INSTALL or SETUP; all information here is included.. see `-h --install` `-h --setup`
#### for detailed descriptions read the ARCH if I write it ...

The only slightly confusing this about this tool is it has a lot of args, and you can do some reasonably unusual things to the arg stack ( I think; of course no statement is finished ). Any command of which there only the main functions of the tool can also be an argument. You can overload the order for example when using in slightly variation aliases ( everything must be explicit and the arg logic will always be the same pretty much: I hope.. However the profiles allow you to control a lot.. SO everything is configurable )

### usage profiles
  - expert
  - non-expert
#### included profiles and how the default operation works
  - safe
  - van
  - grant
#### almost everything mods something before
#### profiles are not config on the cli from cwd...
#### cwd is for usage... tool config is for customisations... such as custom hashing.. 
  - limit functions like hash etc
#### how releases work 
  - v 1 2 3 4 5 6 7 8 
  - each is a release profile - they likely change how the internals works
#### note on major versions
- every prior version is included, almost anything is limited or sticky... see `-h --to-ver`. Since I am using this all the time once it works.. it has to work forever.. 
## upgrading
## running
## logging
## state
## persistence
## behaviours
----
#### notes on security

The tool will never connect to the network, allow any network module. And only runs locally. There should never be a point this is added. Completely out of scope. Its just to help me at first.. and maybe somebody else if it actually works.

##### default: running it as a clone of itself ( there is a word i need ot use for this )
##### optional: running as a monolith
#### how to be paranoid
#### how to see what is actually happening
#### using `--dryrun`
#### using `--transform` to get a gui
#### recommended shell integration
#### recommended os shell integration
#### long-running tasks
----
### locations
#### media-types
#### paths
#### local, networked, archive-mounted
----
### runtime options
----
### options
  #### hardware-limit-matrix / recommended option values
    - not going to automate this at first, unless I can find some code that makes it sort of work. Or libraries do this well.. I think its easy enough from what the kernels tell you....
----
### switches
----
### ops
----
### commands
----
### modes
----
## transforms
#### supported formats
#### interface details
