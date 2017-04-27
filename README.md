# Workflow Assignment

* For Workflow in Aras Innovator, assignment function is supported in a convenient way.
* For the targeted workflow process, assignment is setup/reflected automatically.
* For item types related to workflow, the UI for assignment setting can be called from My InBasket.

## History

This project and the following release notes have been migrated from the old Aras Projects page.

Release | Notes
--------|--------
[v11SP5](https://github.com/ArasLabs/ext-workflow-assignment/releases/tag/v11SP5) | Support version 11SP5. Instruction are described in the ReadMe.pdf.
[v10SP4](https://github.com/ArasLabs/ext-workflow-assignment/releases/tag/v10SP4) | Build 1 is the initial version. For How-to, please refer to the description in the ReadMe.pdf.

#### Supported Aras Versions

Project | Aras
--------|------
[v11SP5](https://github.com/ArasLabs/ext-workflow-assignment/releases/tag/v11SP5) | 11.0 SP5
[v10SP4](https://github.com/ArasLabs/ext-workflow-assignment/releases/tag/v10SP4) | 10.0 SP4

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **ExtWorkflowAssignment** import package

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\ExtWorkflowAssignment\Import\imports.mf` file in the Manifest File field.
6. Select **com.neosystem.workflowAssignment** in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

#### _Optional:_
Japanese language settings may be applied using the contents of the Language directory and the LanguagePackManagementUtility.

## Usage

Review the [ReadMe-workflowAssignment.pdf](./Documentation/ReadMe-workflowAssignment.pdf) for information on using the project.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Created by NEOSYSTEM Co., Ltd.
