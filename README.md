# GitHub Copilot and App Modernization

**Mitul A. Shah, Principal Technical Specialist** 

## Sections
- AppCat + GitHub Copilot
- .NET Conversions
- Prompting Best Practices
- Other Resources

### AppCat + GitHub Copilot
- **Compatibility Report Summarization and Guided Help:** GitHub Copilot Chat can guide you through the migration steps based on the AppCat report generated against your code.
- **Issue List – Ask Copilot How to Remediate:** Copilot Chat can suggest how to fix individual issues in the issue list, including sample code and architectural considerations.

### VB to C# Conversion
- **CodeConverter by icsharpcode:** An open-source Roslyn-based code conversion library and toolchain for converting VB.NET code into C#. It can convert a whole project at once, but the resulting code needs to be validated/fixed. The primary use case would be via the Visual Studio Plugin, but other automation tools (CLI, nuget package, etc.) exist.

### .NET Upgrade Assistant
- **Upgrade your app to the latest .NET versions:** Use Upgrade Assistant right from Visual Studio or CLI. The primary use case would be for ASP.NET MVC or generic class libraries/console apps, which can be upgraded to .NET 6+ for hosting on Linux.

### Prompting Best Practices
- **Provide Context:** Indicate relevant code to Copilot by highlighting code in an open file, opening related files in your IDE, using #file and @workspace, and documenting inputs and outputs for the code you want Copilot to generate.
- **Break Down Complex Tasks:** Break your overall goal into smaller, discrete tasks – one function, one piece of business logic, one file at a time. Document your overall task in a comment.
- **Give Copilot an Identity:** Ask Copilot to behave in a role that suits the task, such as a senior C# developer or a frontend developer skilled in React.
- **Embrace Chat:** Utilize Copilot Chat for the best results in modernization. Autocompletion and inline code generations are best if you are writing new code. Don’t be afraid to correct Copilot’s response.
- **Get Specific:** Start general and get more specific. Avoid ambiguous terms and provide detail when describing what you want, including libraries, packages, dependencies, and naming conventions.

## Other Resources
### AppCat + GitHub Copilot
- [GitHub Copilot Analysis, Customized Rules, and more come to the Azure Migrate application and code assessment - .NET Blog (microsoft.com)](https://devblogs.microsoft.com/dotnet/azure-migrate-application-and-code-assessment-march-2024-update/)

### YouTube
- [ASP.NET Community Standup - Assessing your app's Azure readiness](https://docs.github.com/en/copilot/using-github-copilot/prompt-engineering-for-github-copilot)

### VB Conversion
- [icsharpcode/CodeConverter: Convert code from C# to VB.NET and vice versa using Roslyn (github.com)](https://github.com/icsharpcode/CodeConverter)

### GitHub
- [CodeConverter Wiki - Best Practices](https://github.com/icsharpcode/CodeConverter/wiki)

### GitHub Copilot Best Practices
- [Prompt engineering for GitHub Copilot - GitHub Docs](https://docs.github.com/en/copilot/using-github-copilot/prompt-engineering-for-github-copilot)
- [How to use GitHub Copilot: Prompts, tips, and use cases - The GitHub Blog](https://github.blog/developer-skills/github/how-to-write-better-prompts-for-github-copilot/)
- [Using GitHub Copilot in your IDE: Tips, tricks, and best practices - The GitHub Blog](https://github.blog/developer-skills/github/how-to-use-github-copilot-in-your-ide-tips-tricks-and-best-practices/)

### Formal Learning
- [Get started with GitHub Copilot - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/get-started-github-copilot/)
- [Implement code improvement using GitHub Copilot tools - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/implement-code-improvements-using-github-copilot-tools/)
- [Guided project - Accelerate app development using GitHub Copilot tools - Training | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/guided-project-accelerate-app-development-using-github-copilot-tools/)
- [skills/copilot-codespaces-vscode: Develop with AI-powered code suggestions using GitHub Copilot and VS Code](https://github.com/skills/copilot-codespaces-vscode)