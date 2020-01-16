# terraform init
**Summary**: Initialize Working Directory

**Description**: Pulls down providers required for project.
The providers are saved in .terraform\plugins.
Can be run many times without issue.


# terraform plan
**Summary**: View Potential Changes

**Description**: Displays changes that will be applied to infrastructure if apply command is run.


# terraform apply
**Summary**: Execute Changes

**Description**: Applies local changes to infrastructure.


# terraform destroy
**Summary**: Revert Changes

**Description**: Completely removes all Terraform infrastructure. Very powerful/dangerous command. 


# terraform validate
**Summary**: Syntax Checker

**Description**: Validates all .tf files are using valid HCL syntax. Does not connect to remote services.


# terraform format
**Summary**: Cleans Up Syntax

**Description**: Formats HCL syntax to make files more readable and conform to best practices.


# terraform state
**Summary**: Perform State Management

**Description**: Provides interaction with .tfstate file for advanced state management. Can be used to create state backup files.


# terraform graph
**Summary**: Create Resource Models

**Description**: Crate visual representations of project configuration or execution plans.


# terraform workspace
**Summary**: Manage Workspaces

**Description**: Create/modify/delete workspaces to modify CLI scope.


# terraform taint
**Summary**: Re-provision Specific Resource

**Description**: Re-provisions a specific resource. Destroys and re-applies the resource when ran.
