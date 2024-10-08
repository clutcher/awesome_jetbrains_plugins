# Awesome Jetbrains Plugins

A curated list of Jetbrains plugins. Most of the plugins are compatible with all Jetbrains IDEs (IntelliJ IDEA, PyCharm,
WebStorm, PhpStorm, Rider, CLion, RubyMine, GoLand, Aqua, Android Studio). IDE specific plugins are placed in "Language
specific" section. Also keep in mind, that all of Jetbrains IDEs have great out-of-the-box support for programming
languages itself and major frameworks, which are enabled by default, so there is no sense to include them into this
list.

* [Awesome Jetbrains Plugins](#awesome-jetbrains-plugins)
    * [UI](#ui)
    * [Code Editor](#code-editor)
    * [Navigation](#navigation)
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
        * [Kotlin](#kotlin)
        * [Android](#android)
        * [Python](#python)
            * [Python Frameworks](#python-frameworks)
        * [C#](#c)
            * [C# Frameworks](#c-frameworks)
        * [PHP](#php)
            * [PHP Frameworks](#php-frameworks)
        * [C/C++](#cc)
        * [Rust](#rust)
        * [Go](#go)
    * [AI/LLM Integrations](#aillm-integrations)
    * [Themes](#themes)
    * [Fun](#fun)

## UI

* [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x)
    * Helps to learn essential shortcuts while you are working. When you use the mouse on a button inside the IDE, the
      Key Promoter X shows you the keyboard shortcut that you should have used instead.
* [Window Resizer](https://plugins.jetbrains.com/plugin/18045-window-resizer)
    * Resize IDE window. Useful during screensharing in messengers.
* [Extra Icons](https://plugins.jetbrains.com/plugin/11058-extra-icons)
    * Adds 500+ icons for files like Travis YML, GitLab YML, Angular files, etc.
* [CodeGlance Pro](https://plugins.jetbrains.com/plugin/18824-codeglance-pro)
    * Displays a zoomed out overview of source code into editor pane(similar to Sublime Text). The minimap allows for
      quick scrolling letting you jump straight to sections of code.
* [Extra ToolWindow Colorful Icons](https://plugins.jetbrains.com/plugin/16604-extra-toolwindow-colorful-icons)
    * Makes tool window icons colorful. Extremely helpful with "New UI".
* [Icon Viewer 2](https://plugins.jetbrains.com/plugin/13995-icon-viewer-2)
    * Show images as an icon in project explorer.

## Code Editor

* [Better Highlights](https://plugins.jetbrains.com/plugin/12895-better-highlights)
    * Allows to colorize comments, language keyword, methods/functions.
    * Shows cognitive complexity under methods.
    * Enables ability to reference source code and files in comments.
* [HighlightBracketPair](https://plugins.jetbrains.com/plugin/17320-highlightbracketpair)
    * Highlights current bracket pair, including HTML/XML tags.
* [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)
    * Colorize nearly placed brackets.
* [Indent Rainbow](https://plugins.jetbrains.com/plugin/13308-indent-rainbow)
    * Colorize the indentations.
* [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
    * Adds support of Modal Editing concept from Vim. Can greatly increase your productivity, if you will adopt it.
    * Modal Editing is a concept where the behavior of a text editor depends on the current mode it is in. Vim has three
      modes: Normal Mode for navigation and editing commands, Insert Mode for directly typing and editing text, and
      Visual Mode for selecting and manipulating blocks of text.
* [IdeaVim-Quickscope](https://plugins.jetbrains.com/plugin/19417-ideavim-quickscope)
    * An always-on highlight for a unique character in every word on a line to help you use f, F for navigation.
* [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)
    * Allows to quickly navigate the caret to any position visible in the editor.
* [Kursor](https://plugins.jetbrains.com/plugin/22072-kursor)
    * Changes cursor visuals based on current context (current source code language, current system language, caps lock state etc.)

## Navigation

* [Frame Switcher](https://plugins.jetbrains.com/plugin/7138-frame-switcher)
    * Switch between projects (would open project, if it was not yet opened).
* [HarpoonIJ](https://plugins.jetbrains.com/plugin/20782-harpoonij)
    * Simplifies code navigation by marking up to 5 frequently-used files with access via hotkeys.
* [Focus on Active Task](https://plugins.jetbrains.com/plugin/9824-focus-on-active-task)
    * Filters out not relevant files/paths in project tree. Useful in a thousand files projects to limit visibility of files.

## Utilities

* [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
    * Various tools to manipulate plain strings. For example, sorting, filtering, case switching etc. You can add
      shortcut for any operation, most useful one would be shortcut to switch between cases.
* [Custom Postfix Templates](https://plugins.jetbrains.com/plugin/9862-custom-postfix-templates)
    * Adds additional postfix autocompletion templates for various languages. By default, no templates are present. You
      need to spend time to find out templates useful for your language/project and manually add them as "Web Template".
* [Json Helper](https://plugins.jetbrains.com/plugin/13873-json-helper)
    * Various tools to manipulate JSON. For example, json path searching, escape/unescape, uglify/prettify etc.
* [Randomness](https://plugins.jetbrains.com/plugin/9836-randomness)
    * Generate and insert random numbers, strings, and UUIDs. Useful in unit tests.
* [Developer Tools](https://plugins.jetbrains.com/plugin/21904-developer-tools)
    * Provides UI inside IDE for commonly used tools, like JWT token decoder, RegExp checker, text diff etc.

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
* [Commit Message Template](https://plugins.jetbrains.com/plugin/23100-commit-message-template)
    * Allows to define custom commit message template, when conventional commit approach is not desired.
* [GitLink](https://plugins.jetbrains.com/plugin/8183-gitlink)
    * Allows to quickly generate links on git repo, which is very useful for sharing code with others in corporate messenger.
    * Supports GitHub, Bitbucket, GitLab, Azure and others.
* [Find Pull Request](https://plugins.jetbrains.com/plugin/8262-find-pull-request)
    * Adds Open In->Pull Request action on right click, which opens PR with code changes.
* [Azure DevOps](https://plugins.jetbrains.com/plugin/7981-azure-devops)
    * Enable working with Git and TFVC repositories on Azure DevOps Services or Team Foundation Server(TFS).
* [Azd](https://plugins.jetbrains.com/plugin/22319-azd)
    * Paid plugin for integration with Azure DevOps. Works much better than Azure DevOps plugin from Microsoft.

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
* [Debug Image Viewer (former OpenCV Image Viewer)](https://plugins.jetbrains.com/plugin/14371-debug-image-viewer-former-opencv-image-viewer-)
    * Displays an OpenCV Image (ndarray or Mat) without stopping the debugger with additional tools.
* [BinEd - Binary/Hex Editor](https://plugins.jetbrains.com/plugin/9339-bined--binary-hex-editor)
    * Allows to view and edit any file in binary/hex mode.

### Integrations with other tools

* [SonarLint](https://plugins.jetbrains.com/plugin/7973-sonarlint)
    * Plugin for SonarQube for static code analysis.
* [GitHub Actions Manager](https://plugins.jetbrains.com/plugin/19347-github-actions-manager)
    * View workflow runs and statuses directly in IDE.
* [GitLab Master](https://plugins.jetbrains.com/plugin/20347-gitlab-helper)
    * Adds full integration with GitLab - manage Merge Requests, Pipelines etc.
* [GitLab Merge Requests](https://plugins.jetbrains.com/plugin/18689-gitlab-merge-requests)
    * Review GitLab merge requests inside IDE.
* [GitLab CICD - Pipelines & Jobs, Builds Run Cancel Retry View Log](https://plugins.jetbrains.com/plugin/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log)
    * Allows to view state and detailed information of pipelines/jobs from IDE. Adds possibility to trigger pipelines/jobs, download logs and job artifacts.
* [Jira Integration](https://plugins.jetbrains.com/plugin/11169-jira-integration)
    * Adds integration with Jira - view and update statuses of Jira issues from IDE.
* [Bitbucket Pull Requests](https://plugins.jetbrains.com/plugin/13538-bitbucket-pull-requests)
    * Adds integration with BitBucket - review PR in IDE, approve/decline/merge PRs etc.
* [New Relic CodeStream](https://plugins.jetbrains.com/plugin/12206-new-relic-codestream-github-gitlab-prs-and-code-review)
    * Adds integration with task management and version control tools(bitbucket, jira, gitlab, GitHub etc.), which
      allows to do everything from IDE. Also contains collaboration tools and integrations with Slack and Teams.
      CodeStream itself and plugin are free, so it is definitely worth to try.

### Miscellaneous

* [Archive Browser](https://plugins.jetbrains.com/plugin/9491-archive-browser)
    * Allows to browse files inside archives including nested archives. Nested .jar files are also supported.
    * It was not updated for 2 years, but still works well in the newest version of IDE's.
* [Grep Console](https://plugins.jetbrains.com/plugin/7125-grep-console)
    * Also to tail, filter, highlight etc. inside IDE terminal.
* [Json Parser](https://plugins.jetbrains.com/plugin/10650-json-parser)
    * UI to validate and format JSON strings
* [Multirun](https://plugins.jetbrains.com/plugin/7248-multirun)
    * Group multiple run configurations and run them at once in a single click.
* [Run Configuration as Action](https://plugins.jetbrains.com/plugin/9448-run-configuration-as-action)
    * Register all run configuration as actions to assign shortcuts for them.
* [Naming Is Hard](https://plugins.jetbrains.com/plugin/17272-naming-is-hard)
    * Generates nice random names for new projects and modules.
* [Translation](https://plugins.jetbrains.com/plugin/8579-translation)
    * Translates selected text on desired language.

### Cloud/DevOps Tools

* [AWS Toolkit](https://plugins.jetbrains.com/plugin/11349-aws-toolkit)
    * Adds integration with AWS into IDE - resource explorer, run/debug lambda, logs, s3 explorer etc.
* [Azure Toolkit for Rider](https://plugins.jetbrains.com/plugin/11220-azure-toolkit-for-rider)
    * Jetbrains plugin for integration with Azure into IDE - resource explorer, run/debug Azure Functions etc.
* [Azure Toolkit for IntelliJ](https://plugins.jetbrains.com/plugin/8053-azure-toolkit-for-intellij)
    * Microsoft plugin for integration with Azure into IDE - resource explorer, run/debug Azure Functions etc.
* [Application Insights Debug Log Viewer](https://plugins.jetbrains.com/plugin/13984-application-insights-debug-log-viewer)
    * Show Azure Application Insights logs during application debug session.
* [Kubernetes](https://plugins.jetbrains.com/plugin/10485-kubernetes)
    * Advanced editor for kubernetes and helm configs with runtime support for k8s cluster and pods (attaching pod
      console, viewing logs etc.).
* [Jenkins Control](https://plugins.jetbrains.com/plugin/6110-jenkins-control)
    * Adds integration with Jenkins - trigger jobs, view job logs etc.
* [Terraform and HCL](https://plugins.jetbrains.com/plugin/7808-terraform-and-hcl)
    * Add IDE capabilities for HCL and HIL files (autocomplete, syntax highlight etc.).
* [BashSupport Pro](https://plugins.jetbrains.com/plugin/13841-bashsupport-pro)
    * Add IDE capabilities for shell scripting (autocomplete, syntax highlight etc.).
* [PowerShell](https://plugins.jetbrains.com/plugin/10249-powershell)
    * Add IDE capabilities for PowerShell scripting (autocomplete, syntax highlight etc.).

## Language specific

### Javascript/Typescript

* [Quokka](https://plugins.jetbrains.com/plugin/9667-quokka)
    * Javascript playground inside editor. Allows to write and test code on the fly with access to project files.
* [Wallaby](https://plugins.jetbrains.com/plugin/15742-wallaby)
    * Intelligent test runner for JavaScript that continuously runs your tests. It reports code coverage and other
      results to your code editor immediately as you change your code.
* [NPM Update Dependencies](https://plugins.jetbrains.com/plugin/21105-npm-update-dependencies)
    * Highlights outdated versions in package.json and allows to update version in a single click.
* [Run configuration for Typescript](https://plugins.jetbrains.com/plugin/10841-run-configuration-for-typescript)
    * Simplifies running of TS files.
* [LogIt](https://plugins.jetbrains.com/plugin/13432-logit)
    * Inserts "console.log" function via shortcut.

#### Javascript/Typescript Frameworks

* [GraphQL](https://plugins.jetbrains.com/plugin/8097-graphql)
    * Support for GraphQL. Schema-aware completion, syntax highlighting etc.
* [IntelliVue](https://plugins.jetbrains.com/plugin/12014-intellivue)
    * Provides analysis, actions, and utilities for Vue Single File Components. This plugin adds additional
      functionality on top of the standard Vue plugin.
* [React Buddy](https://plugins.jetbrains.com/plugin/17467-react-buddy)
    * Provides component palettes for MUI (MaterialUI), Ant Design, Chakra UI, Mantine. Helps to create and use
      Storybook stories.
* [React Native Console](https://plugins.jetbrains.com/plugin/9564-react-native-console)
    * Run React Native commands and makes RN coding easier.

### Java

* [Byte Code Analyzer](https://plugins.jetbrains.com/plugin/16970-byte-code-analyzer)
    * Provides different views for .class files and contains additional tools for byte code analysis.
* [RoboPOJOGenerator](https://plugins.jetbrains.com/plugin/8634-robopojogenerator)
    * Generate POJO classes from JSON and other formats.
* [GenerateAllSetter](https://plugins.jetbrains.com/plugin/9360-generateallsetter)
    * Generate setters on object. Useful for mappers and converters.
* [JRebel and XRebel](https://plugins.jetbrains.com/plugin/4441-jrebel-and-xrebel)
    * Integrates with JRebel hot reload and XRebel performance profiler.
* [VisualVM Launcher](https://plugins.jetbrains.com/plugin/7115-visualvm-launcher)
    * Allows to VisualVM from IDE.
* [MetricsTree](https://plugins.jetbrains.com/plugin/13959-metricstree)
    * Displays various code metrics for Java. Starting from simple Lines of Code ending with QMOOD quality attributes, Robert Martin metrics etc.

#### Java Frameworks

* [JPA Buddy](https://plugins.jetbrains.com/plugin/15075-jpa-buddy)
    * Extends support for DB related tools(Hibernate, Spring Data, Flyway, MapStruct etc.) with additional inspections,
      generation wizards, automatic generation of DB migrations etc.
* [Spring Boot Helper](https://plugins.jetbrains.com/plugin/18622-spring-boot-helper)
    * Extends support for Spring Boot - start initializr, autocomplete Spring Boot/Cloud configuration key/value, Spring
      reference configuration, Spring metadata documentation.
* [Maven Helper](https://plugins.jetbrains.com/plugin/7179-maven-helper)
    * Extends maven support with additional useful features, like analyzing and excluding dependencies.
* [Maven Dependency Checker](https://plugins.jetbrains.com/plugin/18525-maven-dependency-checker)
    * Check if there are newer versions of maven dependencies.
* [Gradle Daemons View](https://plugins.jetbrains.com/plugin/22600-gradle-daemons-view)
    * Allows to view and stop Gradle daemons from IDE.

### Kotlin

* [JSON To Kotlin Class (JsonToKotlinClass)](https://plugins.jetbrains.com/plugin/9960-json-to-kotlin-class-jsontokotlinclass-)
    * Specialized converter from JSON into Kotlin data class.
* [ktfmt](https://plugins.jetbrains.com/plugin/14912-ktfmt)
    * Kotlin source code formatter. Useful, if you are not satisfied with built-in formatter.
* [detekt](https://plugins.jetbrains.com/plugin/10761-detekt)
    * Additional static code analysis for Kotlin.

### Android

* [adb_idea](https://plugins.jetbrains.com/plugin/7380-adb-idea)
    * Add frequently used ADB commands into IDE.
* [ADB Tools](https://plugins.jetbrains.com/plugin/18153-adb-tools)
    * Adds a wide range of ADB functionality. Useful, when working with multiple devices.
* [Compose Color Preview](https://plugins.jetbrains.com/plugin/21298-compose-color-preview)
    * Draws colors in gutter for Android Color.

### Python

* [Python Security](https://plugins.jetbrains.com/plugin/13609-python-security)
    * Adds additional static code analysis inspections for Python.
* [Python Annotations](https://plugins.jetbrains.com/plugin/12035-python-annotations)
    * Provides quickfixes for common mistakes in type annotations.
* [Pylint](https://plugins.jetbrains.com/plugin/11084-pylint)
    * Adds pylint static code analysis integration into IDE.

#### Python Frameworks

* [Odoo](https://plugins.jetbrains.com/plugin/13499-odoo)
    * Provides Odoo framework support (code autocompletion, code navigation etc.)
* [Odoo Autocompletion Support](https://plugins.jetbrains.com/plugin/13083-odoo-autocompletion-support)
    * Provides enhanced autocompletion for Odoo addon/module.
* [Lets-Plot in SciView](https://plugins.jetbrains.com/plugin/14379-lets-plot-in-sciview)
    * Provides interactive scientific computing and data visualization.

### C#

* [Heap Allocations Viewer](https://plugins.jetbrains.com/plugin/9223-heap-allocations-viewer)
    * Highlights local object allocations, boxing, delegates and closure creations points.
* [Rossynt](https://plugins.jetbrains.com/plugin/16902-rossynt)
    * Roslyn's syntax tree viewer for C#.
    * Right now doesn't support .NET 8 and plugin looks abandoned.

#### C# Frameworks

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
    * It was not updated for 2 years, but still works well in the newest version of IDE's.

#### PHP Frameworks

* [Laravel Idea](https://plugins.jetbrains.com/plugin/13441-laravel-idea)
    * Add support for Laravel framework.
* [Collector](https://plugins.jetbrains.com/plugin/15246-collector)
    * Adds multiple refactorings for Laravel Collections.
* [Symfony Support](https://plugins.jetbrains.com/plugin/7219-symfony-support)
    * Add support for Symfony framework.
* [Yii2 Framework Support](https://plugins.jetbrains.com/plugin/23693-yii2-framework-support/versions)
    * Add support for Yii2 framework.
* [Magento PhpStorm](https://plugins.jetbrains.com/plugin/8024-magento-phpstorm)
    * Free plugin, which extends support for Magento 2. Has compatibility issues in latest versions of IDE.
* [Magento and Adobe Commerce PhpStorm by Atwix](https://plugins.jetbrains.com/plugin/20554-magento-and-adobe-commerce-phpstorm-by-atwix)
    * Freemium plugin, which extends support for Magento 2 with Inspections and improved Navigation.
* [PHPUnit Enhancement](https://plugins.jetbrains.com/plugin/9674-phpunit-enhancement)
    * Autocompletion and code navigation for PHPUnit.

### C/C++

* [EzArgs](https://plugins.jetbrains.com/plugin/16411-ezargs)
    * Provides option to pass arguments to C++ run configurations by simply writing them in dropdown box on the toolbar.
* [Compiler Explorer](https://plugins.jetbrains.com/plugin/11064-compiler-explorer)
    * Shows compilation results from a remote Compiler Explorer instance.
    * Right now is not working with CLion Nova, as Jetbrains didn't provide any migration guides.
* [Bazel for CLion](https://plugins.jetbrains.com/plugin/9554-bazel-for-clion)
    * Google plugin to add support for Bazel build.
* [CMake Plus](https://plugins.jetbrains.com/plugin/12869-cmake-plus)
    * Extend CMake language support (highlighting, code navigation, inspections etc.).
* [Serial Port Monitor](https://plugins.jetbrains.com/plugin/8031-serial-port-monitor)
    * Allows to communicate with serial devices like Arduino from IDE.

### Rust

* [RON Extended Support](https://plugins.jetbrains.com/plugin/15878-ron-extended-support)
    * Adds support for Rusty Object Notation files (code completion, syntax highlighting etc.).
* [RustJson](https://plugins.jetbrains.com/plugin/22393-rustjson)
    * Converts JSON into Rust Struct.

### Go

* [Go Linter](https://plugins.jetbrains.com/plugin/12496-go-linter)
    * Provides golangci-lint inspection and autofix on-the-fly

## AI/LLM Integrations

* [AI Assistant](https://plugins.jetbrains.com/plugin/22282-ai-assistant)
    * Jetbrains native AI integration.
* [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot)
    * Enables GitHub Copilot integration with IDE.
    * Right now it is considered as most useful AI in Jetbrains IDEs.
* [Tabnine: AI Code Completion & Chat in Java JS/TS Python & More](https://plugins.jetbrains.com/plugin/12798-tabnine-ai-code-completion-js-java-python-ts-rust-go-php--more)
    * Enables Tabnine integration with IDE.
* [Amazon Q](https://plugins.jetbrains.com/plugin/24267-amazon-q/)
    * Enables Amazon CodeWhisperer integration with IDE.
* [Codiumate - Code, test and review with confidence - by CodiumAI](https://plugins.jetbrains.com/plugin/21206-codiumai--integrity-agent-powered-by-gpt-3-5-4)
    * Enables CodiumAI integration with IDE.
* [CodeGPT](https://plugins.jetbrains.com/plugin/21056-codegpt)
    * Integrates AI chat in IDE. Support all major providers (OpenAI, Anthropic, Azure, Mistral etc.)
* [AI Commits](https://plugins.jetbrains.com/plugin/21335-ai-commits)
    * Generate commit messages using LLM. Supports OpenAI, Anthropic, Gemini and few others.
* [Grazie Pro](https://plugins.jetbrains.com/plugin/16136-grazie-pro)
    * Jetbrains paid plugin for grammar and spell check. Also has translation functionality for 8 languages.

## Themes

* [Material Theme UI](https://plugins.jetbrains.com/plugin/8006-material-theme-ui)
* [One Dark](https://plugins.jetbrains.com/plugin/11938-one-dark-theme)
* [Catppuccin Theme](https://plugins.jetbrains.com/plugin/18682-catppuccin-theme)
* [Gerry Themes Pro](https://plugins.jetbrains.com/plugin/19668-gerry-themes-pro)
* [Doki Theme](https://plugins.jetbrains.com/plugin/10804-doki-theme)
* [Codely Theme](https://plugins.jetbrains.com/plugin/12891-codely-theme)
* [Deep Ocean Theme](https://plugins.jetbrains.com/plugin/16729-deep-ocean-theme)
* [Zenburn](https://plugins.jetbrains.com/plugin/17938-zenburn)
* [Sakura Theme](https://plugins.jetbrains.com/plugin/22872-sakura-theme)
* [Sequoia Theme](https://plugins.jetbrains.com/plugin/22826-sequoia-theme)

## Fun

* [Nyan Progress Bar](https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar)
* [Cats Progress Bar](https://plugins.jetbrains.com/plugin/22740-cats-progress-bar)
* [Gopher](https://plugins.jetbrains.com/plugin/12875-gopher)
    * It was not updated for 3 years, but still works well in the newest version of IDE's.
* [Power Mode II](https://plugins.jetbrains.com/plugin/8251-power-mode-ii)
* [Anime Memes](https://plugins.jetbrains.com/plugin/15865-anime-memes)
* [Space Invaders](https://plugins.jetbrains.com/plugin/19383-space-invaders)