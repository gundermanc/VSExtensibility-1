# Welcome to the VSExtensibility repository!
This repo is your hub for all [announcements](announcements.md) and documentation for ongoing and upcoming Visual Studio extensibility projects.  Documentation is currently available for the following:

* Out-of-Proc Extensibility SDK (see below)
* [Extensions to Language Server Protocol (LSP)](lsp/lsp-extensions-specifications.md) 

# VSExtensibility Website 
For a more readable experience for all of the repo's resources and documentation, please visit the [VSExtensibility site](https://vigilant-guide-985f0fe3.pages.github.io/new-extensibility-model/getting-started/create-your-first-extension.html)

# Visual Studio Out-Of-Process Extensibility SDK

While the existing model loads extensions in-process, the new extensibility model brings Visual Studio extensions out-of-process. This out-of-proc model gives you the opportunity to create more reliable, secure, and easier-to-write extensions while still providing the in-depth functionality the old model provides. The following documentation describes:

* The general architecture of the new extensibility model
* How to take advantage of the new extensibility model’s APIs
* How to compile and F5 debug an extension with the new model 
* Resources and code samples to get started writing an extension with the new model

For future updates please bookmark our [announcements](announcements.md) page

## Getting Started
* [Introduction to new out-of-process extensibility](new-extensibility-model/getting-started/oop-extensibility-model-overview.md)
* [Create your first extension](new-extensibility-model/getting-started/create-your-first-extension.md)

## Extension Guides
* [Parts of a new Visual Studio extension](new-extensibility-model/inside-the-sdk/extension-anatomy.md)
* [Parts of the SDK](new-extensibility-model/inside-the-sdk/inside-the-sdk.md)
* [Commands](new-extensibility-model/extension-guides/command/command.md)
* [Editor components](new-extensibility-model/extension-guides/editor/editor.md)
* [Rule based conditions](new-extensibility-model/inside-the-sdk/activation-constraints.md)

## Samples and walkthroughs
A Visual Studio solution containing all samples can be found at [Samples.sln](https://github.com/microsoft/VSExtensibility/tree/main/New_Extensibility_Model/Samples/Samples.sln).

* [Simple command handler](new-extensibility-model/getting-started/create-your-first-extension.md) ([Source](https://github.com/microsoft/VSExtensibility/tree/main/New_Extensibility_Model/Samples/SimpleRemoteCommandSample))
* [Markdown Linter](new-extensibility-model/extension-guides/markdown-linter-sample.md) ([Source](https://github.com/microsoft/VSExtensibility/tree/main/New_Extensibility_Model/Samples/MarkdownLinter))
* [Insert guid extension sample](https://github.com/microsoft/VSExtensibility/tree/main/New_Extensibility_Model/Samples/InsertGuidExtension)
* [Command registration, localization sample](https://github.com/microsoft/VSExtensibility/tree/main/New_Extensibility_Model/Samples/CommandRegistrationsSample)

## API Docs

The following two namespaces are primary extensibility surface provided by the SDK:

* [Microsoft.VisualStudio.Extensibility](new-extensibility-model/api/Microsoft.VisualStudio.Extensibility.md)
* [Microsoft.VisualStudio.Extensibility.Editor](new-extensibility-model/api/Microsoft.VisualStudio.Extensibility.Extensibility.editor.md)

The following assemblies contain classes related to infrastructure and underlying implementation for the wrappers in the SDK:

* [Microsoft.VisualStudio.Extensibility.Framework](new-extensibility-model/api/Microsoft.VisualStudio.Extensibility.Framework.md)
* [Microsoft.VisualStudio.Extensibility.Contracts](new-extensibility-model/api/Microsoft.VisualStudio.Extensibility.Contracts.md)
* [Microsoft.VisualStudio.Extensibility.EditorHostService](new-extensibility-model/api/Microsoft.VisualStudio.Extensibility.EditorHostService.md)
* [Microsoft.VisualStudio.ProjectSystem.Query](new-extensibility-model/api/Microsoft.VisualStudio.ProjectSystem.Query.md)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
