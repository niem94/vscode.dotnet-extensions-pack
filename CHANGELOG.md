# Change Log

All notable changes to the "dotnet-extensions-pack" extension pack are in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [1.2.3] - 2021-08-29

- Removed "XML Tools", ".NET Core Tools" and "Prettier". These are not needed for .NET development.

## [1.2.2] - 2021-08-27

- Removed "C# Extensions" and "NuGet Package Manager", as i rarely use them.

## [1.2.1] - 2021-08-24

- Removed Coverage Gutters. I rarely used it, and its easier just to check this info in Pull Requests with Codecov or similar tools.

## [1.2.0] - 2021-07-29

- Removed C# Extensions as i rarely used its features

## [1.1.9] - 2021-04-27

- Changed database tooling from "SQL Server by Microsoft" to "SQLTools with MSQL Driver". "SQL Server by Microsoft" forces configuration in the global settings, which i do not like, as i want my db connections to be saved only to workspaces. Also SQLTools seems like a much more capable tooling.

## [1.1.8] - 2021-04-23

- Added "C# Extensions" to be able to add Classes and Interfaces from the "right click" context menu. 

## [1.1.6] - 2021-04-09

- Added "Microsoft.AspNetCore.Razor.VSCode.BlazorWasmDebuggingExtension" to improve Blazor Development

## [1.1.5] - 2021-04-09

- Removed "vscode-solution-explorer" as it conflicts with the paste action and thus is a huge annoyance.

## [1.1.4] - 2021-04-02

- Removed IntelliCode as it does not work with C# code.

## [1.1.3] - 2021-03-22

- Added XML Tools to allow for XML formatting in csproj files.

## [1.1.2] - 2021-03-03

- Removed old test explorer in favor of .NET Core Test Explorer by Jun Han, as the old one was not working very well in own projects.

## [1.1.1] - 2021-02-18

- Removed Redhat XML and Redhat YML, as they are not essential to working with dotnet, and I like the extension to be lightweight.
- Updated dates in the changelog. I had written 2020 for changes in 2021.

## [1.0.12] - 2021-02-10

- Added "vscode-solution-explorer"

## [1.0.11] - 2021-02-08

- Removed "C# Namespace Autocompletion" (there is built-in functionality to refactor namespaces in the C# Extension)

## [1.0.10] - 2021-02-05

- Added "NuGet Package Manager"

## [1.0.9] - 2020-12-03

- Added "C# Namespace Autocompletion"

## [1.0.8] - 2020-12-03

- Added Prettier primarily for CSS formatting for Blazor web development

## [1.0.7] - 2020-11-16

- Updated icon

## [1.0.4] - 2020-11-11

- Added Red Hat YAML

## [1.0.3] - 2020-11-11

- Added .NET Core Tools

## [1.0.2] - 2020-11-11

- Added Red Hat XML

## [1.0.0] - 2020-11-09

- Initial release
