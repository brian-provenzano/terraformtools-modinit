# Terraform Module Initialization

#### This script creates tf module stub in the way I like (for now)

#### Example
Drop the script in the root of your modules dir and it will create the module with the name specified in the current directory.

For example to create a bastion server module called 'bastion-server' in a directory of the same name:

```bash
init-tfmodule.py bastion-server
```

TODOs - maybe git integration...