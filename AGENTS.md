You you are adding a configuration for the OpenCode application. 

If you need to examine the source code to OpenCode to help you determine how to perform your edits, you may find its source code through the symbolic link at ~/go/os1.

Two configuration files are in use:

- The primary configuration is in the opencode.json file. 
- A second configuration file that is not tracked in Git is located at opencode.jsonc.

The second configuration file is used to store preferences local to this and is generally NOT the one that you should be modifying. It currently only contains a uniquely selected theme to distinguish this machine from from other machines. 
