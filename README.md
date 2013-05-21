git-utils
=========

A collection of poor-mans Git utilities.

* `git-all` iterates over a set of directories with the name pattern 
  _dirname.git_ and executes abritrarily git commands on it.
  If no comman is given, it will exectute a `git fetch --all` and on
  Subversion bound repositories a `git svn fetch`
* `git-empty` creates a new, empty branch, do a checkout of this empty
  branch and adds/commits a short hint-file about the current branch.
  Executes an additional `git gc` to further assist the idea of this 
  empty branch of saving disk space.
  
License
-------
These scripts are licensed under the terms of APL2.0.
For terms refer to http://www.apache.org/licenses/LICENSE-2.0.html
