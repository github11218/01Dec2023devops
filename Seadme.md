## Git prune, a child of git gc, maintains a repository by clearing unreachable refs. 
## The refs to delete are also referred to as orphaned objects.

Failure to understand the ins and outs of the command could prevent you from using it appropriately. This
guide explains the internals of git prune. You will find it easy to identify when to use the prune command or
ignore it by the end of the tutorial.

Here is a quick overview of how to apply the command.

git prune command cheat sheet

You can use git prune with several options. For instance, use the -- dry-run and -- verbose options

bash

git prune -- dry-run -- verbose

to can check for objects to remove.

Use the -- expire and -- verbose options