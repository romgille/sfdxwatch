# sfdxwatch
A script that runs a watcher on source files inside a Salesforce project

To run it, you have to write the relative path to the files you want to watch.

## Examples

`sfdxwatch lwc/myLightningWebComponent/ classes/myController.cls` will watch both `myLightningWebComponent` files and `myController.cls` file.

`sfdxwatch` will watch the whole subdirectories you have in the current folder.
