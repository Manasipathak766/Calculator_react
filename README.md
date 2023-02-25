Separate branches reserved for specific parts in development:\
**main branch** is always the most recent production code. Experimental code does not belong here.\
**develop branch** contains all of the latest development. \
**test branch** contains all of the tests.\
**hotfix branches** are for minor bug fixes, which cannot wait until the next release.\
**release branches** are used to release new development from develop to master. Any last minute changes,\
such as bumping version numbers, are done in the release branch, and then are merged back into master\
and develop. 
**feature branches** are reserved for bigger features.\