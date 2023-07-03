# Awesome Jetbrains Plugins

A curated list of Jetbrains plugins. Most of the plugins are compatible with all Jetbrains IDEs (IntelliJ IDEA, PyCharm,
WebStorm, PhpStorm, Rider, CLion, RubyMine, GoLand, Aqua, Android Studio). IDE specific plugins are placed in "Language
specific" section. Also keep in mind, that all of Jetbrains IDEs have great out-of-the-box support for programming
languages itself and major frameworks, which are enabled by default, so there is no sense to include them into this
list.

* [Awesome Jetbrains Plugins](#awesome-jetbrains-plugins)
    * [UI](#ui)
    * [Code Editor](#code-editor)
    * [Utilities](#utilities)
    * [Version Control](#version-control)
    * [Tools](#tools)
        * [Additional file types support](#additional-file-types-support)
        * [Integrations with other tools](#integrations-with-other-tools)
        * [Miscellaneous](#miscellaneous)
        * [Cloud/DevOps Tools](#clouddevops-tools)
    * [Language specific](#language-specific)
        * [Javascript/Typescript](#javascripttypescript)
            * [Javascript/Typescript Frameworks](#javascripttypescript-frameworks)
        * [Java](#java)
            * [Java Frameworks](#java-frameworks)
        * [Python](#python)
            * [Python Frameworks](#python-frameworks)
        * [C#](#c)
            * [C# Frameworks](#c-frameworks)
        * [PHP](#php)
            * [PHP Frameworks](#php-frameworks)
        * [C/C++](#cc)
        * [Rust](#rust)
        * [Go](#go)
    * [AI Code Completion](#ai-code-completion)
    * [Themes](#themes)
    * [Fun](#fun)

## UI

* [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x)
    * Helps to learn essential shortcuts while you are working. When you use the mouse on a button inside the IDE, the
      Key Promoter X shows you the keyboard shortcut that you should have used instead.
* [Presentation Assistance](https://plugins.jetbrains.com/plugin/7345-presentation-assistant)
    * Helps others to lear, which shortcuts you are using, by showing name and keyboard shortcuts of any action you
      invoke. Usefully during screen sharing and pair programming.
* [Extra Icons](https://plugins.jetbrains.com/plugin/11058-extra-icons)
    * Adds 500+ icons for files like Travis YML, GitLab YML, Angular files, etc.
* [CodeGlance Pro](https://plugins.jetbrains.com/plugin/18824-codeglance-pro)
    * Displays a zoomed out overview of source code into editor pane(similar to Sublime Text). The minimap allows for
      quick scrolling letting you jump straight to sections of code.
* [Extra ToolWindow Colorful Icons](https://plugins.jetbrains.com/plugin/16604-extra-toolwindow-colorful-icons)
    * Makes tool window icons colorful. Extremely helpful with "New UI".

## Code Editor

* [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
    * Adds support of Modal Editing concept from Vim. Can greatly increase your productivity, if you will adopt it.
    * Modal Editing is a concept where the behavior of a text editor depends on the current mode it is in. Vim has three
      modes: Normal Mode for navigation and editing commands, Insert Mode for directly typing and editing text, and
      Visual Mode for selecting and manipulating blocks of text.
* [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)
    * Allows to quickly navigate the caret to any position visible in the editor.
* [HighlightBracketPair](https://plugins.jetbrains.com/plugin/17320-highlightbracketpair)
    * Highlights current bracket pair.
* [Better Highlights](https://plugins.jetbrains.com/plugin/12895-better-highlights)
    * Allows to colorize comments and language keyword. Enables ability to reference source code and files in comments.
* [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)
    * Colorize nearly placed brackets.
* [Indent Rainbow](https://plugins.jetbrains.com/plugin/13308-indent-rainbow)
    * Colorize the indentations.

## Utilities

* [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
    * Various tools to manipulate plain strings. For example, sorting, filtering, case switching etc. You can add
      shortcut for any operation, most usefull one would be shortcut to switch between cases.
* [Custom Postfix Templates](https://plugins.jetbrains.com/plugin/9862-custom-postfix-templates)
    * Adds additional postfix autocompletion templates for various languages. By default, no templates are present. You
      need to spend time to find out templates useful for your language/project and manually add them as "Web Template".
* [Json Helper](https://plugins.jetbrains.com/plugin/13873-json-helper)
    * Various tools to manipulate JSON. For example, json path searching, escape/unescape, uglify/prettify etc.
* [Randomness](https://plugins.jetbrains.com/plugin/9836-randomness)
    * Generate and insert random numbers, strings, and UUIDs. Useful in unit tests.
* [Shifter](https://plugins.jetbrains.com/plugin/6149-shifter)
    * Various tools to manipulate code strings. For example, shifting keywords/quotes/string literals in array,
      incrementing/decrementing int strings etc.

## Version Control

* [.ignore](https://plugins.jetbrains.com/plugin/7495--ignore)
    * Improve work with .gitignore file by adding syntax highlight, generate rules for .gitignore, entries inspection
      etc.
* [GitToolBox](https://plugins.jetbrains.com/plugin/7499-gittoolbox)
    * Improve work with git by enabling autocompletion, displaying various additional info, like number of ahead commits
      etc., branches clean up, auto-fetch and various other functions.
* [GitLive](https://plugins.jetbrains.com/plugin/11955-gitlive)
    * Main feature is real time merge conflict detection.
* [Conventional Commit](https://plugins.jetbrains.com/plugin/13389-conventional-commit)
    * Provides autocompletion for [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), also named
      semantic commits, inside the VCS Commit dialog.
* [Azure DevOps](https://plugins.jetbrains.com/plugin/7981-azure-devops)
    * Enable working with Git and TFVC repositories on Azure DevOps Services or Team Foundation Server(TFS).

## Tools

### Additional file types support

* [PlantUML Integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)
    * PlantUML diagramming tool integration, which allows to create diagrams from a plain text language.
* [PDF Viewer](https://plugins.jetbrains.com/plugin/14494-pdf-viewer)
    * Allows to view PDF files in IDE.
* [CSV Editor](https://plugins.jetbrains.com/plugin/10037-csv-editor)
    * Allows to edit CSV files in a colored table- & text-editor. It provides syntax-validation, highlighting,
      customization, and plenty more besides.
* [Easy I18n](https://plugins.jetbrains.com/plugin/16316-easy-i18n)
    * Allows to edit translation files(json, yaml, properties) in a tree or table view.
* [.env files support](https://plugins.jetbrains.com/plugin/9525--env-files-support)
    * Allows to edit environment variables files with autocompletion and syntax highlighting.
* [Ideolog](https://plugins.jetbrains.com/plugin/9746-ideolog)
    * Interactive viewer for '.log' files with additional syntax highlighting.
* [OpenCV Image Viewer](https://plugins.jetbrains.com/plugin/14371-opencv-image-viewer)
    * Displays an OpenCV Image (ndarray or Mat) without stopping the debugger with additional tools.

### Integrations with other tools

* [SonarLint](https://plugins.jetbrains.com/plugin/7973-sonarlint)
    * Plugin for SonarQube for static code analysis.
* [Gitlab Helper](https://plugins.jetbrains.com/plugin/20347-gitlab-helper)
    * Adds integration with GitLab - mange Merge Requests, Pipelines etc.
* [New Relic CodeStream: GitHub, GitLab, PRs and Code Review](https://plugins.jetbrains.com/plugin/12206-new-relic-codestream-github-gitlab-prs-and-code-review)
    * Adds integration with task management and version control tools(bitbucket, jira, gitlab, github etc.), which
      allows to do everything from IDE. Also contains collaboration tools and integrations with Slack and Teams.
      CodeStream itself and plugin are free, so it is definitely worth to try.

### Miscellaneous

* [Archive Browser](https://plugins.jetbrains.com/plugin/9491-archive-browser)
    * Allows to browse files inside archives including nested archives. Nested .jar files are also supported.
* [Grep Console](https://plugins.jetbrains.com/plugin/7125-grep-console)
    * Also to tail, filter, highlight etc. inside IDE terminal.
* [Json Parser](https://plugins.jetbrains.com/plugin/10650-json-parser)
    * UI to validate and format JSON strings
* [Multirun](https://plugins.jetbrains.com/plugin/7248-multirun)
    * Group multiple run configurations and run them at once in a single click.
* [Run Configuration as Action](https://plugins.jetbrains.com/plugin/9448-run-configuration-as-action)
    * Register all run configuration as actions to assign shortcuts for them.

### Cloud/DevOps Tools

* [AWS Toolkit](https://plugins.jetbrains.com/plugin/11349-aws-toolkit)
    * Adds integration with AWS into IDE - resource explorer, run/debug lambda, logs, s3 explorer etc.
* [Azure Toolkit for Rider](https://plugins.jetbrains.com/plugin/11220-azure-toolkit-for-rider)
    * Jetbrains plugin for integration with Azure into IDE - resource explorer, run/debug Azure Functions etc.
* [Azure Toolkit for IntelliJ](https://plugins.jetbrains.com/plugin/8053-azure-toolkit-for-intellij)
    * Microsoft plugin for integration with Azure into IDE - resource explorer, run/debug Azure Functions etc.
* [Application Insights Debug Log Viewer]()
    * Show Azure Application Insights logs during application debug session.
* [Kubernetes](https://plugins.jetbrains.com/plugin/10485-kubernetes)
    * Advanced editor for kubernetes and helm configs with runtime support for k8s cluster and pods (attaching pod
      console, viewing logs etc).
* [Jenkins Control](https://plugins.jetbrains.com/plugin/6110-jenkins-control)
    * Adds integration with Jenkins - trigger jobs, view job logs etc.
* [Terraform and HCL](https://plugins.jetbrains.com/plugin/7808-terraform-and-hcl)
    * Add IDE capabilities for HCL and HIL files (autocomplete, syntax highlight etc).
* [BashSupport Pro](https://plugins.jetbrains.com/plugin/13841-bashsupport-pro)
    * Add IDE capabilities for shell scripting (autocomplete, syntax highlight etc).
* [PowerShell](https://plugins.jetbrains.com/plugin/10249-powershell)
    * Add IDE capabilities for PowerShell scripting (autocomplete, syntax highlight etc).

## Language specific

### Javascript/Typescript

* [Quokka](https://plugins.jetbrains.com/plugin/9667-quokka)
    * Javascript playground inside editor. Allows to write and test code on the fly with access to project files.
* [Wallaby](https://plugins.jetbrains.com/plugin/15742-wallaby)
    * Intelligent test runner for JavaScript that continuously runs your tests. It reports code coverage and other
      results to your code editor immediately as you change your code.
* [Run configuration for Typescript](https://plugins.jetbrains.com/plugin/10841-run-configuration-for-typescript)
    * Simplifies running of TS files.
* [LogIt](https://plugins.jetbrains.com/plugin/13432-logit)
    * Inserts "console.log" function via shortcut.

#### Javascript/Typescript Frameworks

* [GraphQL](https://plugins.jetbrains.com/plugin/8097-graphql)
    * Support for GraphQL. Schema-aware completion, syntax highlighting etc.
* [Angular Component Folding](https://plugins.jetbrains.com/plugin/10090-angular-component-folding)
    * Groups files which have same name and different extensions.
* [IntelliVue](https://plugins.jetbrains.com/plugin/12014-intellivue)
    * Provides analysis, actions, and utilities for Vue Single File Components. This plugin adds additional
      functionality on top of the standard Vue plugin.
* [React Buddy](https://plugins.jetbrains.com/plugin/17467-react-buddy)
    * Provides component palettes for MUI (MaterialUI), Ant Design, Chakra UI, Mantine. Helps to create and use
      Storybook stories.
* [React Native Console](https://plugins.jetbrains.com/plugin/9564-react-native-console)
    * Run React Native commands and makes RN coding easier.

### Java

* [RoboPOJOGenerator](https://plugins.jetbrains.com/plugin/8634-robopojogenerator)
    * Generate POJO classes from JSON and other formats.
* [GenerateAllSetter](https://plugins.jetbrains.com/plugin/9360-generateallsetter)
    * Generate setters on object. Useful for mappers and converters.
* [Innerbuilder Generator](https://plugins.jetbrains.com/plugin/15615-innerbuilder-generator)
    * Generates Builder class inside chosen one.

#### Java Frameworks

* [Maven Helper](https://plugins.jetbrains.com/plugin/7179-maven-helper)
    * Extends maven support with additional useful features, like analyzing and excluding dependencies.
* [JPA Buddy](https://plugins.jetbrains.com/plugin/15075-jpa-buddy)
    * Extends support for DB related tools(Hibernate, Spring Data, Flyway, MapStruct etc.) with additional inspections,
      generation wizards, automatic generation of DB migrations etc.
* [Spring Boot Helper](https://plugins.jetbrains.com/plugin/18622-spring-boot-helper)
    * Extends support for Spring Boot - start initializr, autocomplete Spring Boot/Cloud configuration key/value, Spring
      reference configuration, Spring metadata documentation.

### Python

* [Python Security](https://plugins.jetbrains.com/plugin/13609-python-security)
    * Adds additional static code analysis inspections for Python.
* [Python Annotations](https://plugins.jetbrains.com/plugin/12035-python-annotations)
    * Provides quickfixes for common mistakes in type annotations.
* [Pylint](https://plugins.jetbrains.com/plugin/11084-pylint)
    * Adds pylint static code analysis integration into IDE.

#### Python Frameworks

* [Requirements](https://plugins.jetbrains.com/plugin/10837-requirements)
    * Improve work with requirements.txt file by adding syntax highlight, package version inspections, autocomplete etc.
* [Django command runner](https://plugins.jetbrains.com/plugin/13834-django-command-runner)
    * Simply run django management command from definition file.
* [Odoo](https://plugins.jetbrains.com/plugin/13499-odoo)
    * Provides Odoo framework support (code autocompletion, code navigation etc.)
* [Odoo Autocompletion Support](https://plugins.jetbrains.com/plugin/13083-odoo-autocompletion-support)
    * Provides enhanced autocompletion for Odoo addon/module.

### C#

* [Heap Allocations Viewer](https://plugins.jetbrains.com/plugin/9223-heap-allocations-viewer)
    * Highlights local object allocations, boxing, delegates and closure creations points.
* [Rossynt](https://plugins.jetbrains.com/plugin/16902-rossynt)
    * Roslyn's syntax tree viewer for C#.

#### C# Frameworks

* [.NET Core User Secrets](https://plugins.jetbrains.com/plugin/10183--net-core-user-secrets)
    * Adds the ability to create and open ASP.NET User Secrets.
* [Structured Logging](https://plugins.jetbrains.com/plugin/12832-structured-logging)
    * Analyzers for structured logging. Supports Serilog, NLog, and Microsoft.Extensions.Logging.
* [MoqComplete](https://plugins.jetbrains.com/plugin/12659-moqcomplete)
    * Code completion for Moq.

### PHP

* [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-)
    * Adds additional static code analysis inspections for PHP.
* [PHP Toolbox](https://plugins.jetbrains.com/plugin/8133-php-toolbox)
    * Improves autocompletion for PHP and common used frameworks/libraries (Doctrine, Twig etc.)
* [PHP Annotations](https://plugins.jetbrains.com/plugin/7320-php-annotations)
    * Extends PhpStorm to support annotations in DocBlocks and provide additional Attributes features.
* [deep-assoc-completion](https://plugins.jetbrains.com/plugin/9927-deep-assoc-completion)
    * The plugin allows you to have auto-completion for PHP array keys inferred from other functions.

#### PHP Frameworks

* [Laravel Idea](https://plugins.jetbrains.com/plugin/13441-laravel-idea/reviews)
    * Add support for Laravel framework.
* [Symfony Support](https://plugins.jetbrains.com/plugin/7219-symfony-support)
    * Add support for Symfony framework.
* [Yii2 Support](https://plugins.jetbrains.com/plugin/9388-yii2-support)
    * Add support for Yii2 framework.
* [PHPUnit Enhancement](https://plugins.jetbrains.com/plugin/9674-phpunit-enhancement)
    * Autocompletion and code navigation for PHPUnit.

### C/C++

* [C/C++ Coverage](https://plugins.jetbrains.com/plugin/11031-c-c--coverage)
    * C and C++ Line, Region and Branch Coverage gatherer for GCC and Clang.
* [EzArgs](https://plugins.jetbrains.com/plugin/16411-ezargs)
    * Provides option to pass arguments to C++ run configurations by simply writing them in dropdown box on the toolbar.
* [Compiler Explorer](https://plugins.jetbrains.com/plugin/11064-compiler-explorer)
    * Shows compilation results from a remote Compiler Explorer instance.
* [Bazel for CLion](https://plugins.jetbrains.com/plugin/9554-bazel-for-clion)
    * Google plugin to add support for Bazel build.
* [CMake Plus]()
    * Extend CMake language support (highlighting, code navigation, inspections etc).

### Rust

* [RON Extended Support](https://plugins.jetbrains.com/plugin/15878-ron-extended-support)
    * Adds support for Rusty Object Notation files (code completion, syntax highlighting etc).

### Go

* [Go Linter](https://plugins.jetbrains.com/plugin/12496-go-linter/reviews)
    * Provides golangci-lint inspection and autofix on-the-fly

## AI Code Completion

* [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot)
    * Enables GitHub Copilot integration with IDE.
* [Tabnine AI Code Completion- JS Java Python TS Rust Go PHP & More](https://plugins.jetbrains.com/plugin/12798-tabnine-ai-code-completion-js-java-python-ts-rust-go-php--more)
    * Enables Tabnine integration with IDE.
* [AWS Toolkit](https://plugins.jetbrains.com/plugin/11349-aws-toolkit)
    * Enables Amazon CodeWhisperer integration with IDE.

## Themes

* [Material UI](https://plugins.jetbrains.com/plugin/8006-material-theme-ui)
* [Gerry Themes Pro](https://plugins.jetbrains.com/plugin/19668-gerry-themes-pro)
* [Gruvbox - Theme](https://plugins.jetbrains.com/plugin/20558-gruvbox--theme)
* [One Dark](https://plugins.jetbrains.com/plugin/11938-one-dark-theme)
* [Nord](https://plugins.jetbrains.com/plugin/10321-nord)

## Fun

* [Nyan Progress Bar](https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar)
* [Gopher](https://plugins.jetbrains.com/plugin/12875-gopher)
* [Waifu Motivator](https://plugins.jetbrains.com/plugin/13381-waifu-motivator)
* [Power Mode II](https://plugins.jetbrains.com/plugin/8251-power-mode-ii)
* [Anime Memes](https://plugins.jetbrains.com/plugin/15865-anime-memes)
