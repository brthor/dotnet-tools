# dotnet-tools

A list of tool extensions for .NET Core Command Line (dotnet CLI).

These tools can be installed by executing

    dotnet tool install -g $packageId

After installing, the tool should be available by running

    $commandName

You don't need to run `"dotnet $commandName"`, just `$commandName`

The CLI also supports an older format called "project tools" or `<DotNetCliToolReference>`. A list of project tools is [available here](./project-tools.md).

> Pro-tip: global tools do not need to be named "dotnet-*". This is only a convention used some authors as a way to indicate a package is meant to be a command line tool, and not a normal library reference.

Command           | Package Id | Author | Description
------------------|------------|--------|--------------
`altcover` | [altcover.global](https://www.nuget.org/packages/altcover.global/) | [@SteveGilham](https://github.com/SteveGilham) | Cross-platform code line and branch coverage tool-set for .net core/.net framework/mono
`altcover.visualizer` | [altcover.visualizer](https://www.nuget.org/packages/altcover.visualizer/) | [@SteveGilham](https://github.com/SteveGilham) | Code coverage display tool to show which parts of your code _aren't_ being covered.  Requires GTK+3 installed separately
`certes` | [dotnet-certes](https://www.nuget.org/packages/dotnet-certes/) | [@fszlin](https://github.com/fszlin) | CLI tool for acquire certificates via the Automated Certificate Management Environment (ACME) protocol (example: LetsEncrypt.org)  [GitHub](https://github.com/fszlin/certes)
`coverlet` | [coverlet.console](https://www.nuget.org/packages/coverlet.console/) | [@tonerdo](https://github.com/tonerdo) | Coverlet is a cross platform code coverage library for .NET Core, with support for line, branch and method coverage. [GitHub](https://github.com/tonerdo/coverlet)
`csproj-to-2017` | [Project2015To2017.Cli](https://www.nuget.org/packages/Project2015To2017.Cli/) | [@hvanbakel](https://github.com/hvanbakel) | CLI tool for converting old csproj files to the new VS2017 csproj format  [GitHub](https://github.com/hvanbakel/CsprojToVs2017)
`dmd5` | [dmd5](https://www.nuget.org/packages/dmd5) | [@Rwing](https://github.com/Rwing) | Just generate MD5 hash value in CLI.  [GitHub](https://github.com/Rwing/Dotnet.Tool.MD5)
`docker-watch` | [docker-watch](https://www.nuget.org/packages/docker-watch) | [@nickvdyck](https://github.com/nickvdyck) | A command line utility to notify docker mounted volumes about changes on Windows.  [GitHub](https://github.com/nickvdyck/docker-watch)
`docs` | [dotnet-doc](https://www.nuget.org/packages/dotnet-doc/) | [@spboyer](https://github.com/spboyer) | Search [docs.microsoft.com](https://docs.microsoft.com) using the command line.  [GitHub](https://github.com/spboyer/dotnet-doc)
`dotnet-aop` | [dotnet-aop](https://www.nuget.org/packages/dotnet-aop) | [@ignatandrei](https://github.com/ignatandrei/) | A tool to make AOP for .cs files for your CI pipeline.  [GitHub](https://github.com/ignatandrei/AOP_With_Roslyn)
`dotnet-aspnet-codegenerator` | [dotnet-aspnet-codegenerator](https://www.nuget.org/packages/dotnet-aspnet-codegenerator/) | [@aspnet](https://github.com/aspnet)  | Code generation tool for creating controllers, views, and models in ASP.NET Core projects.   [GitHub](https://github.com/aspnet/Scaffolding)
`dotnet-cake` |  [Cake.Tool](https://www.nuget.org/packages/Cake.Tool/) | [@cake-build](https://github.com/cake-build/) | A tool to run cross platform Cake build scripts. [GitHub](https://github.com/cake-build/cake)
`dotnet-config2json` | [dotnet-config2json](https://www.nuget.org/packages/dotnet-config2json/) | [@andrewlock](https://github.com/andrewlock/) | A simple tool to convert a web.config file to an appsettings.json file.  [GitHub](https://github.com/andrewlock/dotnet-config2json)
`dotnet-cowsay` | [dotnet-cowsay](https://www.nuget.org/packages/dotnet-cowsay/) | [@isaac2004](https://github.com/isaac2004) |CLI Tool that gives a a random blog post from discoverdot.net in cowsay format.  [GitHub](https://github.com/isaac2004/dotnet-cowsay/)
`dotnet-dbinfo` | [dotnet-dbinfo](https://www.nuget.org/packages/dotnet-dbinfo/) | [@berkid89](https://github.com/berkid89) | A simple cross-platform command-line tool for get useful database information (in json format).  [GitHub](https://github.com/berkid89/dotnet-dbinfo)
`dotnet-depends` | [dotnet-depends](https://www.nuget.org/packages/dotnet-depends/) | [@mholo65](https://github.com/mholo65) | Dependency explorer for .NET. [Github](https://github.com/mholo65/depends)
`dotnet-eb` | [dotnet-eb](https://www.nuget.org/packages/Amazon.ElasticBeanstalk.Tools/) | [@aws](https://github.com/aws) | Tools to deploy ASP.NET Core apps to AWS Elastic Beanstalk. Global tool started at version 3.0.0. [Github](https://github.com/aws/aws-extensions-for-dotnet-cli)
`dotnet-ecs` | [dotnet-ecs](https://www.nuget.org/packages/Amazon.ECS.Tools/) | [@aws](https://github.com/aws) | Tools to deploy containers to Amazon Elastic Container Service functions. Global tool started at version 3.0.0. [Github](https://github.com/aws/aws-extensions-for-dotnet-cli)
`dotnet-encrypto` | [dotnet-encrypto](https://www.nuget.org/packages/dotnet-encrypto) | [@tomchavakis](https://github.com/tomchavakis) | A tool to encrypt/decrypt folder or files using AES 256 Encryption Algorithm [Github](https://github.com/tomchavakis/encrypto)
`dotnet-fm` | [FluentMigrator.DotNet.Cli](https://www.nuget.org/packages/FluentMigrator.DotNet.Cli/) | [@FluentMigrator](https://github.com/fluentmigrator) | FluentMigrator: Is a database migration framework for .NET much like Ruby on Rails Migrations.  [GitHub](https://fluentmigrator.github.io/articles/runners/dotnet-fm.html)
`dotnet-hash` | [TheBlueSky.DotNet.Tools.SwiftHash](https://www.nuget.org/packages/TheBlueSky.DotNet.Tools.SwiftHash/) | [@TheBlueSky](https://github.com/TheBlueSky) | A simple dotnet tool to calculate hashes for the given file. [GitHub](https://github.com/TheBlueSky/dotnet-hash)
`dotnet-ignore` | [dotnet-ignore](https://www.nuget.org/packages/dotnet-ignore/) | [@Arasz](https://github.com/Arasz) | Global .NET Core tool that can download .gitignore file from github gitignore repository.  [GitHub](https://github.com/Arasz/dotnet-ignore)
`dotnet-lambda` | [dotnet-lambda](https://www.nuget.org/packages/Amazon.Lambda.Tools/) | [@aws](https://github.com/aws) | Tools to deploy AWS Lambda functions. Global tool started at version 3.0.0. [Github](https://github.com/aws/aws-extensions-for-dotnet-cli)
`dotnet-obfuscar` | [dotnet-obfuscar](https://www.nuget.org/packages/Obfuscar.GlobalTool/) | [@lextm](https://github.com/lextm) | A .NET Core global tool to obfuscate assemblies.  [GitHub](https://github.com/obfuscar/obfuscar)
`dotnet-outdated` | [dotnet-outdated](https://www.nuget.org/packages/dotnet-outdated/) | [@jerriep](https://github.com/jerriep) | A .NET Core global tool to display outdated NuGet packages in a project.  [GitHub](https://github.com/jerriep/dotnet-outdated)
`dotnet-property`| [dotnet-property ](https://www.nuget.org/packages/dotnet-property) | [@pwelter34](https://github.com/loresoft) | .NET Core command-line (CLI) tool to update project properties and version numbers on build. [GitHub](https://github.com/loresoft/DotNet.Property)
`dotnet-retire`| [dotnet-retire](https://www.nuget.org/packages/dotnet-retire) | [@johnkors](https://github.com/johnkors) |  A dotnet CLI extension to check your project for known vulnerabilities. [GitHub](https://github.com/retirenet/dotnet-retire)
`dotnet-runas`| [dotnet-runas](https://www.nuget.org/packages/dotnet-runas) | [@NikolayPianikov](https://github.com/NikolayPianikov) |  Allows to run a dotnet process under a specified user account. [GitHub](https://github.com/JetBrains/runAs)
`dotnet-script` | [dotnet-script](https://www.nuget.org/packages/dotnet-script/) | [@filipw](https://github.com/filipw) [@seesharper](https://github.com/seesharper) | Run C# scripts from the .NET CLI.  [GitHub](https://github.com/filipw/dotnet-script)
`dotnet-search` | [dotnet-search](https://www.nuget.org/packages/dotnet-search/) | [@billpratt](https://github.com/billpratt) | Search for Nuget packages using the .NET Core CLI.  [GitHub](https://github.com/billpratt/dotnet-search)
`dotnet-serve` | [dotnet-serve](https://www.nuget.org/packages/dotnet-serve/) | [@natemcmaster](https://github.com/natemcmaster) | A simple command line HTTP server, no code required.  [GitHub](https://github.com/natemcmaster/dotnet-serve)
`dotnet-sonarscanner` | [dotnet-sonarscanner](https://www.nuget.org/packages/dotnet-sonarscanner) | [@SonarSource](https://github.com/SonarSource) | The SonarScanner for MSBuild is the recommended way to launch a SonarQube or SonarCloud analysis for projects/solutions using dotnet command as build tool.  [GitHub](https://github.com/SonarSource/sonar-scanner-msbuild)
`dotnet-sshdeploy` | [dotnet-sshdeploy](https://www.nuget.org/packages/dotnet-sshdeploy) | [@Unosquare](https://github.com/unosquare) | A dotnet CLI command that enables quick deployments over SSH.  [GitHub](https://github.com/unosquare/sshdeploy)
`dotnet-thx` | [DotnetThx](https://www.nuget.org/packages/DotnetThx) | [@krystiankolad](https://github.com/KrystianKolad) | Find authors of packages you are using in you project and visit their GitHub. [Github](https://github.com/KrystianKolad/DotnetThx)
`dotnet-xdt` | [dotnet-xdt](https://www.nuget.org/packages/dotnet-xdt/) | [@nil4](https://github.com/nil4) | Global tool for applying XML Document Transformations to .NET configuration files, or any other XML-structured content.  [GitHub](https://github.com/nil4/dotnet-transform-xdt)
`dotnetrsa` | [dotnetrsa](https://www.nuget.org/packages/dotnetrsa) | [@stulzq](https://github.com/stulzq) | Generate rsa pkcs1, pkcs8, xml format key. Conversion between the three formats.  [GitHub](https://github.com/stulzq/DotnetRSA)
`flubu` | [FlubuCore.GlobalTool](https://www.nuget.org/packages/FlubuCore.GlobalTool) | [@FlubuCore](https://github.com/flubu-core) | Fluent Builder. A cross platform build automation tool for building projects and executing deployment scripts using C# code.  [GitHub](https://github.com/flubu-core/flubu.core)
`ghi` | [github-issues-cli](https://www.nuget.org/packages/github-issues-cli/) | [@jerriep](https://github.com/jerriep) | A simple command-line client for managing GitHub Issues.  [GitHub](https://github.com/jerriep/github-issues-cli)
`giphy` | [GiphyCli](https://www.nuget.org/packages/GiphyCli/) | [@DavidDeSloovere](https://github.com/DavidDeSloovere) | Find that giphy fast and just copy the url or markdown.  [GitHub](https://github.com/DavidDeSloovere/giphy-cli)
`git-status` | [git-status-cli](https://www.nuget.org/packages/git-status-cli/) | [@jerriep](https://github.com/jerriep) | A simple command-line utility to determine status of all Git repositories in a directory structure.  [GitHub](https://github.com/jerriep/git-status-cli)
`gti` | [gti](https://www.nuget.org/packages/gti/) | [@shaun-h](https://github.com/shaun-h) | Global tool for installing .Net Global tools from a tools.gti file. [GitHub](https://github.com/shaun-h/gti)
`html-copy-vscode` | [HtmlCopyVSCode](https://www.nuget.org/packages/HtmlCopyVSCode/) | [@slang25](https://github.com/slang25/) | A global tool to convert snippets copied from VS Code into plain html to paste into your blog.  [GitHub](https://github.com/slang25/html-copy-vscode)
`LocalAppVeyor` | [localappveyor](https://www.nuget.org/packages/localappveyor) | [@joaope](https://github.com/joaope) | .NET Core global tool which brings appveyor.yml to the center of your build process by making possible to execute its build jobs, locally.  [GitHub](https://github.com/joaope/localappveyor)
`nuke` | [Nuke.GlobalTool](https://www.nuget.org/packages/Nuke.GlobalTool) | [@nuke-build](https://github.com/nuke-build) | Run and setup NUKE builds with a single command on any platform :rocket:  [GitHub](https://github.com/nuke-build/nuke)
`NuKeeper` | [NuKeeper](https://www.nuget.org/packages/NuKeeper) | [@AnthonySteele](https://github.com/anthonysteele) | Find outdated NuGet packages and apply updates to them.  [GitHub](https://github.com/NuKeeperDotNet/NuKeeper)
`nyancat` | [nyancat](https://www.nuget.org/packages/nyancat/) | [@nickvdyck](https://github.com/nickvdyck) | Nyancat 😻 in your terminal, rendered through ANSI escape sequences. A port of the original terminal application to make this cat run on dotnet core. 🐱‍🏍  [GitHub](https://github.com/nickvdyck/nyancat.cs)
`protogen` | [protobuf-net.Protogen](https://www.nuget.org/packages/protobuf-net.Protogen/) | [@mgravell](https://github.com/mgravell) | protobuf-net code-generation from .proto schema files.   [GitHub](https://github.com/mgravell/protobuf-net)
`reportgenerator` | [dotnet-reportgenerator-globaltool](https://www.nuget.org/packages/dotnet-reportgenerator-globaltool) | [@danielpalme](https://github.com/danielpalme) | ReportGenerator converts XML reports generated by OpenCover, PartCover, dotCover, Visual Studio, NCover or Cobertura into human readable reports in various formats.  [GitHub](https://github.com/danielpalme/ReportGenerator/)
`rider` | [dotnet-rider-cli](https://www.nuget.org/packages/dotnet-rider-cli) | [@markrendle](https://github.com/markrendle) | **Windows only** Adds a `rider` command to launch JetBrains Rider when it's installed via [Toolbox](https://jetbrains.com/toolbox/).  [GitHub](https://github.com/RendleLabs/dotnet-rider-cli/)
`sleet` | [Sleet](https://www.nuget.org/packages/Sleet/) | [@emgarten](https://github.com/emgarten) | A static NuGet feed generator.   [GitHub](https://github.com/emgarten/Sleet)
`srihash` | [srihash-cli](https://www.nuget.org/packages/srihash-cli) | [@natemcmaster](https://github.com/natemcmaster) | Generates the SRI hash for `<script>` tags in browsers  [GitHub](https://github.com/natemcmaster/srihash-cli)
`sysinfo` | [Elemental.SysInfoTool](https://www.nuget.org/packages/Elemental.SysInfoTool/) | [@markpflug](https://github.com/markpflug) | Outputs system information.  [GitHub](https://github.com/markpflug/Elemental.SysInfoTool)
`tcpmux` | [TcpMux](https://www.nuget.org/packages/TcpMux/) | [@nicodeslandes](https://github.com/nicodeslandes) | TCP Multiplexer; provide simple routing of TCP traffic as well as SSL re-encryption and off-loading.  [GitHub](https://github.com/nicodeslandes/TcpMux)
`unpkg` | [RendleLabs.UnpkgCli](https://www.nuget.org/packages/RendleLabs.UnpkgCli) | [@markrendle](https://github.com/markrendle) | Front-end package manager that uses the [unpkg.com](https://unpkg.com) CDN as a source. No Node.js, NPM or Bower required.  [GitHub](https://github.com/RendleLabs/dotnet-unpkg)
`versioninfo` | [dotnet-versioninfo](https://www.nuget.org/packages/dotnet-versioninfo/) | [@taylorjg](https://github.com/taylorjg) | Display version information of .NET Core assemblies. [GitHub](https://github.com/taylorjg/dotnet-versioninfo)
`weeknumber` | [weeknumber](https://www.nuget.org/packages/weeknumber/) | [@MarkusLund](https://github.com/MarkusLund) | Prints the current weeknumber to the command line.  [GitHub](https://github.com/MarkusLund/weeknumber)
`xscgen` | [dotnet-xscgen](https://www.nuget.org/packages/dotnet-xscgen/) | [@mganss](https://github.com/mganss) | Generate XmlSerializer compatible C# classes from XML Schema files.  [GitHub](https://github.com/mganss/XmlSchemaClassGenerator)

<!-- Contributors: when adding a new item to the list, please help me keep this list sorted by command name in alphabetical order. Thanks! -->
