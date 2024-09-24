# Awesome Jetbrains Plugins

Jetbrains 插件的精选列表。大多数插件与所有 Jetbrains IDE 兼容（IntelliJ IDEA、PyCharm、WebStorm、PhpStorm、Rider、CLion、RubyMine、GoLand、Aqua、Android Studio）。 IDE 特定插件放置在“Language具体”部分。另请记住，所有 Jetbrains IDE 都对编程提供强大的开箱即用支持语言本身和主要框架，默认情况下启用，因此将它们包含到此中是没有意义的列表。

* [Awesome Jetbrains Plugins](#awesome-jetbrains-plugins)
    * [用户界面](#用户界面)
    * [代码编辑器](#代码编辑器)
    * [导航](#导航)
    * [实用程序](#实用程序)
    * [版本控制](#版本控制)
    * [工具](#工具)
        * [其他文件类型支持](#其他文件类型支持)
        * [与其他工具的集成](#与其他工具的集成)
        * [杂项](#杂项)
        * [云/DevOps 工具](#云devops-工具)
    * [特定语言](#特定语言)
        * [Javascript/Typescript](#javascripttypescript)
            * [Javascript/Typescript 构架](#javascripttypescript-构架)
        * [Java](#java)
            * [Java 构架](#java-构架)
        * [Kotlin](#kotlin)
        * [Android](#android)
        * [Python](#python)
            * [Python 构架](#python-构架)
        * [C#](#c)
            * [C# 构架](#c-构架)
        * [PHP](#php)
            * [PHP 构架](#php-构架)
        * [C/C++](#cc)
        * [Rust](#rust)
        * [Go](#go)
    * [AI/LLM 集成](#aillm-集成)
    * [主题](#主题)
    * [有趣](#有趣)

## 用户界面

* [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x)
    * 帮助您在工作时学习基本的快捷方式。当您在 IDE 内的按钮上使用鼠标时，键启动子 X 显示您应该使用的键盘快捷键。
* [Window Resizer](https://plugins.jetbrains.com/plugin/18045-window-resizer)
    * 调整 IDE 窗口的大小。在消息程序中进行屏幕共享时很有用。
* [Extra Icons](https://plugins.jetbrains.com/plugin/11058-extra-icons)
    * 为 Travis YML、GitLab YML、Angular 文件等文件添加 500 多个图标。
* [CodeGlance Pro](https://plugins.jetbrains.com/plugin/18824-codeglance-pro)
    * 在编辑器窗格中显示缩小的源代码概述（类似于 Sublime Text）。小地图允许快速滚动让您可以直接跳到代码部分。
* [Extra ToolWindow Colorful Icons](https://plugins.jetbrains.com/plugin/16604-extra-toolwindow-colorful-icons)
    * 使工具窗口图标变得丰富多彩。对“新用户界面”非常有帮助。
* [Icon Viewer 2](https://plugins.jetbrains.com/plugin/13995-icon-viewer-2)
    * 在项目资源管理器中将图像显示为图标。

## 代码编辑器

* [Better Highlights](https://plugins.jetbrains.com/plugin/12895-better-highlights)
    * 允许对注释、语言关键字、方法/函数进行着色。
        * 显示方法下的认知复杂性。
        * 能够在注释中引用源代码和文件。
* [HighlightBracketPair](https://plugins.jetbrains.com/plugin/17320-highlightbracketpair)
    * 突出显示当前括号对，包括 HTML/XML 标签。
* [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)
    * 为几乎放置的括号着色。
* [Indent Rainbow](https://plugins.jetbrains.com/plugin/13308-indent-rainbow)
    * 给凹痕上色。
* [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
    * 添加对 Vim 的 Modal Editing 概念的支持。如果你愿意采用它，可以大大提高你的生产力。
    * 模态编辑是一个概念，其中文本编辑器的行为取决于它所处的当前模式。Vim 有三种模式：用于导航和编辑命令的正常模式、用于直接键入和编辑文本的插入模式以及用于选择和操作文本块的可视模式。
* [IdeaVim-Quickscope](https://plugins.jetbrains.com/plugin/19417-ideavim-quickscope)
    * 一行中每个单词中的唯一字符始终突出显示，以帮助您使用 f、F 进行导航。
* [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)
    * 允许将插入符号快速导航到编辑器中可见的任何位置。
* [Kursor](https://plugins.jetbrains.com/plugin/22072-kursor)
    * 根据当前上下文（当前源代码语言、当前系统语言、大写锁定状态等）更改光标视觉效果。

## 导航

* [Frame Switcher](https://plugins.jetbrains.com/plugin/7138-frame-switcher)
    * 在项目之间切换（将打开项目，如果尚未打开）。
* [HarpoonIJ](https://plugins.jetbrains.com/plugin/20782-harpoonij)
    * 通过标记最多 5 个可通过热键访问的常用文件来简化代码导航。
* [Focus on Active Task](https://plugins.jetbrains.com/plugin/9824-focus-on-active-task)
    * 过滤掉项目树中不相关的文件/路径。在一千个文件项目中可用于限制文件的可见性。

## 实用程序

* [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
    * 用于操作纯字符串的各种工具。例如，排序、过滤、大小写切换等。您可以为任何操作添加快捷方式，最有用的是 快捷方式 在情况之间切换。
* [Custom Postfix Templates](https://plugins.jetbrains.com/plugin/9862-custom-postfix-templates)
    * 为各种语言添加额外的 postfix 自动完成模板。默认情况下，不存在任何模板。您需要花时间找出对您的语言/项目有用的模板，并手动将它们添加为 “Web 模板”。
* [Json Helper](https://plugins.jetbrains.com/plugin/13873-json-helper)
    * 操作 JSON 的各种工具。例如，json路径搜索、escape/unescape、uglify/prettify等。
* [Randomness](https://plugins.jetbrains.com/plugin/9836-randomness)
    * 生成并插入随机数、字符串和 UUID。在单元测试中很有用。
* [Developer Tools](https://plugins.jetbrains.com/plugin/21904-developer-tools)
    * 为常用工具提供 IDE 内部的 UI，例如 JWT 令牌解码、RegEx 检查器、文本差异等。

## 版本控制

* [.ignore](https://plugins.jetbrains.com/plugin/7495--ignore)
    * 通过添加语法突出显示、生成 .gitignore 规则、条目检查等来改进 .gitignore 文件的工作。
* [GitToolBox](https://plugins.jetbrains.com/plugin/7499-gittoolbox)
    * 通过启用自动完成、显示各种附加信息（例如提前提交的数量等）、分支清理、自动获取和各种其他功能来改进 git 的工作。
* [GitLive](https://plugins.jetbrains.com/plugin/11955-gitlive)
    * 主要功能是实时合并冲突检测。
* [Conventional Commit](https://plugins.jetbrains.com/plugin/13389-conventional-commit)
    * 在 VCS 提交对话框中为[常规提交](https://www.conventionalcommits.org/en/v1.0.0/)（也称为语义提交）提供自动完成功能。
* [Commit Message Template](https://plugins.jetbrains.com/plugin/23100-commit-message-template)
    * 当不需要传统的提交方法时，允许定义自定义提交消息模板。
* [GitLink](https://plugins.jetbrains.com/plugin/8183-gitlink)
    * 允许在 git repo 上快速生成链接，这对于在企业通讯中与其他人共享代码非常有用。
    * 支持 GitHub、Bitbucket、GitLab、Azure 等。
* [Find Pull Request](https://plugins.jetbrains.com/plugin/8262-find-pull-request)
    * 在右键单击时添加 Open In->Pull Request 操作，这会打开带有代码更改的 PR。
* [Azure DevOps](https://plugins.jetbrains.com/plugin/7981-azure-devops)
    * 允许在 Azure DevOps Services 或 Team Foundation Server(TFS) 上使用 Git 和 TFVC 存储库。
* [Azd](https://plugins.jetbrains.com/plugin/22319-azd)
    * 用于与 Azure DevOps 集成的付费插件。比 Microsoft 的 Azure DevOps 插件工作得更好。

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
    * “.log”文件的交互式查看器，带有额外的语法突出显示。
* [Debug Image Viewer (former OpenCV Image Viewer)](https://plugins.jetbrains.com/plugin/14371-debug-image-viewer-former-opencv-image-viewer-)
    * 显示 OpenCV 图像（ndarray 或 Mat），而无需使用其他工具停止调试器。
* [BinEd - Binary/Hex Editor](https://plugins.jetbrains.com/plugin/9339-bined--binary-hex-editor)
    * 允许以二进制/十六进制模式查看和编辑任何文件。

### 与其他工具的集成

* [SonarLint](https://plugins.jetbrains.com/plugin/7973-sonarlint)
    * 用于静态代码分析的 SonarQube 插件。
* [GitHub Actions Manager](https://plugins.jetbrains.com/plugin/19347-github-actions-manager)
    * 直接在 IDE 中查看工作流程运行和状态。
* [GitLab Master](https://plugins.jetbrains.com/plugin/20347-gitlab-helper)
    * 添加与 GitLab 的完全集成 - 管理合并请求、管道等。
* [GitLab Merge Requests](https://plugins.jetbrains.com/plugin/18689-gitlab-merge-requests)
    * 在 IDE 中查看 GitLab 合并请求。
* [GitLab CICD - Pipelines & Jobs, Builds Run Cancel Retry View Log](https://plugins.jetbrains.com/plugin/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log)
    * 允许从 IDE 查看管道/作业的状态和详细信息。增加了触发管道/作业、下载日志和作业工件的可能性。
* [Jira Integration](https://plugins.jetbrains.com/plugin/11169-jira-integration)
    * 添加与 Jira 的集成 - 从 IDE 查看和更新 Jira 问题的状态。
* [Bitbucket Pull Requests](https://plugins.jetbrains.com/plugin/13538-bitbucket-pull-requests)
    * 添加与 BitBucket 的集成 - 在 IDE 中审查 PR、批准/拒绝/合并 PR 等。
* [New Relic CodeStream](https://plugins.jetbrains.com/plugin/12206-new-relic-codestream-github-gitlab-prs-and-code-review)
    * 添加与任务管理和版本控制工具（bitbucket、jira、gitlab、GitHub 等）的集成，这
      允许从 IDE 执行所有操作。还包含协作工具以及与 Slack 和 Teams 的集成。
      CodeStream 本身和插件都是免费的，因此绝对值得尝试。

### 杂项

* [Archive Browser](https://plugins.jetbrains.com/plugin/9491-archive-browser)
    * 允许浏览存档内的文件，包括嵌套存档。还支持嵌套 .jar 文件。
    * 它已经两年没有更新了，但在最新版本的 IDE 中仍然运行良好。
* [Grep Console](https://plugins.jetbrains.com/plugin/7125-grep-console)
    * 还可以在 IDE 终端内进行拖尾、过滤、突出显示等操作。
* [Json Parser](https://plugins.jetbrains.com/plugin/10650-json-parser)
    * 用于验证和格式化 JSON 字符串的 UI
* [Multirun](https://plugins.jetbrains.com/plugin/7248-multirun)
    * 将多个运行配置分组并单击一次即可运行它们。
* [Run Configuration as Action](https://plugins.jetbrains.com/plugin/9448-run-configuration-as-action)
    * 将所有运行配置注册为操作以为其分配快捷方式。
* [Naming Is Hard](https://plugins.jetbrains.com/plugin/17272-naming-is-hard)
    * 为新项目和模块生成漂亮的随机名称。
* [Translation](https://plugins.jetbrains.com/plugin/8579-translation)
    * 将选定的文本翻译成所需的语言。

### 云/DevOps 工具

* [AWS Toolkit](https://plugins.jetbrains.com/plugin/11349-aws-toolkit)
    * 将与 AWS 的集成添加到 IDE 中 - 资源浏览器、运行/调试 lambda、日志、s3 浏览器等。
* [Azure Toolkit for Rider](https://plugins.jetbrains.com/plugin/11220-azure-toolkit-for-rider)
    * Jetbrains 插件，用于与 Azure 集成到 IDE 中 - 资源浏览器、运行/调试 Azure Functions 等。
* [Azure Toolkit for IntelliJ](https://plugins.jetbrains.com/plugin/8053-azure-toolkit-for-intellij)
    * 用于与 Azure 集成到 IDE 中的 Microsoft 插件 - 资源浏览器、运行/调试 Azure Functions 等。
* [Application Insights Debug Log Viewer](https://plugins.jetbrains.com/plugin/13984-application-insights-debug-log-viewer)
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
* [NPM Update Dependencies](https://plugins.jetbrains.com/plugin/21105-npm-update-dependencies)
    * 突出显示 package.json 中的过时版本，并允许单击更新版本。
* [Run configuration for Typescript](https://plugins.jetbrains.com/plugin/10841-run-configuration-for-typescript)
    * 简化 TS 文件的运行。
* [LogIt](https://plugins.jetbrains.com/plugin/13432-logit)
    * 通过快捷方式插入“console.log”功能。

#### Javascript/Typescript 构架

* [GraphQL](https://plugins.jetbrains.com/plugin/8097-graphql)
    * 支持 GraphQL。模式感知补全、语法突出显示等。
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
* [JRebel and XRebel](https://plugins.jetbrains.com/plugin/4441-jrebel-and-xrebel)
    * 与 JRebel 热重载和 XRebel 性能分析器集成。
* [VisualVM Launcher](https://plugins.jetbrains.com/plugin/7115-visualvm-launcher)
    * 允许从 IDE 使用 VisualVM。
* [MetricsTree](https://plugins.jetbrains.com/plugin/13959-metricstree)
    * 显示 Java 的各种代码指标。从简单的代码行开始，以 QMOOD 质量属性、Robert Martin 指标等结尾。

#### Java 构架

* [JPA Buddy](https://plugins.jetbrains.com/plugin/15075-jpa-buddy)
    * 通过附加检查、生成向导、自动生成数据库迁移等扩展对数据库相关工具（Hibernate、Spring Data、Flyway、MapStruct 等）的支持。
* [Spring Boot Helper](https://plugins.jetbrains.com/plugin/18622-spring-boot-helper)
    * 扩展了对 Spring Boot 的支持 - 启动初始化、自动完成 Spring Boot/Cloud 配置键/值、Spring 参考配置、Spring 元数据文档。
* [Maven Helper](https://plugins.jetbrains.com/plugin/7179-maven-helper)
    * 通过其他有用的功能扩展 Maven 支持，例如分析和排除依赖项。
* [Maven Dependency Checker](https://plugins.jetbrains.com/plugin/18525-maven-dependency-checker)
    * 检查是否有较新版本的 Maven 依赖项。
* [Gradle Daemons View](https://plugins.jetbrains.com/plugin/22600-gradle-daemons-view)
    * 允许从 IDE 查看和停止 Gradle 守护进程。

### Kotlin

* [JSON To Kotlin Class (JsonToKotlinClass)](https://plugins.jetbrains.com/plugin/9960-json-to-kotlin-class-jsontokotlinclass-)
    * 从 JSON 到 Kotlin 数据类的专门转换器。
* [ktfmt](https://plugins.jetbrains.com/plugin/14912-ktfmt)
    * Kotlin 源代码格式化程序。如果您对内置格式化程序不满意，则很有用。
* [detekt](https://plugins.jetbrains.com/plugin/10761-detekt)
    * Kotlin 的附加静态代码分析。

### Android

* [adb_idea](https://plugins.jetbrains.com/plugin/7380-adb-idea)
    * 将常用的 ADB 命令添加到 IDE 中。
* [ADB Tools](https://plugins.jetbrains.com/plugin/18153-adb-tools)
    * 添加了广泛的 ADB 功能。在使用多个设备时很有用。
* [Compose Color Preview](https://plugins.jetbrains.com/plugin/21298-compose-color-preview)
    * 在 Android Color 的装订线中绘制颜色。

### Python

* [Python Security](https://plugins.jetbrains.com/plugin/13609-python-security)
    * 为 Python 添加额外的静态代码分析检查。
* [Python Annotations](https://plugins.jetbrains.com/plugin/12035-python-annotations)
    * 提供类型注释中常见错误的快速修复。
* [Pylint](https://plugins.jetbrains.com/plugin/11084-pylint)
    * 将 pylint 静态代码分析集成添加到 IDE 中。

#### Python 构架

* [Odoo](https://plugins.jetbrains.com/plugin/13499-odoo)
    * 提供 Odoo 框架支持（代码自动完成、代码导航等）
* [Odoo Autocompletion Support](https://plugins.jetbrains.com/plugin/13083-odoo-autocompletion-support)
    * 为 Odoo 插件/模块提供增强的自动完成功能。
* [Lets-Plot in SciView](https://plugins.jetbrains.com/plugin/14379-lets-plot-in-sciview)
    * 提供交互式科学计算和数据可视化。

### C#

* [Heap Allocations Viewer](https://plugins.jetbrains.com/plugin/9223-heap-allocations-viewer)
    * 突出显示本地对象分配、装箱、委托和闭包创建点。
* [Rossynt](https://plugins.jetbrains.com/plugin/16902-rossynt)
    * Roslyn 的 C# 语法树查看器。
    * 现在不支持 .NET 8，插件看起来已被废弃。

#### C# 构架

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
    * 扩展 PhpStorm 以支持 DocBlock 中的注释，并提供其他属性功能。
* [deep-assoc-completion](https://plugins.jetbrains.com/plugin/9927-deep-assoc-completion)
    * 该插件允许您自动完成从其他函数推断的 PHP 数组键。
    * 它已经 2 年没有更新了，但在最新版本的 IDE 中仍然运行良好。

#### PHP 构架

* [Laravel Idea](https://plugins.jetbrains.com/plugin/13441-laravel-idea)
    * 添加对 Laravel 框架的支持。
* [Collector](https://plugins.jetbrains.com/plugin/15246-collector)
    * 为 Laravel Collections 添加多个重构。
* [Symfony Support](https://plugins.jetbrains.com/plugin/7219-symfony-support)
    * 添加对 Symfony 框架的支持。
* [Yii2 Framework Support](https://plugins.jetbrains.com/plugin/23693-yii2-framework-support/versions)
    * 添加对 Yii2 框架的支持。
* [Magento PhpStorm](https://plugins.jetbrains.com/plugin/8024-magento-phpstorm)
    * 免费插件，扩展了对 Magento 2 的支持。在最新版本的 IDE 中存在兼容性问题。
* [Magento and Adobe Commerce PhpStorm by Atwix](https://plugins.jetbrains.com/plugin/20554-magento-and-adobe-commerce-phpstorm-by-atwix)
    * 免费增值插件，它通过检查和改进的导航扩展了对 Magento 2 的支持。
* [PHPUnit Enhancement](https://plugins.jetbrains.com/plugin/9674-phpunit-enhancement)
    * PHPUnit 的自动完成和代码导航。

### C/C++

* [EzArgs](https://plugins.jetbrains.com/plugin/16411-ezargs)
    * 提供将参数传递给 C++ 运行配置的选项，只需将参数写入工具栏上的下拉框中即可。
* [Compiler Explorer](https://plugins.jetbrains.com/plugin/11064-compiler-explorer)
    * 显示来自远程 Compiler Explorer 实例的编译结果。
    * 目前无法与 CLion Nova 一起使用，因为 Jetbrains 没有提供任何迁移指南。
* [Bazel for CLion](https://plugins.jetbrains.com/plugin/9554-bazel-for-clion)
    * Google 插件添加对 Bazel 构建的支持。
* [CMake Plus](https://plugins.jetbrains.com/plugin/12869-cmake-plus)
    * 扩展 CMake 语言支持（高亮显示、代码导航、检查等）。
* [Serial Port Monitor](https://plugins.jetbrains.com/plugin/8031-serial-port-monitor)
    * 允许从 IDE 与 Arduino 等串行设备通信。

### Rust

* [RON Extended Support](https://plugins.jetbrains.com/plugin/15878-ron-extended-support)
    * 添加对 Rusty Object Notation 文件（代码完成、语法高亮等）的支持。
* [RustJson](https://plugins.jetbrains.com/plugin/22393-rustjson)
    * 将 JSON 转换为 Rust 结构体。

### Go

* [Go Linter](https://plugins.jetbrains.com/plugin/12496-go-linter)
    * 提供 golangci-lint 检查和动态自动修复

## AI/LLM 集成

* [AI Assistant](https://plugins.jetbrains.com/plugin/22282-ai-assistant)
    * Jetbrains 原生 AI 集成。
* [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot)
    * 启用 GitHub Copilot 与 IDE 的集成。
    * 目前，它被认为是 Jetbrains IDE 中最有用的 AI。
* [Tabnine: AI Code Completion & Chat in Java JS/TS Python & More](https://plugins.jetbrains.com/plugin/12798-tabnine-ai-code-completion-js-java-python-ts-rust-go-php--more)
    * 启用 Tabnine 与 IDE 的集成。
* [Amazon Q](https://plugins.jetbrains.com/plugin/24267-amazon-q/)
    * 启用 Amazon CodeWhisperer 与 IDE 的集成。
* [Codiumate - Code, test and review with confidence - by CodiumAI](https://plugins.jetbrains.com/plugin/21206-codiumai--integrity-agent-powered-by-gpt-3-5-4)
    * 启用 CodiumAI 与 IDE 的集成。
* [CodeGPT](https://plugins.jetbrains.com/plugin/21056-codegpt)
    * 在 IDE 中集成 AI 聊天。支持所有主要提供商（OpenAI、Anthropic、Azure、Mistral 等）
* [AI Commits](https://plugins.jetbrains.com/plugin/21335-ai-commits)
    * 使用 LLM 生成提交消息。支持 OpenAI、Anthropic、Gemini 等。
* [Grazie Pro](https://plugins.jetbrains.com/plugin/16136-grazie-pro)
    * Jetbrains 用于语法和拼写检查的付费插件。还具有 8 种语言的翻译功能。

## 主题

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

## 有趣

* [Nyan Progress Bar](https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar)
* [Cats Progress Bar](https://plugins.jetbrains.com/plugin/22740-cats-progress-bar)
* [Gopher](https://plugins.jetbrains.com/plugin/12875-gopher)
    * 它已经 3 年没有更新了，但在最新版本的 IDE 中仍然运行良好。
* [Power Mode II](https://plugins.jetbrains.com/plugin/8251-power-mode-ii)
* [Anime Memes](https://plugins.jetbrains.com/plugin/15865-anime-memes)
* [Space Invaders](https://plugins.jetbrains.com/plugin/19383-space-invaders)