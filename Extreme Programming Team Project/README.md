Add your development guide and setup guide here...

The aim is to quickly help developers set up the project for development once they have checked out the svn repository for the first time
and to serve as a point of reference/single source of truth for specific details.

#### Suggested development workflow
Steps: Accept a 'trac' ticket > `svn update` > [technical work start] > `svn update` > `svn commit -m "[[ticket number]: description of work done]"`

Justification: The first few steps should be self explanatory, but the second use of `svn update` is to assure that any merge conflicts are resolved locally before committing changes to the master copy.
