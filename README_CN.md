# Awesome Jetbrains Plugins

Jetbrains 插件的精选列表。大多数插件与所有 Jetbrains IDE（IntelliJ IDEA、PyCharm、语言本身和主要框架）兼容，这些插件默认启用，因此将它们纳入此列表是没有意义的。

* [Awesome Jetbrains Plugins](#awesome-jetbrains-plugins)
    * [用户界面](#用户界面)
    * [代码编辑器](#代码编辑器)
    * [公用事业](#公用事业)
    * [版本控制](#版本控制)
    * [工具](#工具)
        * [其他文件类型支持](#其他文件类型支持)
        * [与其他工具集成](#与其他工具集成)
        * [杂项](#杂项)
        * [云/DevOps 工具](#云devops-工具)
    * [特定语言](#特定语言)
        * [Javascript/Typescript](#javascripttypescript)
            * [Javascript/Typescript 构架](#javascripttypescript-构架)
        * [Java](#java)
            * [Java 构架](#java-构架)
        * [Python](#python)
            * [Python 构架](#python-构架)
        * [C#](#c)
            * [C# 构架](#c-构架)
        * [PHP](#php)
            * [PHP 构架](#php-构架)
        * [C/C++](#cc)
        * [Rust](#rust)
        * [Go](#go)
    * [人工智能代码补全](#人工智能代码补全)
    * [主题](#主题)
    * [玩笑](#玩笑)

## 用户界面

* [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x)
    * 帮助您在工作时学习基本的快捷方式。当您在 IDE 内的按钮上使用鼠标时，按键启动器 X 会显示您应该使用的键盘快捷键。
* [Presentation Assistance](https://plugins.jetbrains.com/plugin/7345-presentation-assistant)
  * 通过显示您调用的任何操作的名称和键盘快捷键，帮助其他人了解您正在使用哪些快捷键。 在屏幕共享和结对编程期间很有用。
* [Extra Icons](https://plugins.jetbrains.com/plugin/11058-extra-icons)
    * 为 Travis YML、GitLab YML、Angular 文件等文件添加 500 多个图标。
* [CodeGlance Pro](https://plugins.jetbrains.com/plugin/18824-codeglance-pro)
    * 在编辑器窗格中显示缩小的源代码概述（类似于 Sublime Text）。小地图允许快速滚动，让您直接跳到鳕鱼的部分e.
* [Extra ToolWindow Colorful Icons](https://plugins.jetbrains.com/plugin/16604-extra-toolwindow-colorful-icons)
    * 使工具窗口图标变得丰富多彩。对“新用户界面”非常有帮助。

## 代码编辑器

* [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
    * 添加了对 Vim 模态编辑概念的支持。如果您愿意采用它，可以大大提高您的生产力。
    * 模态编辑是一个概念，其中文本编辑器的行为取决于其当前所处的模式。Vim
      具有三种模式：用于导航和编辑命令的普通模式、用于直接键入和编辑文本的插入模式以及用于选择和操作的可视模式文本块。
* [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)
    * 允许将插入符号快速导航到编辑器中可见的任何位置。
* [Better Highlights](https://plugins.jetbrains.com/plugin/12895-better-highlights)
    * 显示方法下的认知复杂性。
    * 允许对评论和语言关键字进行着色。
    * 能够在注释中引用源代码和文件。
* [HighlightBracketPair](https://plugins.jetbrains.com/plugin/17320-highlightbracketpair)
    * 突出显示当前括号对。
* [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)
    * 为几乎放置的括号着色。
* [Indent Rainbow](https://plugins.jetbrains.com/plugin/13308-indent-rainbow)
    * 给凹痕上色。

## 公用事业

* [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
  * 操作普通字符串的各种工具。 例如，排序、过滤、大小写切换等。您可以为任何操作添加快捷方式，最有用的是在大小写之间切换的快捷方式。
* [Custom Postfix Templates](https://plugins.jetbrains.com/plugin/9862-custom-postfix-templates)
    * 为各种语言添加额外的后缀自动完成模板。默认情况下，不存在任何模板。您需要花时间找出对您的语言/项目有用的模板，并手动将它们添加为“Web
      模板”。
* [Json Helper](https://plugins.jetbrains.com/plugin/13873-json-helper)
    * 操作 JSON 的各种工具。例如，json路径搜索、escape/unescape、uglify/prettify等。
* [Randomness](https://plugins.jetbrains.com/plugin/9836-randomness)
    * 生成并插入随机数、字符串和 UUID。在单元测试中很有用。
* [Shifter](https://plugins.jetbrains.com/plugin/6149-shifter)
    * 操作代码字符串的各种工具。例如，在数组中移动关键字/引号/字符串文字、递增/递减 int 字符串等。

## 版本控制

* [.ignore](https://plugins.jetbrains.com/plugin/7495--ignore)
    * 通过添加语法突出显示、生成 .gitignore 规则、条目检查等来改进 .gitignore 文件的工作。
* [GitToolBox](https://plugins.jetbrains.com/plugin/7499-gittoolbox)
    * 通过启用自动完成、显示各种附加信息（例如提前提交的数量等）、分支清理、自动获取和各种其他功能来改进 git 的工作。
* [GitLive](https://plugins.jetbrains.com/plugin/11955-gitlive)
    * 主要功能是实时合并冲突检测。
* [Conventional Commit](https://plugins.jetbrains.com/plugin/13389-conventional-commit)
    * 在 VCS 提交对话框中为[常规提交](https://www.conventionalcommits.org/en/v1.0.0/)（也称为语义提交）提供自动完成功能。
* [Azure DevOps](https://plugins.jetbrains.com/plugin/7981-azure-devops)
    * 允许在 Azure DevOps Services 或 Team Foundation Server(TFS) 上使用 Git 和 TFVC 存储库。

## 工具

### 其他文件类型支持

* [PlantUML Integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)
    * PlantUML 图表工具集成，允许从纯文本语言创建图表。
* [PDF Viewer](https://plugins.jetbrains.com/plugin/14494-pdf-viewer)
    * 允许在 IDE 中查看 PDF 文件。
* [CSV Editor](https://plugins.jetbrains.com/plugin/10037-csv-editor)
    * 允许在彩色表格和文本编辑器中编辑 CSV 文件。它提供语法验证、突出显示、自定义等等。
* [Easy I18n](https://plugins.jetbrains.com/plugin/16316-easy-i18n)
    * 允许在树视图或表视图中编辑翻译文件（json、yaml、属性）。
* [.env files support](https://plugins.jetbrains.com/plugin/9525--env-files-support)
    * 允许通过自动完成和语法突出显示来编辑环境变量文件。
* [Ideolog](https://plugins.jetbrains.com/plugin/9746-ideolog)
    * “.log”文件的交互式查看器，具有额外的语法突出显示功能。
* [OpenCV Image Viewer](https://plugins.jetbrains.com/plugin/14371-opencv-image-viewer)
    * 显示 OpenCV 图像（ndarray 或 Mat），而无需使用其他工具停止调试器。

### 与其他工具集成

* [SonarLint](https://plugins.jetbrains.com/plugin/7973-sonarlint)
    * 用于静态代码分析的 SonarQube 插件。
* [Gitlab Helper](https://plugins.jetbrains.com/plugin/20347-gitlab-helper)
    * 添加与 GitLab 的集成 - 管理合并请求、管道等。
* [New Relic CodeStream: GitHub, GitLab, PRs and Code Review](https://plugins.jetbrains.com/plugin/12206-new-relic-codestream-github-gitlab-prs-and-code-review)
    * 添加与任务管理和版本控制工具（bitbucket、jira、gitlab、github 等）的集成，允许从 IDE 执行所有操作。还包含协作工具以及与
      Slack 和 Teams 的集成。 CodeStream 本身和插件都是免费的，因此绝对值得尝试。

### 杂项

* [Archive Browser](https://plugins.jetbrains.com/plugin/9491-archive-browser)
    * 允许浏览存档内的文件，包括嵌套存档。还支持嵌套 .jar 文件。
* [Grep Console](https://plugins.jetbrains.com/plugin/7125-grep-console)
    * 还可以在 IDE 终端内进行拖尾、过滤、突出显示等操作。
* [Json Parser](https://plugins.jetbrains.com/plugin/10650-json-parser)
    * 用于验证和格式化 JSON 字符串的 UI
* [Multirun](https://plugins.jetbrains.com/plugin/7248-multirun)
    * 将多个运行配置分组并单击一次即可运行它们。
* [Run Configuration as Action](https://plugins.jetbrains.com/plugin/9448-run-configuration-as-action)
    * 将所有运行配置注册为操作以为其分配快捷方式。

### 云/DevOps 工具

* [AWS Toolkit](https://plugins.jetbrains.com/plugin/11349-aws-toolkit)
    * 将与 AWS 的集成添加到 IDE 中 - 资源浏览器、运行/调试 lambda、日志、s3 浏览器等。
* [Azure Toolkit for Rider](https://plugins.jetbrains.com/plugin/11220-azure-toolkit-for-rider)
    * Jetbrains 插件，用于与 Azure 集成到 IDE 中 - 资源浏览器、运行/调试 Azure Functions 等。
* [Azure Toolkit for IntelliJ](https://plugins.jetbrains.com/plugin/8053-azure-toolkit-for-intellij)
    * 用于与 Azure 集成到 IDE 中的 Microsoft 插件 - 资源浏览器、运行/调试 Azure Functions 等。
* [Application Insights Debug Log Viewer]()
    * 在应用程序调试会话期间显示 Azure Application Insights 日志。
* [Kubernetes](https://plugins.jetbrains.com/plugin/10485-kubernetes)
    * kubernetes 和 helm 配置的高级编辑器，具有对 k8s 集群和 pod 的运行时支持（附加 pod 控制台、查看日志等）。
* [Jenkins Control](https://plugins.jetbrains.com/plugin/6110-jenkins-control)
    * 添加与 Jenkins 的集成 - 触发作业、查看作业日志等。
* [Terraform and HCL](https://plugins.jetbrains.com/plugin/7808-terraform-and-hcl)
    * 为 HCL 和 HIL 文件添加 IDE 功能（自动完成、语法突出显示等）。
* [BashSupport Pro](https://plugins.jetbrains.com/plugin/13841-bashsupport-pro)
    * 添加用于 shell 脚本编写的 IDE 功能（自动完成、语法突出显示等）。
* [PowerShell](https://plugins.jetbrains.com/plugin/10249-powershell)
    * 为 PowerShell 脚本添加 IDE 功能（自动完成、语法突出显示等）。

## 特定语言

### Javascript/Typescript

* [Quokka](https://plugins.jetbrains.com/plugin/9667-quokka)
    * 编辑器内的 Javascript 游乐场。允许通过访问项目文件来动态编写和测试代码。
* [Wallaby](https://plugins.jetbrains.com/plugin/15742-wallaby)
    * JavaScript 智能测试运行器可连续运行您的测试。当您更改代码时，它会立即向代码编辑器报告代码覆盖率和其他结果。
* [Run configuration for Typescript](https://plugins.jetbrains.com/plugin/10841-run-configuration-for-typescript)
    * 简化 TS 文件的运行。
* [LogIt](https://plugins.jetbrains.com/plugin/13432-logit)
    * 通过快捷方式插入“console.log”功能。

#### Javascript/Typescript 构架

* [GraphQL](https://plugins.jetbrains.com/plugin/8097-graphql)
    * 支持 GraphQL。模式感知补全、语法突出显示等。
* [Angular Component Folding](https://plugins.jetbrains.com/plugin/10090-angular-component-folding)
    * 将具有相同名称和不同扩展名的文件分组。
* [IntelliVue](https://plugins.jetbrains.com/plugin/12014-intellivue)
    * 为 Vue 单文件组件提供分析、操作和实用程序。该插件在标准 Vue 插件之上添加了附加功能。
* [React Buddy](https://plugins.jetbrains.com/plugin/17467-react-buddy)
    * 提供 MUI (MaterialUI)、Ant Design、Chakra UI、Mantine 的组件面板。帮助创建和使用 Storybook 故事。
* [React Native Console](https://plugins.jetbrains.com/plugin/9564-react-native-console)
    * 运行 React Native 命令并使 RN 编码更容易。

### Java

* [Byte Code Analyzer](https://plugins.jetbrains.com/plugin/16970-byte-code-analyzer)
    * 提供 .class 文件的不同视图，并包含用于字节码分析的附加工具。
* [RoboPOJOGenerator](https://plugins.jetbrains.com/plugin/8634-robopojogenerator)
    * 从 JSON 和其他格式生成 POJO 类。
* [GenerateAllSetter](https://plugins.jetbrains.com/plugin/9360-generateallsetter)
    * 在对象上生成设置器。对于映射器和转换器很有用。
* [Innerbuilder Generator](https://plugins.jetbrains.com/plugin/15615-innerbuilder-generator)
    * 在所选类中生成 Builder 类。

#### Java 构架

* [Maven Helper](https://plugins.jetbrains.com/plugin/7179-maven-helper)
    * 通过其他有用的功能扩展 Maven 支持，例如分析和排除依赖项。
* [JPA Buddy](https://plugins.jetbrains.com/plugin/15075-jpa-buddy)
    * 通过附加检查、生成向导、自动生成数据库迁移等扩展对数据库相关工具（Hibernate、Spring Data、Flyway、MapStruct 等）的支持。
* [Spring Boot Helper](https://plugins.jetbrains.com/plugin/18622-spring-boot-helper)
    * 扩展了对 Spring Boot 的支持 - 启动初始化、自动完成 Spring Boot/Cloud 配置键/值、Spring 参考配置、Spring 元数据文档。

### Python

* [Python Security](https://plugins.jetbrains.com/plugin/13609-python-security)
    * 为 Python 添加额外的静态代码分析检查。
* [Python Annotations](https://plugins.jetbrains.com/plugin/12035-python-annotations)
    * 提供类型注释中常见错误的快速修复。
* [Pylint](https://plugins.jetbrains.com/plugin/11084-pylint)
    * 将 pylint 静态代码分析集成添加到 IDE 中。

#### Python 构架

* [Requirements](https://plugins.jetbrains.com/plugin/10837-requirements)
    * 通过添加语法突出显示、包版本检查、自动完成等来改进 requests.txt 文件的工作。
* [Django command runner](https://plugins.jetbrains.com/plugin/13834-django-command-runner)
    * 只需从定义文件运行 django 管理命令即可。
* [Odoo](https://plugins.jetbrains.com/plugin/13499-odoo)
    * 提供 Odoo 框架支持（代码自动完成、代码导航等）
* [Odoo Autocompletion Support](https://plugins.jetbrains.com/plugin/13083-odoo-autocompletion-support)
    * 为 Odoo 插件/模块提供增强的自动完成功能。

### C#

* [Heap Allocations Viewer](https://plugins.jetbrains.com/plugin/9223-heap-allocations-viewer)
    * 突出显示本地对象分配、装箱、委托和闭包创建点。
* [Rossynt](https://plugins.jetbrains.com/plugin/16902-rossynt)
    * Roslyn 的 C# 语法树查看器。

#### C# 构架

* [.NET Core User Secrets](https://plugins.jetbrains.com/plugin/10183--net-core-user-secrets)
    * 添加了创建和打开 ASP.NET 用户机密的功能。
* [Structured Logging](https://plugins.jetbrains.com/plugin/12832-structured-logging)
    * 用于结构化日志记录的分析器。支持 Serilog、NLog 和 Microsoft.Extensions.Logging。
* [MoqComplete](https://plugins.jetbrains.com/plugin/12659-moqcomplete)
    * 最小起订量的代码完成。

### PHP

* [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-)
    * 为 PHP 添加额外的静态代码分析检查。
* [PHP Toolbox](https://plugins.jetbrains.com/plugin/8133-php-toolbox)
    * 改进了 PHP 和常用框架/库（Doctrine、Twig 等）的自动完成功能
* [PHP Annotations](https://plugins.jetbrains.com/plugin/7320-php-annotations)
    * 扩展 PhpStorm 以支持 DocBlocks 中的注释并提供额外的属性功能。
* [deep-assoc-completion](https://plugins.jetbrains.com/plugin/9927-deep-assoc-completion)
    * 该插件允许您自动完成从其他函数推断的 PHP 数组键。

#### PHP 构架

* [Laravel Idea](https://plugins.jetbrains.com/plugin/13441-laravel-idea/reviews)
    * 添加对 Laravel 框架的支持。
* [Symfony Support](https://plugins.jetbrains.com/plugin/7219-symfony-support)
    * 添加对 Symfony 框架的支持。
* [Yii2 Support](https://plugins.jetbrains.com/plugin/9388-yii2-support)
    * 添加对 Yii2 框架的支持。
* [PHPUnit Enhancement](https://plugins.jetbrains.com/plugin/9674-phpunit-enhancement)
    * PHPUnit 的自动完成和代码导航。

### C/C++

* [C/C++ Coverage](https://plugins.jetbrains.com/plugin/11031-c-c--coverage)
    * GCC 和 Clang 的 C 和 C++ 线路、区域和分支覆盖率收集器。
* [EzArgs](https://plugins.jetbrains.com/plugin/16411-ezargs)
    * 提供将参数传递给 C++ 运行配置的选项，只需将参数写入工具栏上的下拉框中即可。
* [Compiler Explorer](https://plugins.jetbrains.com/plugin/11064-compiler-explorer)
    * 显示来自远程 Compiler Explorer 实例的编译结果。
* [Bazel for CLion](https://plugins.jetbrains.com/plugin/9554-bazel-for-clion)
    * Google 插件添加对 Bazel 构建的支持。
* [CMake Plus]()
    * 扩展 CMake 语言支持（突出显示、代码导航、检查等）。

### Rust

* [RON Extended Support](https://plugins.jetbrains.com/plugin/15878-ron-extended-support)
    * 添加对 Rusty 对象表示法文件的支持（代码完成、语法突出显示等）。

### Go

* [Go Linter](https://plugins.jetbrains.com/plugin/12496-go-linter/reviews)
    * 提供 golangci-lint 检查和动态自动修复

## 人工智能代码补全

* [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot)
    * 启用 GitHub Copilot 与 IDE 集成。
* [Tabnine AI Code Completion- JS Java Python TS Rust Go PHP & More](https://plugins.jetbrains.com/plugin/12798-tabnine-ai-code-completion-js-java-python-ts-rust-go-php--more)
    * 启用 Tabnine 与 IDE 集成。
* [AWS Toolkit](https://plugins.jetbrains.com/plugin/11349-aws-toolkit)
    * 启用 Amazon CodeWhisperer 与 IDE 集成。

## 主题

* [Material UI](https://plugins.jetbrains.com/plugin/8006-material-theme-ui)
* [Gerry Themes Pro](https://plugins.jetbrains.com/plugin/19668-gerry-themes-pro)
* [Gruvbox - Theme](https://plugins.jetbrains.com/plugin/20558-gruvbox--theme)
* [One Dark](https://plugins.jetbrains.com/plugin/11938-one-dark-theme)
* [Nord](https://plugins.jetbrains.com/plugin/10321-nord)

## 玩笑

* [Nyan Progress Bar](https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar)
* [Gopher](https://plugins.jetbrains.com/plugin/12875-gopher)
* [Waifu Motivator](https://plugins.jetbrains.com/plugin/13381-waifu-motivator)
* [Power Mode II](https://plugins.jetbrains.com/plugin/8251-power-mode-ii)
* [Anime Memes](https://plugins.jetbrains.com/plugin/15865-anime-memes)
