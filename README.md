# Community health files for the @opsbot github organization

## About default community health files

You can add default community health files to the root of a public repository called .github that is owned by an organization or user account.

GitHub will use and display default files for any public repository owned by the account that does not have its own file of that type in any of the following places:

- the root of the repository
- the .github folder
- the docs folder

For example, anyone who creates an issue or pull request in a public repository that does not have its own CONTRIBUTING file will see a link to the default CONTRIBUTING file. If a repository has any files in its own .github/ISSUE_TEMPLATE folder, including issue templates or a config.yml file, none of the contents of the default .github/ISSUE_TEMPLATE folder will be used.

Default files are not included in clones, packages, or downloads of individual repositories because they are stored only in the .github repository.

## Supported file types

You can create defaults in your organization or user account for the following community health files:

|Community health file|Description|
|---|---|
|CODE_OF_CONDUCT.md|A CODE_OF_CONDUCT file defines standards for how to engage in a community. For more information, see ["Adding a code of conduct to your project."](https://help.github.com/en/articles/adding-a-code-of-conduct-to-your-project)
|CONTRIBUTING.md|A CONTRIBUTING file communicates how people should contribute to your project. For more information, see ["Setting guidelines for repository contributors."](https://help.github.com/en/articles/setting-guidelines-for-repository-contributors)
|FUNDING.yml|A FUNDING file displays a sponsor button in your repository to increase the visibility of funding options for your open source project. For more information, see ["Displaying a sponsor button in your repository."](https://help.github.com/en/articles/displaying-a-sponsor-button-in-your-repository)
|Issue and pull request templates and config.yml|Issue and pull request templates customize and standardize the information you'd like contributors to include when they open issues and pull requests in your repository. For more information, see ["About issue and pull request templates."](https://help.github.com/en/articles/about-issue-and-pull-request-templates)
|SECURITY.|A SECURITY file gives instructions for how to responsibly report a security vulnerability in your project. For more information, see ["Adding a security policy to your repository."](https://help.github.com/en/articles/adding-a-security-policy-to-your-repository)
|SUPPORT.md|A SUPPORT file lets people know about ways to get help with your project. For more information, see ["Adding support resources to your project."](https://help.github.com/en/articles/adding-support-resources-to-your-project)

You cannot create a default license file. License files must be added to individual repositories so the file will be included when a project is cloned, packaged, or downloaded.
