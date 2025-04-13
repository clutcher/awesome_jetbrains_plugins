# Awesome Jetbrains Plugins

A curated list of Jetbrains plugins. Most of the plugins are compatible with all Jetbrains IDEs (IntelliJ IDEA, PyCharm,
WebStorm, PhpStorm, Rider, CLion, RubyMine, GoLand, Aqua, Android Studio). IDE-specific plugins are placed in "Language
specific" section. Also keep in mind that all of Jetbrains IDEs have great out-of-the-box support for programming
languages itself and major frameworks, which are enabled by default, so there is no sense to include them in this
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
    * Resize an IDE window. Useful during screensharing in messengers.
* [Extra Icons](https://plugins.jetbrains.com/plugin/11058-extra-icons)
    * Adds 500+ icons for files like Travis YML, GitLab YML, Angular files, etc.
* [CodeGlance Pro](https://plugins.jetbrains.com/plugin/18824-codeglance-pro)
    * Displays a zoomed out overview of source code into editor pane (similar to Sublime Text).
      The minimap allows for quick scrolling letting you jump straight to sections of code.
* [Extra ToolWindow Colorful Icons](https://plugins.jetbrains.com/plugin/16604-extra-toolwindow-colorful-icons)
    * Makes tool window icons colorful. Extremely helpful with "New UI".
* [Icon Viewer 2](https://plugins.jetbrains.com/plugin/13995-icon-viewer-2)
    * Show images as an icon in project explorer.

## Code Editor

* [Better Highlights](https://plugins.jetbrains.com/plugin/12895-better-highlights)
    * Allows colorizing comments, language keyword, methods/functions.
    * Shows cognitive complexity under methods.
    * Enables the ability to reference source code and files in comments.
* [HighlightBracketPair](https://plugins.jetbrains.com/plugin/17320-highlightbracketpair)
    * Highlights current bracket pair, including HTML/XML tags.
* [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)
    * Colorize nearly placed brackets.
* [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
    * Adding support of Modal Editing concept from Vim. Can greatly increase your productivity if you adopt it.
    * Modal Editing is a concept where the behavior of a text editor depends on the current mode it is in. Vim has three
      modes: Normal Mode for navigation and editing commands, Insert Mode for directly typing and editing text, and
      Visual Mode for selecting and manipulating blocks of text.
* [IdeaVim-Quickscope](https://plugins.jetbrains.com/plugin/19417-ideavim-quickscope)
    * An always-on highlight for a unique character in every word on a line to help you use f, F for navigation.
* [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)
    * Allows quickly navigating the caret to any position visible in the editor.
* [Kursor](https://plugins.jetbrains.com/plugin/22072-kursor)
    * Changes cursor visuals based on current context (current source code language, current system language, caps lock state etc.)

## Navigation

* [Frame Switcher](https://plugins.jetbrains.com/plugin/7138-frame-switcher)
    * Switch between projects (would open a project if it was not yet opened).
* [HarpoonIJ](https://plugins.jetbrains.com/plugin/20782-harpoonij)
    * Simplifies code navigation by marking up to five frequently used files with access via hotkeys.
* [Focus on Active Task](https://plugins.jetbrains.com/plugin/9824-focus-on-active-task)
    * Filters out not relevant files/paths in a project tree. Useful in a thousand files projects to limit visibility of files.

## Utilities

* [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
    * Various tools to manipulate plain strings.
      For example, sorting, filtering etc. You can add shortcut for any operation, the most useful one would be shortcut to switch between cases.
    * Allows case switching(camelCase, snake_case etc.) of any selected string with shortcut or via submenu on mouse right click.
* [Custom Postfix Templates](https://plugins.jetbrains.com/plugin/9862-custom-postfix-templates)
    * Adds additional postfix autocompletion templates for various languages. By default, no templates are present. You
      need to spend time to find out templates useful for your language/project and manually add them as "Web Template".
* [Json Helper](https://plugins.jetbrains.com/plugin/13873-json-helper)
    * Various tools to manipulate JSON. For example, JSON path searching, escape/unescape, uglify/prettify etc.
* [Randomness](https://plugins.jetbrains.com/plugin/9836-randomness)
    * Generate and insert random numbers, strings, and UUIDs. Useful in unit tests.
* [Developer Tools](https://plugins.jetbrains.com/plugin/21904-developer-tools)
    * Provides UI inside IDE for commonly used tools, like JWT token decoder, RegExp checker, text diff, etc.

## Version Control

* [.ignore](https://plugins.jetbrains.com/plugin/7495--ignore)
    * Improve work with .gitignore file by adding syntax highlight, generate rules for .gitignore, entries inspection
      etc.
* [GitToolBox](https://plugins.jetbrains.com/plugin/7499-gittoolbox)
    * Improve work with git by enabling autocompletion, displaying various additional info, like number of ahead commits
      etc., branches clean up, auto-fetch, and various other functions.
* [GitLive](https://plugins.jetbrains.com/plugin/11955-gitlive)
    * The main feature is real time merge conflict detection.
* [Conventional Commit](https://plugins.jetbrains.com/plugin/13389-conventional-commit)
    * Provides autocompletion for [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), also named
      semantic commits, inside the VCS Commit dialog.
* [Commit Message Template](https://plugins.jetbrains.com/plugin/23100-commit-message-template)
    * Allows defining custom commit message template when conventional commit approach is not desired.
* [GitLink](https://plugins.jetbrains.com/plugin/8183-gitlink)
    * Allows you to quickly generate links on git repo, which is handy for sharing code with others in corporate messenger.
    * Supports GitHub, Bitbucket, GitLab, Azure and others.
* [Find Pull Request](https://plugins.jetbrains.com/plugin/8262-find-pull-request)
    * Adds Open In->Pull Request action on right click, which opens PR with code changes.
    * Adds "List Pull Request" under "Annotate with Git Blame", which works similarly with showing PRs instead of commiters in gutter.
* [Azd](https://plugins.jetbrains.com/plugin/22319-azd)
    * Paid plugin for integration with Azure DevOps. Works much better than Azure DevOps plugin from Microsoft.

## Tools

### Additional file types support

* [PlantUML Integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)
    * PlantUML diagramming tool integration, which allows creating diagrams from a plain text language.
* [PDF Viewer](https://plugins.jetbrains.com/plugin/14494-pdf-viewer)
    * Allows viewing PDF files in the IDE.
* [CSV Editor](https://plugins.jetbrains.com/plugin/10037-csv-editor)
    * Allows editing CSV files in a colored table- & text-editor.
      It provides syntax-validation, highlighting, customization, and plenty more besides.
* [Easy I18n](https://plugins.jetbrains.com/plugin/16316-easy-i18n)
    * Allows editing translation files (JSON, YAML, properties) in a tree or table view.
* [.env files support](https://plugins.jetbrains.com/plugin/9525--env-files-support)
    * Allows editing environment variables files with autocompletion and syntax highlighting.
* [Ideolog](https://plugins.jetbrains.com/plugin/9746-ideolog)
    * Interactive viewer for '.log' files with additional syntax highlighting.
* [Debug Image Viewer (former OpenCV Image Viewer)](https://plugins.jetbrains.com/plugin/14371-debug-image-viewer-former-opencv-image-viewer-)
    * Displays an OpenCV Image (ndarray or Mat) without stopping the debugger with additional tools.
* [BinEd - Binary/Hex Editor](https://plugins.jetbrains.com/plugin/9339-bined--binary-hex-editor)
    * Allows viewing and edit any file in binary/hex mode.

### Integrations with other tools

* [SonarQube for IDE](https://plugins.jetbrains.com/plugin/7973-sonarqube-for-ide)
    * Plugin for SonarQube for static code analysis.
* [GitHub Actions Manager](https://plugins.jetbrains.com/plugin/19347-github-actions-manager)
    * View workflow runs and statuses directly in the IDE.
* [GitLab Integration Pro](https://plugins.jetbrains.com/plugin/18689-gitlab-integration-pro)
    * Review GitLab merge requests inside the IDE.
* [GitLab CICD - Pipelines & Jobs, Builds Run Cancel Retry View Log](https://plugins.jetbrains.com/plugin/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log)
    * Allows viewing state and detailed information of pipelines/jobs from the IDE. Adds possibility to trigger pipelines/jobs, download logs and job artifacts.
* [Jira Integration](https://plugins.jetbrains.com/plugin/11169-jira-integration)
    * Adds integration with Jira - view and update statuses of Jira issues from the IDE.
* [Bitbucket Integration Pro](https://plugins.jetbrains.com/plugin/13538-bitbucket-integration-pro)
    * Adds integration with BitBucket - review PR in IDE, approve/decline/merge PRs, etc.

### Miscellaneous

* [Archive Browser](https://plugins.jetbrains.com/plugin/9491-archive-browser)
    * Allows browsing files inside archives including nested archives. Nested .jar files are also supported.
    * It was not updated for 3 years, but still works well in the newest version of the IDE.
* [Grep Console](https://plugins.jetbrains.com/plugin/7125-grep-console)
    * Also to tail, filter, highlight, etc. inside the IDE terminal.
* [Native Terminal](https://plugins.jetbrains.com/plugin/9966-native-terminal)
    * Add a Terminal icon for fast open of project directories in your favorite terminal.
* [Json Parser And Code Generation](https://plugins.jetbrains.com/plugin/10650-json-parser-and-code-generation)
    * UI to validate and format JSON strings
* [Multirun](https://plugins.jetbrains.com/plugin/7248-multirun)
    * Group multiple run configurations and run them at once in a single click.
* [Run Configuration as Action](https://plugins.jetbrains.com/plugin/9448-run-configuration-as-action)
    * Register all run configurations as actions to assign shortcuts for them.
* [Naming Is Hard](https://plugins.jetbrains.com/plugin/17272-naming-is-hard)
    * Generates nice random names for new projects and modules.
* [Translation](https://plugins.jetbrains.com/plugin/8579-translation)
    * Translates selected text on desired language.

### Cloud/DevOps Tools

* [AWS Toolkit](https://plugins.jetbrains.com/plugin/11349-aws-toolkit)
    * Adds integration with AWS into IDE - resource explorer, run/debug lambda, logs, s3 explorer, etc.
* [Azure Toolkit for Rider](https://plugins.jetbrains.com/plugin/11220-azure-toolkit-for-rider)
    * Jetbrains plugin for integration with Azure into IDE - resource explorer, run/debug Azure Functions, etc.
* [Azure Toolkit for IntelliJ](https://plugins.jetbrains.com/plugin/8053-azure-toolkit-for-intellij)
    * Microsoft plugin for integration with Azure into IDE - resource explorer, run/debug Azure Functions, etc.
* [Application Insights Debug Log Viewer](https://plugins.jetbrains.com/plugin/13984-application-insights-debug-log-viewer)
    * Show Azure Application Insights logs during application debug session.
* [Google Cloud Code](https://plugins.jetbrains.com/plugin/8079-google-cloud-code)
    * Integration with Google Cloud Platform (GCP) services.
* [Kubernetes](https://plugins.jetbrains.com/plugin/10485-kubernetes)
    * Advanced editor for kubernetes and helm configs with runtime support for k8s cluster and pods (attaching pod
      console, viewing logs, etc.).
* [Jenkins Control](https://plugins.jetbrains.com/plugin/6110-jenkins-control)
    * Adds integration with Jenkins - trigger jobs, view job logs etc.
* [Terraform and HCL](https://plugins.jetbrains.com/plugin/7808-terraform-and-hcl)
    * Add IDE capabilities for HCL and HIL files (autocomplete, syntax highlight, etc.).
* [BashSupport Pro](https://plugins.jetbrains.com/plugin/13841-bashsupport-pro)
    * Add IDE capabilities for shell scripting (autocomplete, syntax highlight, etc.).
* [PowerShell](https://plugins.jetbrains.com/plugin/10249-powershell)
    * Add IDE capabilities for PowerShell scripting (autocomplete, syntax highlight, etc.).

## Language specific

### Javascript/Typescript

* [Quokka](https://plugins.jetbrains.com/plugin/9667-quokka)
    * JavaScript playground inside editor. Allows you to write and test code on the fly with access to project files.
* [Wallaby](https://plugins.jetbrains.com/plugin/15742-wallaby)
    * Intelligent test runner for JavaScript that continuously runs your tests. It reports code coverage and other
      results to your code editor immediately as you change your code.
* [NPM Update Dependencies](https://plugins.jetbrains.com/plugin/21105-npm-update-dependencies)
    * Highlights outdated versions in package.json and allows to update a version in a single click.
* [Run configuration for TypeScript](https://plugins.jetbrains.com/plugin/10841-run-configuration-for-typescript)
    * Simplifies running of TS files.
* [LogIt](https://plugins.jetbrains.com/plugin/13432-logit)
    * Inserts "console.log" function via shortcut.

#### Javascript/Typescript Frameworks

* [GraphQL](https://plugins.jetbrains.com/plugin/8097-graphql)
    * Support for GraphQL. Schema-aware completion, syntax highlighting, etc.
* [Angular Component Folding](https://plugins.jetbrains.com/plugin/10090-angular-component-folding)
    * Groups files which have the same name and different extensions.
* [IntelliVue](https://plugins.jetbrains.com/plugin/12014-intellivue)
    * Provides analysis, actions, and utilities for Vue Single File Components. This plugin adds additional
      functionality on top of the standard Vue plugin.
* [React Buddy](https://plugins.jetbrains.com/plugin/17467-react-buddy)
    * Provides component palettes for MUI (MaterialUI), Ant Design, Chakra UI, Mantine. Helps to create and use
      Storybook stories.
* [React Native Console](https://plugins.jetbrains.com/plugin/9564-react-native-console)
    * Run React Native commands and makes RN coding easier.

### Java

* [CheckStyle-IDEA](https://plugins.jetbrains.com/plugin/1065-checkstyle-idea)
    * Adds realtime and on demand scanning of Java files with checkstyle.
* [Byte Code Analyzer](https://plugins.jetbrains.com/plugin/16970-byte-code-analyzer)
    * Provides different views for .class files and contains additional tools for byte code analysis.
* [RoboPOJOGenerator](https://plugins.jetbrains.com/plugin/8634-robopojogenerator)
    * Generate POJO classes from JSON and other formats.
* [JRebel and XRebel](https://plugins.jetbrains.com/plugin/4441-jrebel-and-xrebel)
    * Integrates with JRebel hot reload and XRebel performance profiler.
* [Lightrun](https://plugins.jetbrains.com/plugin/16477-lightrun)
    * Adds functionality to dynamically inject logs, snapshots, and metrics into running applications without redeployments, enabling real-time debugging and monitoring directly from the IDE.
* [VisualVM Launcher](https://plugins.jetbrains.com/plugin/7115-visualvm-launcher)
    * Allows you to start VisualVM from the IDE.
* [MetricsTree](https://plugins.jetbrains.com/plugin/13959-metricstree)
    * Displays various code metrics for Java. Starting from simple Lines of Code ending with QMOOD quality attributes, Robert Martin metrics, etc.

#### Java Frameworks

* [JPA Buddy](https://plugins.jetbrains.com/plugin/15075-jpa-buddy)
    * Extends support for DB related tools (Hibernate, Spring Data, Flyway, MapStruct, etc.) with additional inspections,
      generation wizards, automatic generation of DB migrations, etc.
* [Spring Boot Helper](https://plugins.jetbrains.com/plugin/18622-spring-boot-helper)
    * Extends support for Spring Boot - start initializr, autocomplete Spring Boot/Cloud configuration key/value, Spring
      reference configuration, Spring metadata documentation.
* [Maven Helper](https://plugins.jetbrains.com/plugin/7179-maven-helper)
    * Extends maven support with additional useful features, like analyzing and excluding dependencies.
* [Maven Dependency Checker](https://plugins.jetbrains.com/plugin/18525-maven-dependency-checker)
    * Check if there are newer versions of maven dependencies.
* [Gradle Utilities](https://plugins.jetbrains.com/plugin/16800-gradle-utilities)
    * Lists all running Gradle daemons, checks the latest Gradle version, clear gradle caches, and other tools.
* [Apidog Fast Request - Auto detect endpoints, HTTP REST Client](https://plugins.jetbrains.com/plugin/25925-apidog-fast-request--auto-detect-endpoints-http-rest-client)
    * Allows executing requests to Spring controllers based on their implementation from nice UI inside the IDE.

### Kotlin

* [JSON To Kotlin Class (JsonToKotlinClass)](https://plugins.jetbrains.com/plugin/9960-json-to-kotlin-class-jsontokotlinclass-)
    * Specialized converter from JSON into Kotlin data class.
* [ktfmt](https://plugins.jetbrains.com/plugin/14912-ktfmt)
    * Kotlin source code formatter. Useful if you are not satisfied with built-in formatter.
* [detekt](https://plugins.jetbrains.com/plugin/10761-detekt)
    * Additional static code analysis for Kotlin.

### Android

* [adb_idea](https://plugins.jetbrains.com/plugin/7380-adb-idea)
    * Add frequently used ADB commands into the IDE.
* [ADB Tools](https://plugins.jetbrains.com/plugin/18153-adb-tools)
    * Adds a wide range of ADB functionality. Useful when working with multiple devices.
* [Compose Color Preview](https://plugins.jetbrains.com/plugin/21298-compose-color-preview)
    * Draws colors in gutter for Android Color.

### Python

* [Pylint](https://plugins.jetbrains.com/plugin/11084-pylint)
    * Adds pylint static code analysis integration into the IDE.

#### Python Frameworks

* [Django command runner](https://plugins.jetbrains.com/plugin/13834-django-command-runner)
    * Run django management command from a definition file.
* [Pydantic](https://plugins.jetbrains.com/plugin/12861-pydantic)
    * Add autocompletion and refactoring for Pydantic models.
* [Odoo](https://plugins.jetbrains.com/plugin/13499-odoo)
    * Provides Odoo framework support (code autocompletion, code navigation etc.)
* [Odoo Autocompletion Support](https://plugins.jetbrains.com/plugin/13083-odoo-autocompletion-support)
    * Provides enhanced autocompletion for Odoo addon/module.
    * It was not updated for 2 years, but still works well in the newest version of the IDE.
* [Lets-Plot in SciView](https://plugins.jetbrains.com/plugin/14379-lets-plot-in-sciview)
    * Provides interactive scientific computing and data visualization.

### C#

* [Heap Allocations Viewer](https://plugins.jetbrains.com/plugin/9223-heap-allocations-viewer)
    * Highlights local object allocations, boxing, delegates and closure creation points.

#### C# Frameworks

* [Structured Logging](https://plugins.jetbrains.com/plugin/12832-structured-logging)
    * Analyzers for structured logging. Supports Serilog, NLog, and Microsoft.Extensions.Logging.
* [MoqComplete](https://plugins.jetbrains.com/plugin/12659-moqcomplete)
    * Code completion for Moq.

### PHP

* [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-)
    * Adds additional static code analysis inspections for PHP.
* [PHP Annotations](https://plugins.jetbrains.com/plugin/7320-php-annotations)
    * Extends PhpStorm to support annotations in DocBlocks and provide additional Attributes features.
* [deep-assoc-completion](https://plugins.jetbrains.com/plugin/9927-deep-assoc-completion)
    * The plugin allows you to have auto-completion for PHP array keys inferred from other functions.
    * It was not updated for 2 years, but still works well in the newest version of the IDE.

#### PHP Frameworks

* [Laravel Idea](https://plugins.jetbrains.com/plugin/13441-laravel-idea)
    * Add support for a Laravel framework.
* [Whisperer For Laravel](https://plugins.jetbrains.com/plugin/26042-whisperer-for-laravel)
    * Adds enhanced autocompletion and code generation for models, migrations, controllers etc.
* [Collector](https://plugins.jetbrains.com/plugin/15246-collector)
    * Adds multiple refactorings for Laravel Collections.
* [Symfony Support](https://plugins.jetbrains.com/plugin/7219-symfony-support)
    * Add support for a Symfony framework.
* [Yii2 Framework Support](https://plugins.jetbrains.com/plugin/23693-yii2-framework-support)
    * Add support for a Yii2 framework.
* [Magento PhpStorm](https://plugins.jetbrains.com/plugin/8024-magento-phpstorm)
    * Free plugin, which extends support for Magento 2. Has compatibility issues in the latest versions of the IDE.
* [Magento and Adobe Commerce PhpStorm by Atwix](https://plugins.jetbrains.com/plugin/20554-magento-and-adobe-commerce-phpstorm-by-atwix)
    * Freemium plugin, which extends support for Magento 2 with Inspections and improved Navigation.

### C/C++

* [EzArgs](https://plugins.jetbrains.com/plugin/16411-ezargs)
    * Provides an option to pass arguments to C++ run configurations by simply writing them in the dropdown box on the toolbar.
* [Compiler Explorer](https://plugins.jetbrains.com/plugin/11064-compiler-explorer)
    * Shows compilation results from a remote Compiler Explorer instance.
    * Right now is not working with CLion Nova, as Jetbrains didn't provide any migration guides.
* [Bazel for CLion](https://plugins.jetbrains.com/plugin/9554-bazel-for-clion)
    * Google plugin to add support for Bazel build.
* [CMake Plus](https://plugins.jetbrains.com/plugin/12869-cmake-plus)
    * Extend CMake language support (highlighting, code navigation, inspections, etc.).
* [Serial Port Monitor](https://plugins.jetbrains.com/plugin/8031-serial-port-monitor)
    * Allows communicating with serial devices like Arduino from IDE.

### Rust

* [RON Extended Support](https://plugins.jetbrains.com/plugin/15878-ron-extended-support)
    * Adds support for Rusty Object Notation files (code completion, syntax highlighting, etc.).
* [RustJson](https://plugins.jetbrains.com/plugin/22393-rustjson)
    * Converts JSON into Rust Struct.

### Go

* [Go Linter](https://plugins.jetbrains.com/plugin/12496-go-linter)
    * Provides golangci-lint inspection and autofix on-the-fly

## AI/LLM Integrations

* [JetBrains AI Assistant](https://plugins.jetbrains.com/plugin/22282-ai-assistant)
    * Jetbrains native AI integration.
* [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot)
    * Enables GitHub Copilot integration with IDE.
* [Tabnine: AI Chat & Autocomplete for JavaScript, Python & more](https://plugins.jetbrains.com/plugin/12798-tabnine-ai-chat--autocomplete-for-javascript-python--more)
    * Enables Tabnine integration with IDE.
* [Amazon Q](https://plugins.jetbrains.com/plugin/24267-amazon-q/)
    * Enables Amazon CodeWhisperer integration with IDE.
* [Qodo Gen](https://plugins.jetbrains.com/plugin/21206-qodo-gen)
    * Enables Qodo (former CodiumAI) integration with IDE.
* [Proxy AI](https://plugins.jetbrains.com/plugin/21056-proxy-ai)
    * Integrates AI chat in the IDE. Support all major providers (OpenAI, Anthropic, Azure, Mistral, etc.)
* [AI Commits](https://plugins.jetbrains.com/plugin/21335-ai-commits)
    * Generate commit messages using LLM. Supports OpenAI, Anthropic, Gemini and a few others.
* [Grazie Pro](https://plugins.jetbrains.com/plugin/16136-grazie-pro)
    * Jetbrains paid plugin for grammar and spell check. It also has translation functionality for eight languages.

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
* [YourProgressBar](https://plugins.jetbrains.com/plugin/21417-yourprogressbar)
    * Replace progress bar with custom image.
* [Gopher](https://plugins.jetbrains.com/plugin/12875-gopher)
    * It was not updated for 3 years, but still works well in the newest version of the IDE.
* [Power Mode II](https://plugins.jetbrains.com/plugin/8251-power-mode-ii)
* [Anime Memes](https://plugins.jetbrains.com/plugin/15865-anime-memes)
* [Space Invaders](https://plugins.jetbrains.com/plugin/19383-space-invaders)
* [Pets](https://plugins.jetbrains.com/plugin/21008-pets)