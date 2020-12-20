# How to build a box with the provided files FAQ

The first step is to create a folder structure inside a directory that would contain your packer template and all relevant files.

Packer tempate Direcotry
|-http (folder for your preseed.cfg file)
|-output (folder for your template output)
|-scripts (this one is self explanatory)
|-iso (if you have the OS image locally and do not want to waste time downloading it)
|-template.json

The above structure is needed in order for packer to work without errors.

Once that is done you need to navigate to the parent directory and run the needed packer commands for the build to initiate.
 
