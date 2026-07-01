# Awesome Jetbrains Plugins

Jetbrains 插件的精选列表。大多数插件都与所有 Jetbrains IDE（IntelliJ IDEA、PyCharm、
WebStorm、PhpStorm、Rider、CLion、RubyMine、GoLand、Aqua、Android Studio）兼容。特定于 IDE 的插件放置在
“特定语言”部分。另请记住，所有 Jetbrains IDE 都对编程语言本身和主要框架提供了出色的开箱即用支持，
它们默认处于启用状态，因此没有必要将它们包含在此列表中。

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
            * [Javascript/Typescript 框架](#javascripttypescript-框架)
        * [Java](#java)
            * [Java 框架](#java-框架)
        * [Kotlin](#kotlin)
        * [Android](#android)
        * [Python](#python)
            * [Python 框架](#python-框架)
        * [C#](#c)
            * [C# 框架](#c-框架)
        * [PHP](#php)
            * [PHP 框架](#php-框架)
        * [C/C++](#cc)
        * [Rust](#rust)
        * [Go](#go)
    * [AI/LLM 集成](#aillm-集成)
    * [主题](#主题)
    * [有趣](#有趣)

## 用户界面

* [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x)
    * 帮助您在工作时学习基本的快捷方式。当您在 IDE 内的按钮上使用鼠标时，Key Promoter X 会显示您应该使用的键盘快捷键。
* [Window Arranger](https://plugins.jetbrains.com/plugin/18045-window-arranger)
    * 调整、排列和对齐 IDE 窗口。支持在项目之间切换和窗口定位（左/右/上/下、最大化、水平/垂直对齐）。在屏幕共享期间很有用。
* [Extra Icons](https://plugins.jetbrains.com/plugin/11058-extra-icons)
    * 为 Travis YML、GitLab YML、Angular 文件等文件添加 500 多个图标。
* [CodeGlance Pro](https://plugins.jetbrains.com/plugin/18824-codeglance-pro)
    * 在编辑器窗格中显示缩小的源代码概述（类似于 Sublime Text）。小地图允许快速滚动让您可以直接跳到代码部分。
* [Extra ToolWindow Colorful Icons](https://plugins.jetbrains.com/plugin/16604-extra-toolwindow-colorful-icons)
    * 使工具窗口图标变得丰富多彩。包含多种图标主题。
* [Icon Viewer 2](https://plugins.jetbrains.com/plugin/13995-icon-viewer-2)
    * 在项目资源管理器中将图像显示为图标。

## 代码编辑器

* [Better Highlights](https://plugins.jetbrains.com/plugin/12895-better-highlights)
    * 允许对注释、语言关键字、方法/函数进行着色。
    * 显示方法下的认知复杂性。
    * 启用在注释中引用源代码和文件的功能。
* [HighlightBracketPair](https://plugins.jetbrains.com/plugin/17320-highlightbracketpair)
    * 突出显示当前括号对，包括 HTML/XML 标签。
* [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)
    * 为紧密放置的括号着色。免费增值插件 - 旧版本的基本功能仍然免费，部分高级功能需要付费。
* [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
    * 从 Vim 添加对模态编辑概念的支持。如果你采用它，可以大大提高你的生产力。
    * 模态编辑是一个概念，其中文本编辑器的行为取决于它所处的当前模式。Vim 有三种模式：用于导航和编辑命令的正常模式、用于直接键入和编辑文本的插入模式以及用于选择和操作文本块的可视模式。
* [IdeaVim-Quickscope](https://plugins.jetbrains.com/plugin/19417-ideavim-quickscope)
    * 一行中每个单词中的唯一字符始终突出显示，以帮助您使用 f、F 进行导航。
* [Which-Key](https://plugins.jetbrains.com/plugin/15976-which-key)
    * IdeaVim 扩展，当您键入 leader 键序列时在弹出窗口中显示可用的键绑定。需要 IdeaVim。
* [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)
    * 允许将插入点快速导航到编辑器中可见的任何位置。
* [Kursor](https://plugins.jetbrains.com/plugin/22072-kursor)
    * 根据当前上下文（当前源代码语言、当前系统语言、大写锁定状态等）更改光标视觉效果。

## 导航

* [Frame Switcher](https://plugins.jetbrains.com/plugin/7138-frame-switcher)
    * 在项目之间切换（如果项目尚未打开，则打开项目）。
* [Projects Organizer](https://plugins.jetbrains.com/plugin/30429-projects-organizer)
    * 将最近项目列表转变为结构化目录，支持嵌套分组、标签、收藏、关联项目、备注、文档链接和快速搜索。
* [Focus on Active Task](https://plugins.jetbrains.com/plugin/9824-focus-on-active-task)
    * 过滤掉项目树中不相关的文件/路径。在拥有上千个文件的项目中用于限制文件的可见性。
    * 很长时间没有更新，但仍可在 IDE 中运行。

## 实用程序

* [String Manipulation](https://plugins.jetbrains.com/plugin/2162-string-manipulation)
    * 用于操作纯字符串的各种工具。 例如，排序、筛选等。您可以为任何操作添加快捷方式，最有用的是在大小写之间切换的快捷方式。
    * 允许在鼠标右键单击时通过快捷方式或通过子菜单对任何选定的字符串进行大小写切换（驼峰式命名法、snake_case 等）。
* [Custom Postfix Templates](https://plugins.jetbrains.com/plugin/9862-custom-postfix-templates)
    * 为各种语言添加额外的 postfix 自动完成模板。默认情况下，没有模板。您需要花时间找出对您的语言/项目有用的模板，并手动将它们添加为 “Web 模板”。
* [Json Helper](https://plugins.jetbrains.com/plugin/13873-json-helper)
    * 用于操作 JSON 的各种工具。例如，JSON 路径搜索、escape/unescape、uglify/prettify 等。
* [Randomness](https://plugins.jetbrains.com/plugin/9836-randomness)
    * 生成并插入随机数、字符串、UUID、IP 地址、姓名、电子邮件、电话号码和自定义数据类型。在单元测试中很有用。
* [Developer Tools](https://plugins.jetbrains.com/plugin/21904-developer-tools)
    * 在 IDE 中为常用工具提供 UI，如 JWT 令牌解码器、RegExp 检查器、文本差异等。
* [EnvFile](https://plugins.jetbrains.com/plugin/7861-envfile)
    * 从 .env、YAML 或 JSON 文件为运行配置设置环境变量。与提供语法高亮的 ".env files support" 插件互补。

## 版本控制

* [.ignore](https://plugins.jetbrains.com/plugin/7495--ignore)
    * 通过添加语法突出显示、生成规则、条目检查等来改进 .gitignore 和其他忽略文件（.dockerignore、.npmignore 等）的工作。
* [GitToolBox](https://plugins.jetbrains.com/plugin/7499-gittoolbox)
    * 通过启用自动完成、显示各种附加信息（如领先提交数等）、分支清理、自动获取和各种其他功能来改进 git 的工作。免费增值 - 较新的功能（如内联 blame 注释）需要付费。
* [GitLive](https://plugins.jetbrains.com/plugin/11955-gitlive)
    * 主要功能是实时合并冲突检测。还提供协作者可见性和实时差异。
* [Conventional Commit](https://plugins.jetbrains.com/plugin/13389-conventional-commit)
    * 在 VCS 提交对话框中为[约定式提交](https://www.conventionalcommits.org/en/v1.0.0/)（也称为语义提交）提供自动完成功能。
* [Commit Message Template](https://plugins.jetbrains.com/plugin/23100-commit-message-template)
    * 允许在不需要常规提交方法时定义自定义提交消息模板。
* [GitLink](https://plugins.jetbrains.com/plugin/8183-gitlink)
    * 允许您在 git repo 上快速生成链接，这对于在企业信使中与他人共享代码非常方便。
    * 支持 GitHub、Bitbucket、GitLab、Azure、Gitea、Gerrit 等。
* [Git Machete](https://plugins.jetbrains.com/plugin/14221-git-machete)
    * 分支布局组织器和 rebase/merge 工作流自动化工具。显示分支的树形图，包含与父分支和远程分支的同步状态。使多分支的 rebase/merge/push/pull 操作更加轻松。
* [Find Pull Request](https://plugins.jetbrains.com/plugin/8262-find-pull-request)
    * 在右键单击时添加 Open In->Pull Request 操作，这会打开带有代码更改的 PR。
    * 在”Annotate with Git Blame”下添加”List Pull Request”，其工作方式类似于在 gutter 中显示 PR 而不是提交者。
    * 很长时间没有更新，但仍可在 IDE 中运行。
* [.gitattributes Support](https://plugins.jetbrains.com/plugin/26477--gitattributes-support)
    * 为 .gitattributes 文件添加语法高亮、关键字自动完成和模式匹配。
* [Azd](https://plugins.jetbrains.com/plugin/22319-azd)
    * 用于与 Azure DevOps 集成的付费插件。比 Microsoft 的 Azure DevOps 插件工作得更好。

## 工具

### 其他文件类型支持

* [PlantUML Integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)
    * PlantUML 图表工具集成，允许从纯文本语言创建图表。
* [PDF Viewer](https://plugins.jetbrains.com/plugin/14494-pdf-viewer)
    * 允许在 IDE 中查看 PDF 文件。
* [CSV Editor](https://plugins.jetbrains.com/plugin/10037-csv-editor)
    * 允许在彩色表格和文本编辑器中编辑CSV文件。
      它还提供语法验证、突出显示、自定义等等。
* [Easy I18n](https://plugins.jetbrains.com/plugin/16316-easy-i18n)
    * 允许在树状或表格视图中编辑翻译文件（JSON、YAML、属性）。
* [.env files support](https://plugins.jetbrains.com/plugin/9525--env-files-support)
    * 允许使用自动完成和语法高亮来编辑环境变量文件。
* [Cron & Crontab Support](https://plugins.jetbrains.com/plugin/26412-cron--crontab-support)
    * 高亮 cron 表达式错误，将 cron 语法翻译成简单易懂的英语，并可从 IDE 执行命令。
* [Ideolog](https://plugins.jetbrains.com/plugin/9746-ideolog)
    * “.log”文件的交互式查看器，具有额外的语法高亮显示。
* [Debug Image Viewer (former OpenCV Image Viewer)](https://plugins.jetbrains.com/plugin/14371-debug-image-viewer-former-opencv-image-viewer-)
    * 显示 OpenCV 图像（ndarray 或 Mat），而无需使用其他工具停止调试器。
* [BinEd - Binary/Hex Editor](https://plugins.jetbrains.com/plugin/9339-bined--binary-hex-editor)
    * 允许以二进制/十六进制模式查看和编辑任何文件。

### 与其他工具的集成

* [SonarQube for IDE](https://plugins.jetbrains.com/plugin/7973-sonarqube-for-ide)
    * 用于静态代码分析的 SonarQube 插件。前身为 SonarLint。
* [GitHub Actions Manager](https://plugins.jetbrains.com/plugin/19347-github-actions-manager)
    * 免费增值插件，可直接在 IDE 中查看工作流程运行、日志和状态。付费版本增加了手动触发工作流程、下载构件、部署审批以及重新运行/取消作业等功能。
* [JetLab - Integration for GitLab](https://plugins.jetbrains.com/plugin/18689-gitlab-integration-pro)
    * 在 IDE 中查看 GitLab 合并请求。前身为 GitLab Integration Pro。
* [GitLab CICD - Pipelines & Jobs, Builds Run Cancel Retry View Log](https://plugins.jetbrains.com/plugin/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log)
    * 允许从 IDE 查看管道/作业的状态和详细信息。还支持触发管道/作业、下载日志和下载作业工件。
* [CI Aid for GitLab](https://plugins.jetbrains.com/plugin/25859-ci-aid-for-gitlab)
    * GitLab CI YAML 编辑支持 - 自动完成、架构验证、元素间导航、检查和远程包含缓存。
* [Jira Integration](https://plugins.jetbrains.com/plugin/11169-jira-integration)
    * 添加与 Jira 的集成 - 从 IDE 查看和更新 Jira 问题的状态。
* [Bitbucket Integration Pro](https://plugins.jetbrains.com/plugin/13538-bitbucket-integration-pro)
    * 添加与 BitBucket 的集成 - 在 IDE 中审查 PR、批准/拒绝/合并 PR 等。

### 杂项

* [Archive Browser](https://plugins.jetbrains.com/plugin/9491-archive-browser)
    * 允许浏览档案中的文件，包括嵌套档案。还支持嵌套的 .jar 文件。
    * 很长时间没有更新，但仍可在 IDE 中运行。
* [Grep Console](https://plugins.jetbrains.com/plugin/7125-grep-console)
    * 在 IDE 终端内进行 Grep、拖尾、过滤、突出显示等操作。
* [Native Terminal](https://plugins.jetbrains.com/plugin/9966-native-terminal)
    * 添加一个终端图标，以便在您最喜欢的终端中快速打开项目目录。
* [Json Parser & Code Gen](https://plugins.jetbrains.com/plugin/10650-json-parser--code-gen)
    * 用于验证和格式化 JSON 字符串的 UI。还可以从 JSON 生成 Dart 和 Kotlin 代码，从网络或本地文件加载 JSON，并提供树视图导航。
* [Run Configuration as Action](https://plugins.jetbrains.com/plugin/9448-run-configuration-as-action)
    * 将所有运行配置注册为操作，以便为其分配快捷方式。
    * 很长时间没有更新，但仍可在 IDE 中运行。
* [Translation](https://plugins.jetbrains.com/plugin/8579-translation)
    * 将选定的文本翻译成所需的语言。支持 Google 翻译、Microsoft 翻译和 DeepL。

### 云/DevOps 工具

* [AWS Toolkit](https://plugins.jetbrains.com/plugin/11349-aws-toolkit)
    * 将与 AWS 的集成添加到 IDE 中 - 资源浏览器、运行/调试 lambda、日志、s3 浏览器等。
* [Azure Toolkit for Rider](https://plugins.jetbrains.com/plugin/11220-azure-toolkit-for-rider)
    * Jetbrains 插件，用于在 IDE 中集成 Azure 服务 - 资源浏览器、运行/调试 Azure Functions 等。
* [Azure Toolkit for IntelliJ](https://plugins.jetbrains.com/plugin/8053-azure-toolkit-for-intellij)
    * Microsoft 插件，用于在 IDE 中集成 Azure 服务 - 资源浏览器、运行/调试 Azure Functions 等。
* [Application Insights Debug Log Viewer](https://plugins.jetbrains.com/plugin/13984-application-insights-debug-log-viewer)
    * 在应用程序调试会话期间显示 Azure Application Insights 日志。
* [Google Cloud Code](https://plugins.jetbrains.com/plugin/8079-google-cloud-code)
    * 与 Google Cloud Platform (GCP) 服务集成。
* [Kubernetes](https://plugins.jetbrains.com/plugin/10485-kubernetes)
    * kubernetes 和 helm 配置的高级编辑器，具有对 k8s 集群和 pod 的运行时支持（附加 pod 控制台、查看日志等）。
* [Jenkins Control](https://plugins.jetbrains.com/plugin/6110-jenkins-control)
    * 添加与 Jenkins 的集成 - 触发作业、查看作业日志等。
* [Terraform and HCL](https://plugins.jetbrains.com/plugin/7808-terraform-and-hcl)
    * 为 HCL 和 HIL 文件添加 IDE 功能（自动完成、语法突出显示等）。还支持 OpenTofu 和 Terragrunt。
* [BashSupport Pro](https://plugins.jetbrains.com/plugin/13841-bashsupport-pro)
    * 添加用于 shell 脚本编写的 IDE 功能（自动完成、语法突出显示等）。支持 Bash、POSIX 和 Zsh。
* [PowerShell](https://plugins.jetbrains.com/plugin/10249-powershell)
    * 为 PowerShell 脚本添加 IDE 功能（自动完成、语法突出显示等）。

## 特定语言

### Javascript/Typescript

* [Quokka](https://plugins.jetbrains.com/plugin/9667-quokka)
    * 编辑器中的 JavaScript playground。允许您通过访问项目文件来动态编写和测试代码。
* [Wallaby](https://plugins.jetbrains.com/plugin/15742-wallaby)
    * JavaScript 智能测试运行器可连续运行您的测试。当您更改代码时，它会立即向代码编辑器报告代码覆盖率和其他结果。
* [NPM Update Dependencies](https://plugins.jetbrains.com/plugin/21105-npm-update-dependencies)
    * 突出显示 package.json 中的过时版本，并允许单击更新版本。
* [Run configuration for TypeScript](https://plugins.jetbrains.com/plugin/10841-run-configuration-for-typescript)
    * 简化 TS 文件的运行。
    * 很长时间没有更新，但仍可在 IDE 中运行。
* [LogIt](https://plugins.jetbrains.com/plugin/13432-logit)
    * 通过快捷方式插入“console.log”功能。

#### Javascript/Typescript 框架

* [GraphQL](https://plugins.jetbrains.com/plugin/8097-graphql)
    * 支持 GraphQL。架构感知补全、语法高亮显示等。
* [IntelliVue](https://plugins.jetbrains.com/plugin/12014-intellivue)
    * 为 Vue 单文件组件提供分析、操作和实用程序。该插件在标准 Vue 插件之上添加了附加功能。
* [React Buddy](https://plugins.jetbrains.com/plugin/17467-react-buddy)
    * 提供 MUI (MaterialUI)、Ant Design、Chakra UI、Mantine 的组件面板。帮助创建和使用 Storybook 故事。现已由 JetBrains 捆绑和维护。
* [React Native Console](https://plugins.jetbrains.com/plugin/9564-react-native-console)
    * 运行 React Native 命令并使 RN 编码更容易。

### Java

* [CheckStyle-IDEA](https://plugins.jetbrains.com/plugin/1065-checkstyle-idea)
    * 使用 checkstyle 添加对 Java 文件的实时和按需扫描。
* [Byte Code Analyzer](https://plugins.jetbrains.com/plugin/16970-byte-code-analyzer)
    * 提供 .class 文件的不同视图，并包含用于字节码分析的附加工具。
* [RoboPOJOGenerator](https://plugins.jetbrains.com/plugin/8634-robopojogenerator)
    * 从 JSON 和其他格式生成 POJO 类。
* [JRebel and XRebel for IntelliJ](https://plugins.jetbrains.com/plugin/4441-jrebel-and-xrebel)
    * 与 JRebel 热重载和 XRebel 性能分析器集成。
* [Lightrun](https://plugins.jetbrains.com/plugin/16477-lightrun)
    * 添加了将日志、快照和指标动态注入正在运行的应用程序的功能，无需重新部署，从而可以直接从 IDE 进行实时调试和监控。
* [VisualVM Launcher](https://plugins.jetbrains.com/plugin/7115-visualvm-launcher)
    * 允许您从 IDE 启动 VisualVM。
    * 很长时间没有更新，但仍可在 IDE 中运行。
* [MetricsTree](https://plugins.jetbrains.com/plugin/13959-metricstree)
    * 显示 Java 的各种代码指标。从简单的代码行开始，以 QMOOD 质量属性、Robert Martin 指标等结尾。

#### Java 框架

* [JPA Buddy](https://plugins.jetbrains.com/plugin/15075-jpa-buddy)
    * 通过附加检查、生成向导、自动生成数据库迁移等扩展对数据库相关工具（Hibernate、Spring Data、Flyway、MapStruct 等）的支持。已被 JetBrains 收购和维护。
* [Spring Boot Helper](https://plugins.jetbrains.com/plugin/18622-spring-boot-helper)
    * 付费插件，扩展了对 Spring Boot 的支持 - 自动完成 Spring Boot/Cloud 配置键/值、Spring 参考配置、Spring 元数据文档、属性的跳转到定义。
* [Maven Helper](https://plugins.jetbrains.com/plugin/7179-maven-helper)
    * 通过其他有用的功能扩展 Maven 支持，例如分析和排除依赖项。
* [Maven Dependency Checker](https://plugins.jetbrains.com/plugin/18525-maven-dependency-checker)
    * 检查是否有较新版本的 Maven 依赖项。
* [Gradle Utilities](https://plugins.jetbrains.com/plugin/16800-gradle-utilities)
    * 列出所有正在运行的 Gradle 守护程序、检查最新的 Gradle 版本、清除 Gradle 缓存和其他工具。

### Kotlin

* [JSON To Kotlin Class (JsonToKotlinClass)](https://plugins.jetbrains.com/plugin/9960-json-to-kotlin-class-jsontokotlinclass-)
    * 从 JSON 到 Kotlin 数据类的专门转换器。
* [ktfmt](https://plugins.jetbrains.com/plugin/14912-ktfmt)
    * Kotlin 源代码格式化程序。如果您对内置格式化程序不满意，则很有用。
* [detekt](https://plugins.jetbrains.com/plugin/10761-detekt)
    * Kotlin 的附加静态代码分析。
* [kotlin-fill-class](https://plugins.jetbrains.com/plugin/10942-kotlin-fill-class)
    * 提供意图操作，用默认值填充空构造函数或函数。对于快速创建测试对象非常有用。

### Android

* [adb_idea](https://plugins.jetbrains.com/plugin/7380-adb-idea)
    * 将常用的 ADB 命令添加到 IDE 中。
* [Compose Color Preview](https://plugins.jetbrains.com/plugin/21298-compose-color-preview)
    * 在 Android Color 的装订线中绘制颜色。

### Python

* [Python Annotations](https://plugins.jetbrains.com/plugin/12035-python-annotations)
    * 提供 Python 类型注释的检查和快速修复 — 简化 Union/Optional，现代化为 PEP 585/695 语法等。
* [Pylint](https://plugins.jetbrains.com/plugin/26358-pylint)
    * 将 pylint 静态代码分析集成添加到 IDE 中。
    * 这是[原始 Pylint 插件](https://plugins.jetbrains.com/plugin/11084-pylint)的重写/更新。

#### Python 框架

* [Django command runner](https://plugins.jetbrains.com/plugin/13834-django-command-runner)
    * 从定义文件运行 django 管理命令。
* [Pydantic](https://plugins.jetbrains.com/plugin/12861-pydantic)
    * 为 Pydantic 模型添加自动完成和重构。
* [Odoo](https://plugins.jetbrains.com/plugin/13499-odoo)
    * 提供 Odoo 框架支持（代码自动完成、代码导航等）
* [Lets-Plot in SciView](https://plugins.jetbrains.com/plugin/14379-lets-plot-in-sciview)
    * 提供交互式科学计算和数据可视化。

### C#

* [Heap Allocations Viewer](https://plugins.jetbrains.com/plugin/9223-heap-allocations-viewer)
    * 突出显示本地对象分配、装箱、委托和闭包创建点。

#### C# 框架

* [Structured Logging](https://plugins.jetbrains.com/plugin/12832-structured-logging)
    * 用于结构化日志记录的分析器。支持 Serilog、NLog 和 Microsoft.Extensions.Logging。
* [MoqComplete](https://plugins.jetbrains.com/plugin/12659-moqcomplete)
    * Moq 框架的代码补全。

### PHP

* [Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-)
    * 为 PHP 添加额外的静态代码分析检查。
* [PHP Toolbox](https://plugins.jetbrains.com/plugin/8133-php-toolbox)
    * 改进了 PHP 和常用框架/库（Doctrine、Twig 等）的自动完成功能。
* [PHP Annotations](https://plugins.jetbrains.com/plugin/7320-php-annotations)
    * 扩展 PhpStorm 以支持 DocBlock 中的注释，并提供 PHP 8 Attributes 功能。
* [deep-assoc-completion](https://plugins.jetbrains.com/plugin/9927-deep-assoc-completion)
    * 该插件允许您自动完成从其他函数推断的 PHP 数组键。
    * 很长时间没有更新，但仍可在 IDE 中运行。

#### PHP 框架

* [Whisperer For Laravel](https://plugins.jetbrains.com/plugin/26042-whisperer-for-laravel)
    * 为模型、迁移、控制器等添加了增强的自动完成和代码生成。
* [Symfony Plugin](https://plugins.jetbrains.com/plugin/7219-symfony-support)
    * 添加对 Symfony 框架的支持。
* [Yii2 Framework Support](https://plugins.jetbrains.com/plugin/23693-yii2-framework-support)
    * 添加对 Yii2 框架的支持。
* [Magento PhpStorm](https://plugins.jetbrains.com/plugin/8024-magento-phpstorm)
    * 免费插件，扩展了对 Magento 2 的支持。
* [Magento and Adobe Commerce PhpStorm by Atwix](https://plugins.jetbrains.com/plugin/20554-magento-and-adobe-commerce-phpstorm-by-atwix)
    * 免费增值插件，它通过检查和改进的导航扩展了对 Magento 2 的支持。

### C/C++

* [EzArgs](https://plugins.jetbrains.com/plugin/16411-ezargs)
    * 提供将参数传递给 C++ 运行配置的选项，只需将参数写入工具栏上的下拉框中即可。
* [Bazel for CLion](https://plugins.jetbrains.com/plugin/9554-bazel-for-clion)
    * JetBrains 插件（前身为 Google 开发）添加对 Bazel 构建的支持。
* [CMake Plus](https://plugins.jetbrains.com/plugin/12869-cmake-plus)
    * 扩展 CMake 语言支持（高亮显示、代码导航、检查等）。
### Rust

* [RON Extended Support for Rust Rover](https://plugins.jetbrains.com/plugin/26307-ron-extended-support-for-rust-rover)
    * 添加对 Rusty Object Notation 文件（代码完成、语法高亮等）的支持。
* [RustJson](https://plugins.jetbrains.com/plugin/22393-rustjson)
    * 将 JSON 转换为 Rust 结构体。
    * 很长时间没有更新，但仍可在 IDE 中运行。

### Go

所有有价值的 Go 插件现在都由 JetBrains 开发并捆绑到 IDE 中。

## AI/LLM 集成

* [JetBrains AI Assistant](https://plugins.jetbrains.com/plugin/22282-ai-assistant)
    * Jetbrains 原生 AI 集成。免费层提供无限代码补全和本地模型支持。支持通过 OpenAI 兼容 API（Ollama、LM Studio 等）使用自己的 LLM。
* [Junie](https://plugins.jetbrains.com/plugin/26104-junie-the-ai-coding-agent-by-jetbrains)
    * JetBrains AI 编码代理，可自主处理任务 - 编写代码、运行测试、修复错误并迭代结果。
* [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot--your-ai-pair-programmer)
    * 启用 GitHub Copilot 与 IDE 的集成。支持代码补全、聊天、代码审查和代理模式。
* [Claude Code](https://plugins.jetbrains.com/plugin/27310-claude-code-beta-)
    * 将 Claude Code AI 助手集成到 IDE 中。需要单独安装 Claude Code CLI。
* [Gemini Code Assist](https://plugins.jetbrains.com/plugin/24198-gemini-code-assist)
    * Google 基于 Gemini 模型的 AI 编码助手。提供代码补全、生成和智能操作。免费使用。
* [Amazon Q](https://plugins.jetbrains.com/plugin/24267-amazon-q/)
    * Amazon 的 AI 编码助手（前身为 CodeWhisperer）。提供代码补全、聊天和安全扫描。
* [Lingma](https://plugins.jetbrains.com/plugin/17809-lingma--alibaba-cloud-ai-coding-assistant)
    * 阿里云 AI 编码助手。提供代码补全、多文件编辑和聊天功能。
* [Explyt](https://plugins.jetbrains.com/plugin/27979-explyt-ai-agent)
    * 面向 JetBrains IDE 的 AI 代理。使用调试器、重构、符号导航和静态分析等 IDE 工具。

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
* [YourProgressBar](https://plugins.jetbrains.com/plugin/21417-yourprogressbar)
    * 将进度条替换为自定义图像。
* [Anime Memes](https://plugins.jetbrains.com/plugin/15865-anime-memes)
* [Space Invaders](https://plugins.jetbrains.com/plugin/19383-space-invaders)
* [Pets](https://plugins.jetbrains.com/plugin/21008-pets)