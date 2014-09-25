lag-done
========

Last Activity on Git Done: Returns your commits from the previous business day

## Usage:
* $ lag-done 
    * Returns your commits from the previous day
    * If yesterday was a weekend, from the previous 3 days.
* $ lag-done 5
    * Returns your commits from 5 days ago

## Notes
* Must be called from a git directory
* Ignores merge commits
* Uses all available branches
* Defaults to Markdown list (see variable in file to change)

## Change Log
* 2014-09-25 First Release  
