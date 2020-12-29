# Contributing

Welcome, and thank you for your interest in contributing to the AL developer tools! The goal of this document is to provide a high-level overview of how you can get involved.

## Asking Questions

Have a question? Rather than opening an issue, please ask use one of the following resources:

- [Business Central Community](https://community.dynamics.com/business/f/758)  
- [mibuso forum](https://forum.mibuso.com/categories/nav-three-tier)  
- [Dynamics User Group](https://dynamicsuser.net/nav/f/developers)  
  
The active community will be eager to assist you. Your well-worded question will serve as a resource to others searching for help.

## Reporting Issues

Have you identified a reproducible problem in the AL developer tools? Here's how you can make reporting your issue as effective as possible.

### Identify Where to Report

The Dynamics 365 Business Central team accepts feedback through multiple channels and repositories. Try to file the issue through the correct channel.

- For issues related to extensions authored by Microsoft, such as the `System Application` or the `Base Application` as well as event requests, use the [ALAppExtensions](https://github.com/Microsoft/ALAppExtensions) repository.
- For issues concerning versions of Business Central that are in mainstream support you should use the [support channel](README.README.MD).
- For new features in AL/Visual Studio Code language and tools, as well as Business Central in general, use [Business Central Ideas](https://aka.ms/bcideas). This will allow other members of the community to vote on your idea and will allow us to prioritize based accordingly.
- For issues related to bugs in the latest version of the AL Language extension for Visual Studio Code, use the current [GitHub repository](https://github.com/microsoft/al). You should always use the latest version of the AL Language extension when targetting any version of Business Central. If you are targetting NAV 2018 or older, please use the [support channel](README.README.MD).
- For suggestions and discussions on static analysis rules (code cop), use the current [GitHub repo](https://github.com/microsoft/al).

### Look For an Existing Issue

Before you create a new issue, please do a search in [open issues](https://github.com/microsoft/AL/issues) to see if the issue or feature request has already been filed.

Be sure to scan through the [most popular](https://github.com/microsoft/AL/issues?q=is%3Aopen+is%3Aissue+sort%3Areactions-%2B1-desc+) issues.

If you find your issue already exists, make relevant comments and add your [reaction](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments). Use a reaction in place of a "+1" comment:

- 👍 - upvote
- 👎 - downvote

If you cannot find an existing issue that describes your bug, create a new issue using the guidelines below.

### Writing Good Bug Reports and Feature Requests

File a single issue per problem. Do not enumerate multiple bugs or feature requests in the same issue.

Do not add your issue as a comment to an existing issue unless it's for the identical input. Many issues look similar, but have different causes.

The more information you can provide, the more likely someone will be successful at reproducing the issue and finding a fix.

Please include the following with each issue:

**1. Describe the bug**
A clear and concise description of what the bug is. 

**2. To Reproduce**
Steps and to reproduce the behavior:

1. Go to '...'

``` AL code snippet that demonstrates the issue or a link to a code repository the developers can easily pull down to recreate the issue locally ```

**Note:** Because the developers need to copy and paste the code snippet, including a code snippet as a media file (i.e. .gif) is not sufficient.

**3. Expected behavior**
A clear and concise description of what you expected to happen.

**4. Actual behavior**
A clear and concise description of what happened accompanied by images, animations, or a link to a video showing the issue occurring

**5. Versions:**

- AL Language. Go to Visual Studio Code → Extensions panel → AL Language 
- Visual Studio Code: Go to Visual Studio Code → Help → About
- Business Central. In the client search for: System Information
- List of extensions that you have installed

### Final Checklist

Please remember to do the following:

* [ ] Search the issue repository to ensure your report is a new issue

* [ ] Recreate the issue after disabling all extensions except the AL Language extension

* [ ] Simplify your code around the issue to better isolate the problem

### Follow Your Issue

Once submitted, your report will go into the [issue tracking](https://github.com/microsoft/AL/wiki/Issue-Tracking) workflow. Be sure to understand what will happen next, so you know what to expect, and how to continue to assist throughout the process.

## Support

If you have encountered an issue in a version of the AL compiler and developer tools that is in mainstream support, or in the application, platform, or another component of Dynamics 365 Business Central, please read the following articles on how to get support for the Dynamics 365 Business Central product:

- [Technical Support for Dynamics 365 Business Central](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/technical-support)
- [Managing Technical Support](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/manage-technical-support)

https://github.com/twbs/bootstrap/blob/main/.github/CONTRIBUTING.md

If your problem or idea is not addressed yet, [please open a new issue](https://github.com/microsoft/AL/issues/new/choose).

## Contributor License Agreement

This project welcomes contributions and suggestions. Most contributions require you to
agree to a Contributor License Agreement (CLA) declaring that you have the right to,
and actually do, grant us the rights to use your contribution. For details, visit
<https://cla.microsoft.com>.

When you submit a pull request, a CLA-bot will automatically determine whether you need
to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the
instructions provided by the bot. You will only need to do this once across all repositories using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.