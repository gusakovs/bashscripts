# BASHSCRIPTS

This is a series of scripts I use on a daily basis. Feel free to modify them so they suit your needs.

## rename

A simple batch "sequence" renaming tool.

By default, **only** `jpg` files are renames and every filename starts with "test-".

Flags :
* -s : "string". The name you want to give your files
* -n : The starting number. Default is 1.
* -t : "theme". What comes after the "string".

The blueprint is the following :

`test-${string}-${theme}-${sequence}.jpg`
