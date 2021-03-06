# DotNet 资源大全中文版 

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-dotnet](https://github.com/quozd/awesome-dotnet) 是由 quozd 发起和维护。内容包括：编译器、压缩、应用框架、应用模板、加密、数据库、反编译、IDE、日志、风格指南等。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

* * *

### 我们要做什么？

- 基于 awesome-dotnet 列表，我们将对其中的各个资源项进行编译整理。此外还将从其他来源补充好资源。
- 整理后的内容，将收录在[伯乐在线资源频道](http://hao.jobbole.com/)。可参考已整理的内容：
  - 《[Scrapy：Python的爬虫框架](http://hao.jobbole.com/python-scrapy/)》
  - 《[Flask：一个使用Python编写的轻量级Web应用框架](http://hao.jobbole.com/flask/)》

* * *

### 如何参与本项目？

从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 在用 DotNet；

如有兴趣，请加 QQ：50872495。加 Q 时请注明「DotNet大全」

* * *

### 本项目的参与者

- 维护者：
- 贡献者：[Erucy](http://www.jobbole.com/members/Erucy)、你

注：名单不分排名，不定期补充更新

### 最新活动

* **贡献打赏：**整理 20 个资源以上的朋友会开通打赏功能，参见[Dropwizard](http://hao.jobbole.com/dropwizard/)结尾打赏信息。
* **整理技术资源，赠送经典书籍**： 每整理 20 个资源，赠送技术书籍一本。[活动详情](http://group.jobbole.com/13769/)

* * *

（注：下面用 [$] 标注的表示收费工具，但部分收费工具针对开源软件的开发/部署/托管是免费的）

## API

*   框架
    *   [NancyFx](https://github.com/NancyFx/Nancy)：轻量、用于构建 HTTP 基础服务的非正式（low-ceremony）框架，基于.Net 及 Mono 平台。
    *   [ASP.NET WebAPI](http://www.asp.net/web-api/)：快捷创建 HTTP 服务的框架，可以广泛用于多种不同的客户端，包括浏览器和移动设备。
    *   [ServiceStack](https://github.com/ServiceStack/ServiceStack) ：架构缜密、速度飞快、令人愉悦的 web 服务。
    *   [Nelibur](https://github.com/Nelibur/Nelibur)：Nelibur 是一个使用纯 WCF 构建的基于消息的 web 服务框架。Nelibur 可以便捷地创建高性能、基于消息的 web 服务，使得你全面拥有 WCF 的强大能力。
*   [WebAPI Contrib](https://github.com/WebApiContrib/WebAPIContrib)：帮助你提高 ASP.NET Web API 能力的开源项目集合。

## 应用框架（Application Frameworks）

*   [ASP.NET Boilerplate](https://github.com/aspnetboilerplate/aspnetboilerplate)：现代 ASP.NET MVC web 应用程序的入门，包含最佳实践和最流行的工具。
*   [Orleans](https://github.com/dotnet/orleans)：Orleans 框架提供了直接构建分布式、大规模计算应用的方法，无需学习和使用复杂的并行或扩展模型。
*   [CoreFX](https://github.com/dotnet/corefx)：corefx 仓库包含了 .NET 核心功能库的实现（被称为“CoreFX”）。包含了 System.Collections、System.IO、System.Xml 以及诸多其它组件。目前构建并运行于 Windows 平台。你可以关注这个仓库，了解在未来的几个月内即将增加的对 Linux 和 Mac 的支持。
*   [CSLA .NET](https://github.com/MarimerLLC/csla)：业务层开发框架 [http://www.cslanet.com](http://www.cslanet.com)。
*   [Mono](https://github.com/mono/mono)：Mono 是 ECMA CLI、C# 以及 .NET 的开源实现。
*   [Mono-Addins](https://github.com/mono/mono-addins)：Mono.Addins 是一个通用框架，用于创建可扩展的应用程序<del><span style="color: #ff0000;">，</del>以及这些应用程序的扩展插件。
*   [Spring.Net](https://github.com/spring-projects/spring-net)：Spring.NET 是一个开源的应用程序框架，可以便捷地创建企业级 .NET 项目。

## 应用模板（Application Templates）

*   [MVC.Template](https://github.com/NonFactors/MVC.Template)：ASP.NET MVC 5 入门项目模板。
*   [ProjectScaffold](https://github.com/fsprojects/ProjectScaffold)：F# 基金会推荐的 .NET 解决方案的原型——包括文件系统的搭建、用于管理依赖的 Paket 以及用于自动化构建、测试的 FAKE。默认情况下，构建流程也会对文档进行编译，并生成 NuGet 程序包。
*   [Side-Waffle](https://github.com/LigerShark/side-waffle) ：包含大量有用的 Web 和桌面开发模板。
*   [Template10](https://github.com/Windows-XAML/Template10) ：带有设计模式的 Windows 10 模板。

## 人工智能（Artificial Intelligence）

*   [AIMLBot（Program#）](http://aimlbot.sourceforge.net/)：使用 C# 编写的一个小型、快速、兼容标准、易于定制的聊天机器人，基于 AIML （人工智能标记语言 Artificial Intelligence Markup Language）。
*   [SIML](http://simlbot.com/) ：智能综合智能标记语言（Synthetic Intelligence Markup Language），下一代聊天机器人及数字助手语言。

## 程序集处理（Assembly Manipulation）

*   [dnSpy](https://github.com/0xd4d/dnSpy)：dnSpy 是一个 .NET 程序集编辑器、反编译器和调试器，来自 ILSpy 分支。
*   [Fody](https://github.com/Fody/Fody)：织入（weaving）.net 程序集的可扩展工具。
*   [Mono.Cecil](https://github.com/jbevain/cecil)：Cecil 类库用于生成和检查 ECMA CIL 程序和库。

## 资源（Assets）

*   [Cassette](https://github.com/andrewdavey/cassette)：管理 .NET web 应用程序资源（脚本、css 和 模板）
*   [NodeAssets](https://github.com/ajorkowski/NodeAssets)：.net 资源管理器，通过 SignalR 实时更新 css，也可以使用 NodeJS 编译器。
*   [Bundler](https://github.com/ServiceStack/Bundler)：编译和最小化 Less、Sass、Stylus、Css、JS、CoffeeScript、LiveScript 文件。MVC集成了 MVC 和 ServiceStack。
*   [SquishIt](https://github.com/jetheredge/SquishIt)：让你**轻松**合并一些 css 和 javascript。

## 认证和授权（Authentication and Authorization）

*   [ASP.NET Identity](https://aspnetidentity.codeplex.com/)：用于 ASP.NET 应用程序的新身份系统。
*   [DotNetOpenAuth](https://github.com/DotNetOpenAuth/DotNetOpenAuth)：OpenID、OAuth 和 InfoCard 协议的一个 C# 实现。
*   [Logibit Hawk](https://github.com/logibit/logibit.hawk/)：一个 F# [Hawk](https://github.com/hueniverse/hawk#usage-example) 认证库。
*   [IdentityModel](https://github.com/IdentityModel)：.NET 4.5 和 MVC4、Web API 身份和访问控制的辅助库。
*   [IdentityServer](https://github.com/IdentityServer)：可扩展的 OAuth2 和 OpenID 连接提供程序框架。
*   [OAuth](https://github.com/danielcrenna/oauth)：超轻量级 OAuth 1.0a 签名生成库，C# 编写。

## 自动构建（Build Automation）

*   [Psake](https://github.com/psake/psake)：基于 .NET 的自动化构建工具，使用 PowerShell 编写。
*   [FAKE](https://github.com/fsharp/FAKE)：F# Make，一个跨平台自动构建系统。
*   [Invoke-Build](https://github.com/nightroman/Invoke-Build)：PowerShell 自动构建和测试工具，灵感来自 Psake。
*   [MSBuild](https://github.com/Microsoft/msbuild)：微软构建引擎（MSBuild）是 .NET 和 Visual Studio 的构建平台。
*   [Cake](https://github.com/cake-build/cake)：Cake（C# Make）使用 C# DSL 的跨平台自动构建系统。

## 缓存（Caching）

*   [CacheCow](https://github.com/aliostad/CacheCow)：ASP.NET Web API HTTP 客户端和服务器端缓存实现。
*   [Akavache](https://github.com/akavache/Akavache)：一个异步、持久化的键值存储。

## CLI

*   [Command Line Parser](https://github.com/gsscoder/commandline)：Command Line Parser 类库为 CLR 应用程序提供了一套简洁的 API，用于处理命令行参数及相关任务。
*   [Fluent Command Line Parser](https://github.com/fclp/fluent-command-line-parser)：一个简单、强类型的 .NET C# 命令行解析库，交互方式流畅易用。
*   [Power Args](https://github.com/adamabdelhamed/PowerArgs)：PowerArgs 将命令行参数转换为 .NET 对象，便于程序使用。它还提供了大量可选的扩展，例如参数校验、自动生成使用帮助、tab 补全等等。
*   [UnionArgParser](https://github.com/nessos/UnionArgParser)：针对 F# 应用程序的声明式 CLI 参数和 XML 配置解析器。

## CLR

*   [CoreCLR](https://github.com/dotnet/coreclr)：coreclr repo 包含了完整的 .NET 核心运行时实现（称为“CoreCLR”）。它包括 RyuJIT、.NET GC、非托管代码交互（native interop）等诸多组件。它目前构建和运行于 Windows 平台。你可以关注这个仓库，了解未来的几个月内即将增加的对 Linux 和 Mac 的支持。

## CMS

*   [Composite C1](https://compositec1.codeplex.com/)：一个 web 内容管理系统，着重在用户体验及适应性。
*   [mojoPortal](https://mojoportal.codeplex.com/)：MojoPortal 是一个可扩展、跨数据库、移动友好的 web 内容管理系统（CMS）和 web 应用程序框架，使用 C# ASP.NET 编写。
*   [N2CMS](http://www.n2cms.com/)：开源、轻量、代码优先的 CMS，可以无缝地集成到任何 MVC 项目中。
*   [Orchard](https://github.com/OrchardCMS/Orchard)：免费、开源、专注社区的项目，目标是在 ASP.NET 平台上提供应用程序和可重用组件。
*   [Piranha CMS](https://github.com/PiranhaCMS/Piranha)：Piranha 是一个有趣、快速、轻量级的 .NET 框架，用于开发基于 cms 附带其它功能的 web 应用程序。它基于 ASP.NET MVC 和 Web 页面创建，完全兼容 Visual Studio 和 WebMatrix。[http://piranhacms.org](http://piranhacms.org)
*   [Umbraco](https://github.com/umbraco/Umbraco-CMS)：Umbraco 是一个免费开源的内容管理系统，基于 ASP.NET 平台构建

## 代码分析和度量（Code Analysis and Metrics）

*   [CodeMaid](http://www.codemaid.net/)：Visual studio 扩展，用于清理、挖掘和简化 C#、C++、F#、VB、PHP、JSON、XAML、XML、ASP、HTML、CSS、LESS、SCSS、JavaScript 和 TypeScript 代码。
*   [StyleCop](https://stylecop.codeplex.com/)：StyleCop 使用一组风格和一致性规则，对 C# 源代码进行分析和强制性检查。
*   [Gendarme](https://github.com/spouliot/gendarme)：可扩展的、基于规则的工具，用于在 .NET 应用程序和类库中查找问题。
*   [Metrics-Net](https://github.com/danielcrenna/metrics-net)：捕获 CLR 和应用程序级别的度量值。所以你知道它的功能。

## 编译器（Compiler）

*   [Bridge.NET](https://github.com/bridgedotnet/Bridge)：将 C# 编译成 JavaScript 的开源编译器 [http://bridge.net/](http://bridge.net/)。
*   [ClojureCLR](https://github.com/clojure/clojure-clr)：从 Clojure 到 CLR 的转换，是 Clojure 项目的一部分。
*   [F#](https://github.com/fsharp/fsharp/)：F# 编译器、核心库和工具——更安全、更快、代码更好的函数式编程语言。
*   [FunScript](http://funscript.info/)：F# 到 JavaScript 的编译器，可以通过 TypeScript 类型提供程序使用 JQuery 等 JavaScript 库。
*   [JSIL](https://github.com/sq/JSIL)：CIL 到 Javascript 的编译器 [http://jsil.org/](http://jsil.org/)。
*   [Mono-basic](https://github.com/mono/mono-basic)：Visual Basic 编译器和运行时。
*   [Nemerle](https://github.com/rsdn/nemerle)：Nemerle 是一个 .NET 平台高级静态类型编程语言。它提供函数式、面向对象式和命令式编程语言的特性。它拥有一个简单的类似 C# 的语法和强大的元编程（meta-programming）系统。 [http://nemerle.org](http://nemerle.org)
*   [Netjs](https://github.com/praeclarum/Netjs)：.NET 到 TypeScript 和 JavaScript 编译器。兼容可移植类库。你甚至可以使用 EXE 文件。
*   [Roslyn](https://github.com/dotnet/roslyn)：.NET 编译平台（“Roslyn”）提供开源的 C# 和 Visual Basic 编译器，包含丰富的代码分析 API。它可以使用和 Visual Studio 一样的 API 来构建代码分析工具。
*   [VisualFSharp](https://github.com/Microsoft/visualfsharp)：Visual F# 编译器和工具。

## 压缩（Compression）

*   [SharpCompress](https://github.com/adamhathcock/sharpcompress)：SharpCompress 是一个用于 .NET、Mono、Silverlight、WP7 的压缩类库，可以解压rar、7zip、zip、tar、bzip2 和 gzip，提供单向读取和随机文件访问 API。支持对 zip/tar/bzip2/gzip 进行写入的实现。
*   [DotNetZip.Semverd](https://github.com/haf/DotNetZip.Semverd)：一个开源项目，提供对 ZIP 文件处理的 .NET 类库和相关工具。 （分支自 [**已经不再维护的** DotNetZip](http://dotnetzip.codeplex.com)）
*   [SharpZipLib](http://icsharpcode.github.io/SharpZipLib/)：一个 Zip、GZip、Tar 和 BZip2 的类库，完全由 C# 编写，面向 .NET 平台。

## 持续集成（Continuous Integration）

*   [TeamCity](http://www.jetbrains.com/teamcity/)：可以直接使用的，可扩展、面向开发人员友好的构建服务器——开箱即用**。** **[$]**
*   [CruiseControl.NET](http://www.cruisecontrolnet.org/)：一个自动化持续集成服务器，使用 .NET Framework 实现。
*   [MyGet](http://www.myget.org/)：为NuGet、NPM、Bower 和 VSIX 提供持续集成、部署、宿主程序包仓库的服务。**[[开源软件免费](https://www.myget.org/opensource)]** **[$]**
*   [AppVeyor](http://www.appveyor.com/)：.NET 持续构建和部署服务。 **[$]** **[开源软件免费]**

## 加密（Cryptography）

*   [BouncyCastle](https://bouncycastle.org/)：和 .Net 的 System.Security.Cryptography 一起，在 CLR 上提供加密算法的实现。
*   [HashLib](http://hashlib.codeplex.com/)：HashLib 包含了几乎所有你见过的哈希算法，它几乎支持所有东西并且非常容易使用。
*   [libsodium-net](https://github.com/adamcaudill/libsodium-net)：libsodium for .NET——一个安全加密库。
*   [StreamCryptor](https://github.com/bitbeans/StreamCryptor) ：使用 libsodium 和 protobuf 对流进行加密和解密。

## 数据库（Database）

*   [BrightstarDb](https://github.com/BrightstarDB/BrightstarDB)：BrightstarDB 是一个原生的 .NET RDF 三元组数据库（triple store）。
*   [Event Store](https://github.com/EventStore/EventStore) ：开源的功能性数据库，支持使用 JavaScript 进行复杂事件处理。 [https://geteventstore.com](https://geteventstore.com)
*   [LiteDB](https://github.com/mbdavid/LiteDB)：一个 .NET 的 NoSQL 单文件文档数据库。[http://www.litedb.org](https://geteventstore.com)
*   [RavenDB](https://github.com/ravendb/ravendb)：支持 linq 的 .NET 文档数据库。

## 数据库驱动（Database Drivers）

*   [MySQL Connector](https://dev.mysql.com/downloads/connector/net/)：完全托管的 MySQL ADO.NET 数据库提供程序、连接器。
*   [Npgsql](https://github.com/npgsql/Npgsql)：Postgresql 的 .Net 数据提供程序。
*   [MongoDB](https://github.com/mongodb/mongo-csharp-driver)：MongoDB 官方 C# 驱动。
*   [ServiceStack Redis](https://github.com/ServiceStack/ServiceStack.Redis)：.NET 领先的 C# Redis 客户端。
*   [StackExchange Redis](https://github.com/StackExchange/StackExchange.Redis)：来自 StackExchange 的通用 redis 客户端。
*   [Cassandra](https://github.com/datastax/csharp-driver)：DataStax 开发的 Apache Cassandra .NET 驱动程序。
*   [Couchbase](https://github.com/couchbase/couchbase-net-client)：couchbase 官方 .NET 客户端库，基于 Enyim memcached 客户端。
*   [Firebird.NET](http://sourceforge.net/projects/firebird/)：由C# 编写的 .NET 数据提供程序，提供对 Firebird API 的高性能原生实现。

## 反编译（Decompilation）

*   [ILSpy](http://ilspy.net/)：ILSpy 是一个开源的 .NET 程序集查看器和反编译器。
*   [JustDecompile Engine](https://github.com/telerik/JustDecompileEngine)：[JustDecompile](http://www.telerik.com/products/decompiler.aspx) 反编译引擎。

## 部署（Deployment）

*   [Unfold](https://github.com/thomasvm/unfold)：基于 Powershell 的 .net web 应用程序部署解决方案。

## DirectX

*   [SlimDX](http://www.slimdx.org)：为 .NET 应用程序提供的 DirectX 封装。
*   [SharpDX](https://github.com/sharpdx/SharpDX)：SharpDX 是一个开源项目，为 .Net 及所有 Windows 平台提供完整的 DirectX API，可以开发高性能的游戏、2D/3D图形渲染以及实时音频应用程序。

## 分布式计算（Distributed Computing）

*   [Project Orleans](https://github.com/dotnet/orleans)：Orleans 框架提供了直接构建分布式、大规模计算应用的方法，无需学习和使用复杂的并行或扩展模型。由微软研究院开发。
*   [Akka.net](https://github.com/akkadotnet/akka.net)：Akka.NET 是流行的 Java/Scala 框架 Akka 的 .NET 版本。它由社区提供，与 Typesafe（原始的 Java、Scala 版本的开发商）无关。

## 文档（Documentation）

*   [Sandcastle](http://shfb.codeplex.com/)：Sandcastle 帮助文件生成器和 NDoc 类似。
*   [SharpDox](https://github.com/Geaz/sharpDox)：一个 c# 文档工具。
*   [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle)：向 WebApi 项目无缝地添加 swagger 文档（译者注：swagger 是一套用于生成、描述、展现 RESTful 风格 web 服务文档的框架和规范）。
*   [F# Formatting](http://tpetricek.github.io/FSharp.Formatting/)：F# 和 C# 项目的文档工具，文档生成自 F# 脚本文件、Markdown 文档、内嵌 XML 或 Markdown评论。

## 电子商务和支付（E-Commerce and Payments）

*   [Paypal Merchant SDK](https://github.com/paypal/merchant-sdk-dotnet) ：Paypal Merchant官方.NET SDK。
*   [NopCommerce](https://nopcommerce.codeplex.com/)：nopCommerce。开源的电子商务购物车（ASP.NET MVC）。
*   [ServiceStack.Stripe](https://github.com/ServiceStack/Stripe)：针对 stripe.com REST API 的强类型 .NET 客户端。
*   [SmartStoreNET](https://github.com/smartstoreag/SmartStoreNET)：免费 ASP.NET MVC 电子商务购物车解决方案。[http://www.smartstore.com/net/en](http://www.smartstore.com/net/en)
*   [Stripe.Net](https://github.com/jaymedavis/stripe.net)：Stripe.net 是针对 [http://stripe.com](http://stripe.com) 完整服务的 .net api。
*   [BeYourMarket](https://github.com/beyourmarket/beyourmarket) ：BeYourMarket 是一个点对点的市场框架。[http://beyourmarket.com](http://beyourmarket.com)
*   [Virto Commerce](https://github.com/VirtoCommerce/vc-community)：Virto Commerce 是第二个版本，也是唯一的开源许可下的企业级别电子商务产品。Virto Commerce 基于 .NET 4.5，使用了 MVC、IoC、EF、Azure、Angular JS 等其他先进技术。它可以在微软的云平台（Azure）、亚马逊云服务（AWS）和企业内部部署。[http://virtocommerce.com](http://virtocommerce.com)

## 环境管理（Environment Management）

*   [DNVM](https://github.com/aspnet/dnvm)：.NET SDK 管理器，一组命令行工具，用于更新和配置需要使用的运行时环境（DNX）。

## ETL

*   [Reactive ETL](https://reactiveetl.codeplex.com/)：Reactive ETL 使用 .NET 反应性扩展框架（reactive extensions） 重写了 Rhino ETL。

## 游戏（Game）

*   [MonoGame](https://github.com/mono/MonoGame)：一个用来创建跨平台游戏的强大框架。
*   [CocosSharp](https://github.com/mono/CocosSharp)：CocosSharp 是 Cocos2D 和 Cocos3D API 的 C# 实现版本，可以在所有支持 MonoGame 的平台上运行。
*   [Duality](https://github.com/AdamsLair/duality)：Duality 是一个 2D 游戏开发框架。专注于功能的模块化，自带一个可视化编辑器。
*   [Paradox](https://github.com/SiliconStudio/paradox)：Paradox 游戏引擎。[http://paradox3d.net](http://paradox3d.net)

## 地理信息系统（Gis）

*   [NetTopologySuite](https://github.com/NetTopologySuite/NetTopologySuite/)：一个 在 .NET 平台上实现快速、可靠的 GIS 系统解决方案。
*   [SharpMap](https://sharpmap.codeplex.com/)：一个易于使用的地图库，可以用于 web 和桌面应用程序。

## Git工具（Git Tools）

*   [Bonobo Git Server](https://github.com/jakubgarfield/Bonobo-Git-Server)：Bonobo Git Server for Windows 是一个 web 应用程序，可以安装在你自己的 IIS 上，用于管理和连接你的 git 仓库。 [http://bonobogitserver.com](http://bonobogitserver.com)
*   [GitExtensions](https://github.com/gitextensions/gitextensions)：GitExtensions 包含资源管理器扩展、Visual Studio 2008/2010/2012/2013 插件和一个独立的 Git 仓库工具。 [http://gitextensions.github.io/](http://gitextensions.github.io/)
*   [GitLink](https://github.com/CatenaLogic/GitLink)：让用户可以单步调试托管在 GitHub 或 BitBucket 上的代码。
*   [GitVersion](https://github.com/Particular/GitVersion)：根据你的 Git 仓库的状态生成一个语义化版本号（Semantic Version Number）。
*   [LibGit2Sharp](https://github.com/libgit2/libgit2sharp)：LibGit2Sharp 带来了 libgit2 所有的功能和速度，是一个本地 Git 实现，可以运行在 .Net 和 Mono 平台。
*   [NGit](https://github.com/mono/ngit)：NGit 是 JGit 移植到 C# 的版本。
*   [posh-git](https://github.com/dahlbyk/posh-git)：Git 的 PowerShell 环境。

## 图形（Graphics）

*   [Oxyplot](https://github.com/oxyplot/)：OxyPlot 是一个 .NET 跨平台绘图库。
*   [OpenTK](http://www.opentk.com/)：Open Toolkit 是一个封装了 OpenGL、OpenCL 和 OpenAL 的 高级底层 C# 开发库。
*   [NGraphics](https://github.com/praeclarum/NGraphics)：NGraphics 是一个 .NET 跨平台矢量图形渲染库。

## GUI

*   [MahApps.Metro](https://github.com/MahApps/MahApps.Metro)：用于创建 Metro 风格 WPF 应用的工具箱。
*   [Callisto](https://github.com/timheuer/callisto)：用于 Windows 8 XAML 应用的控件工具箱。包含若干 UI 控件，让你更容易地创建符合 Windows UI 风格规范的Windows 商店应用。
*   [ObjectListView](http://objectlistview.sourceforge.net/cs/index.html)：ObjectListView 使用 C# 封装了 .NET 的 ListView 控件。它使得 ListView 更加易用，并且加入了一些新特性。
*   [DockPanelSuite](http://dockpanelsuite.com/) ：灵感来自 Visual Studio 的停靠窗口（docking）类库，用于 .NET WinForm 应用。
*   [AvalonEdit](https://github.com/icsharpcode/AvalonEdit) ：在 SharpDevelop 中使用，基于 WPF 的文本编辑器组件。
*   [XWT](https://github.com/mono/xwt)：跨平台 UI 工具箱，用于创建 .NET 和 Mono 桌面应用程序。
*   [Gtk#](https://github.com/mono/gtk-sharp)：Gtk# 是 Gtk+ GUI 工具箱的 Mono/.NET 版本，绝大多数 Mono 中的 GUI 应用都基于它构建。
*   [MaterialDesignInXamlToolkit](https://github.com/ButchersBoy/MaterialDesignInXamlToolkit)：用于创建 Material Design 风格 WPF 应用的工具箱。
*   [Eto.Forms](https://github.com/picoe/Eto)：跨平台的 GUI 框架，用于 .NET 和 Mono 下的桌面和移动应用程序。
*   [Dragablz](https://github.com/ButchersBoy/Dragablz)：可拖拽、可分离（tearable，译者注：即拖拽标签页成为独立窗口）的 WPF 标签页控件（类似 Chrome）。支持布局和主题，包含兼容 MahApps 和 Material Design 的主题。
*   [Fluent.Ribbon](https://github.com/fluentribbon/Fluent.Ribbon)：Fluent Ribbon Control Suite 是一个在 WPF 中实现 Office 和 Windows 8 风格的 Ribbon 库。

## HTML 和 CSS（HTML and CSS）

*   [AngleSharp](https://github.com/FlorianRappl/AngleSharp)：支持构建完整的 HTML5 DOM 和 CSS3 模型。
*   [CsQuery](https://github.com/jamietre/CsQuery)：jQuery 风格的HTML5 解析器，可与 DOM 交互。
*   [dotless](https://github.com/dotless/dotless)：ruby Less CSS 库的 .NET 移植版本。[http://www.dotlesscss.org](http://www.dotlesscss.org)
*   [ExCSS](https://github.com/TylerBrinks/ExCSS)：C# 的 CSS3 解析器开发库。
*   [FluentBootstrap](http://fluentbootstrap.com)：让ASP.NET MVC 和 WebPages 更容易使用 Boostrap CSS 框架。
*   [HtmlAgilityPack](http://htmlagilitypack.codeplex.com/)：一个灵活的 HTML 解析器，可以对 DOM 进行读写，支持 XPATH 和 XSLT。

## HTTP

*   [Http.fs](https://github.com/relentless/Http.fs)：`[F#]` 中的一个函数式 HTTP 客户端。
*   [RestSharp](https://github.com/restsharp/RestSharp)：.NET 下简单的 REST 和 HTTP API 协议客户端。
*   [EasyHttp](https://github.com/hhariri/EasyHttp)：C# Http开发库。
*   [Refit](https://github.com/paulcbetts/refit) ：Xamarin 和 .NET 下自动生成强类型的 REST 库。
*   [RestEase](https://github.com/canton7/RestEase)：类型安全且易于使用的 REST API 客户端库，简单可定制。大部分灵感来自 Refit。

## IDE

*   [SharpDevelop](https://github.com/icsharpcode/SharpDevelop)：用于 .NET 编程语言的免费 IDE。
*   [MonoDevelop](https://github.com/mono/monodevelop)：MonoDevelop 是一个跨平台的 IDE，主要面向 Mono/.NET 开发者。
*   [Visual Studio Express](http://www.visualstudio.com/en-us/products/visual-studio-express-vs.aspx)：用于 .NET 开发的免费、轻量版本的 Visual Studio。
*   [Visual Studio Community](http://msdn.microsoft.com/en-us/visual-studio-community-vs.aspx)：功能完整的免费 IDE。
*   [Waf DotNetPad](http://dotnetpad.codeplex.com) ：简单快速的代码编辑器，让开发 C# 或 Visual Basic 充满乐趣。
*   [Visual Studio Code](https://code.visualstudio.com/)：非常棒的编辑器，来自微软，基于 GitHub Atom。

## 图像处理（Image Processing）

*   [ImageResizer](http://imageresizing.net/)：在图片 URL 后面增加命令，在几毫秒内获取修改后的版本，支持实时的对图片进行缩放、编辑。
*   [ImageProcessor](http://imageprocessor.org/)：开源 .NET 库，用于实时处理图片。
*   [DynamicImage](http://dynamicimage.apphb.com/)：高性能开源图片处理库，用于 ASP.NET。
*   [MetadataExtractor](https://github.com/drewnoakes/metadata-extractor-dotnet)：从图片中提取 Exif、IPTC、XMP、ICC 等其它元数据信息。
*   [Emgu CV](http://www.emgu.com/wiki/index.php/Main_Page)：OpenCV 的 .NET 跨平台封装。

## 安装工具（Install Tools）

*   [Wix Toolset](http://wixtoolset.org/)：强大的工具集，用于创建你自己的 Windows 安装程序。
*   [Squirrel](https://github.com/squirrel/squirrel.windows)：Squirrel 即是一套工具也是一个类库，可以无安全管理 Windows 桌面程序的安装和更新。

## 国际化（Internationalization）

*   [i18n](https://github.com/turquoiseowl/i18n)：ASP.NET MVC 智能国际化工具。

## 互操作（Interoperability）

*   [CefSharp](https://github.com/cefsharp/CefSharp)：Chromium Embedded Framework 的 .NET 支持（WPF 和 WinForm）。
*   [CppSharp](https://github.com/mono/CppSharp)：在 C# 中平滑使用 C++ API 的工具。
*   [Sharpen](https://github.com/mono/sharpen)：Sharpen 是 db4o 编写的 Eclipse 插件，可以让你把 Java 项目转换为 C#。
*   [CXXI](https://github.com/mono/cxxi)：C++ 互操作框架。

## IoC

*   [Castle Windsor](https://github.com/castleproject/Windsor)：Castle Windsor 是一个用于 .NET 和 Silverlight 的成熟的 控制反转（IoC） 容器。
*   [Unity](https://unity.codeplex.com/)：轻量级、可扩展的依赖注入容器，支持构造函数、属性和方法调用注入。
*   [Autofac](https://github.com/autofac/Autofac)：令人着迷的 .NET IoC 容器。
*   [Ninject](https://github.com/ninject/ninject)：.net 依赖注入的忍者。
*   [StructureMap](https://structuremap.github.io/)：.Net 最早的 IoC/ID 容器。
*   [Spring.Net](https://github.com/spring-projects/spring-net)：Spring.NET 是一个开源应用程序框架，可以便捷地创建企业级 .NET 应用。
*   [LightInject](https://github.com/seesharper/LightInject) ：一个超轻量级 IoC 容器。
*   [TinyIoC](https://github.com/grumpydev/TinyIoC)：单文件、简单、跨平台的 IoC 容器。

## 日志（Logging）

*   [Essential Diagnostics](http://essentialdiagnostics.codeplex.com/)：为内置System.Diagnostics 命名空间扩展功能，提供更灵活的日志功能。
*   [NLog](https://github.com/nlog/NLog/)：先进的 .NET 和 Silverlight 日志工具。
*   [ELMAH](https://code.google.com/p/elmah/)：ELMAH 官方网站。
*   [Elmah MVC](https://github.com/alexanderbeletsky/elmah-mvc)：MVC 版 Elmah。
*   [Logary](http://logary.github.io/)：Logary 是一个 mono 和 .Net 平台下高性能、多目标的日志、度量、追踪和健康检查库。支持多目标，为微服务构建。
*   [Log4Net](https://logging.apache.org/log4net/)：Apache log4net 工具库能够帮助程序员向多种不同的目标输出日志语句。
*   [Serilog](https://github.com/serilog/serilog)：一个 NoSQL 时代下简单直接的日志库。将多个优秀的传统结构化分析日志功能合并到一个易于使用的程序集中。
*   [StackExchange.Exceptional](https://github.com/NickCraver/StackExchange.Exceptional)：Stack Exchange 网络使用的错误处理程序。
*   [Semantic Logging Application Block (SLAB)](http://slab.codeplex.com/)：为内置 System.Diagnostics.Tracing 命名空间（EventSource类）扩展功能，支持将日志记录到多个容器中，包括 Azure 表存储、数据库、文件（JSON、XML、文本文件）。通过 ETW 支持进程内和进程外的日志记录，支持 Rx 进行实时的事件过滤和聚合。

## 机器学习和数据科学（Machine Learning and Data Science）

*   [Accord.NET](http://accord-framework.net/)：机器学习框架，包含了音频和图像处理的库（计算机视觉、计算机听觉、信号处理和统计）。
*   [Accord.NET Extensions](https://github.com/dajuric/accord-net-extensions)：高级图像处理和计算机视觉算法扩展。
*   [AForge.NET](http://www.aforgenet.com/)：为计算机视觉和人工智能领域的开发者和研究人员提供的框架（包括图像处理、神经网络、遗传算法、机器学习、机器人科学）。
*   [Deedle](http://bluemountaincapital.github.io/Deedle/)：处理探索性数据的数据帧和时序库，支持 C# 和 F#。
*   [FsLab](http://www.fslab.org)：数据科学和机器学习库的集合，支持 F# 和 .NET。
*   [numl](https://github.com/sethjuarez/numl) ：包含最流行的监督学习和无监督学习算法，尽量减少创建预测模型时的冲突。
*   [R Provider](http://bluemountaincapital.github.io/FSharpRProvider/) ：将 R 语言包和函数封装为类型安全的类型提供程序供 F# 调用。
*   [F# Data](http://fsharp.github.io/FSharp.Data/)：F# 类型提供程序，访问 XML、JSON、CSV 和 HTML 文件（基于样例文档），以及 WorldBank 数据。

## Markdown 处理（Markdown Processors）

*   [MarkdownSharp](https://code.google.com/p/markdownsharp/)：C# 实现的开源 Markdown 处理器，在 Stack Overflow 中使用。
*   [F# Formatting](http://tpetricek.github.io/FSharp.Formatting/)：用于生成 F# 和 C# 项目文档的工具。该工具库的核心组件中包含了可扩展的 Markdown 解析器。
*   [CommonMark.NET](https://github.com/Knagis/CommonMark.NET)：CommonMark 规范的 C# 实现，用于将 Markdown 文档转换为 HTML。为最佳性能和可移植性进行了优化。

## 邮件（Mail）

*   [FluentEmail](https://github.com/lukencode/FluentEmail)：System.Net.Mail 的一个流式（Fluent）封装，支持 razor 模板引擎。
*   [MailKit](https://github.com/jstedfast/MailKit)：完整的跨平台的邮件协议栈，包括 IMAP、POP3、SMTP，支持验证等特性。基于 MimeKit 构建。
*   [MimeKit](https://github.com/jstedfast/MimeKit)：跨平台 .NET MIME 创建和解析库，支持 S/MIME、PGP、TNEF 和 Unix mbox spools。
*   [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net)：一个 C# 开发库，将你的样式表嵌入到内置的 style 属性中，最大限度支持邮件客户端。

## 数学（Mathematics）

*   [MathNet](http://www.mathdotnet.com/)：Math.NET 是一个开源项目，旨在创建和维护涵盖基础数学在内的工具集，面向高级和日常需要使用此类功能的 .Net 开发人员。

## 多媒体（Media）

*   [TagLib#](https://github.com/mono/taglib-sharp)：TagLib#（即 taglib-sharp）是一个读写媒体文件元数据的库，支持视频、音频和照片格式。

## 度量（Metrics）

*   [C# StatsD Client](https://github.com/goncalopereira/statsd-csharp-client)：Etsy StatsD 服务器的 C# 客户端

## 微框架（Micro Framework）

*   [.NET Micro Framework Interpreter](https://github.com/NETMF/netmf-interpreter)：Microsoft® .NET Micro Framework（NETMF）是一个在 Visual Studio 中提供为小型设备上编写嵌入式应用的框架。

## 杂项（Misc）

*   [.NET Fiddle](https://dotnetfiddle.net/)：在浏览器中编写、编译并运行 C# 代码。相当于 C# 版本的 JSFiddle。
*   [AzureCrawler](https://github.com/yagopv/AzureCrawler)：从 Angular、Ember、Durandal 或任何 JavaScript 应用中获取 HTML 快照。
*   [BitSharp](https://github.com/pmlyon/BitSharp)：C# 比特币节点。
*   [CSScript](http://www.csscript.net/)：CS-Script 是一个基于 CLR 的脚本系统，使用 C# 作为编程语言。CS-Script 目前针对微软的 CLR 实现（.NET 2.0/3.0/3.5/4.0/4.5）并完整支持 Mono。附带很多附加特性，比如脚本宿主。
*   [CsvHelper](https://github.com/JoshClose/CsvHelper)：帮助读写 CSV 文件的开发库。[http://csvhelper.com](http://csvhelper.com)
*   [FluentValidation](https://github.com/JeremySkinner/FluentValidation)：一个小型的 .NET 校验库，使用流式接口和 lambda 表达式构建校验规则。
*   [Humanizer](https://github.com/MehdiK/Humanizer)：Humanizer 能够在 .NET 平台上满足所有针对字符串、枚举、日期、时间、时间范围、数字等类型数据的操作和显示要求。
*   [LINQPad](http://www.linqpad.net)：一个 C#/VB/F# 的便签本，能够立即执行任何表达式、语句块或程序，带有富文本显示等有用的特性。同样可以让你使用 LINQ 进行交互性数据库查询。 [$]（译者注：也有免费许可，但是功能受限）
*   [Polly](https://github.com/michael-wolfenden/Polly)：快捷便利的异常处理策略，例如 重试、始终重试、等待并重试或断路（Circuit Break）等行为。 （.NET 3.5、4.0、4.5、PCL、Xamarin）
*   [Rant](https://github.com/TheBerkin/Rant)：Rant 程序文本生成 DSL（领域特定语言）。 [http://berkin.me/rant](http://berkin.me/rant)
*   [ScriptCS](https://github.com/scriptcs/scriptcs)：使用文本编辑器、nuget 和强大的 Roslyn 来编写 C# 应用！

## MVVM

*   [Caliburn.Micro](https://github.com/Caliburn-Micro/Caliburn.Micro) ：小型但功能强大的框架，可以用来给所有 XAML 平台创建应用。它对 MV* 模式的强大支持可以让你快速构建你的解决方案，与此同时不必牺牲代码质量和可测试能力。
*   [MVVM Light Toolkit](https://mvvmlight.codeplex.com/)：该工具箱主要是用来加速创建和开发 MVVM 应用，适用于 WPF、Silverlight、Windows Store（RT）和 Windows Phone 平台。
*   [Catel](https://catel.codeplex.com/)：Catel 是一个应用开发平台，主要着眼在 MVVM（WPF、Silverlight、Windows Phone 及 WinRT）以及 MVC（ASP.NET MVC）。Catel 的核心部分包含 IoC 容器、模型、校验、备忘录模式（memento）、消息中介（message mediator）、参数检查等。
*   [UpdateControls](http://updatecontrols.net/cs/)：Update Controls 不需要你实现 INotifyPropertyChanged 接口或声明一个 DependencyProperty。可以将控件直接关联到 CLR 属性，这使得它完美贴合 MVVM 模式。
*   [ReactiveUI](https://github.com/reactiveui/reactiveui/)：一个 .NET 下的 MVVM 框架，集成了反应性扩展框架（Rx），允许开发者使用 WPF、Windows Store Apps、WP8 或 Xamarin 创建优雅的、可测试的应用。
*   [Okra App Framework](http://okraframework.github.io)：一个以 app 为中心的 Windows 8.1 MVVM 框架，融合依赖注入，包含一套完整的 Visual Studio MVVM 模板。
*   [WPF Application Framework (WAF)](http://waf.codeplex.com)：一个轻量级的框架，能够帮助你创建结构优雅的 WPF 应用。支持你使用分层架构和 MVVM 模式。
*   [MVVMCross](https://github.com/MvvmCross/MvvmCross)：跨平台mvvm 移动开发框架，针对 WP7 和 WP8 的 WPF/Silverlight、Android 的 Mono、iOS 的 MonoTouch 以及 WPA8.1/Windows 8.1 商店应用的 Windows Universal 项目。它使用可移植类库（PCL）来支持可维护的跨平台 C# 原生应用。
*   [Stylet](https://github.com/canton7/stylet/)：最小化 MVVM 框架（参考 Caliburn Micro），包含了良好的文档、高覆盖率的测试以及自带的 IoC 容器。
*   [Gemini](https://github.com/tgjones/gemini)：类似 Visual Studio Shell 的 IDE 框架。基于 WPF、AvalonDock 和 Caliburn Micro 构建。

## Office

*   [ClosedXML](https://closedxml.codeplex.com/)：ClosedXML 能够让开发人员更便捷地创建 Excel 2007、2010 文件。
*   [NPOI](http://npoi.codeplex.com/)：该项目是 .NET 版本的 POI 项目，原始的 Java 版本位于[http://poi.apache.org/](http://poi.apache.org/) 。
*   [EPPlus](http://epplus.codeplex.com/)：EPPlus 是一个 .net 类库，用于读写 Open Office Xml 格式的 Excel 2007、2010 文件（xlsx）。
*   [Open XML SDK](https://github.com/officedev/open-xml-sdk)：Open XML SDK 是一个开源库，用于处理 Open XML 文档（包括 DOCX、XLSX 和 PPTX）。

## ORM

*   [Entity Framework](https://github.com/aspnet/EntityFramework)：对象关系映射器（ORM）框架，让 .NET 开发人员使用领域特定的对象来处理关系型数据。
*   [BL Toolkit](https://github.com/igor-tkachev/bltoolkit)：.NET 平台的业务逻辑工具箱。
*   [Dapper](https://github.com/StackExchange/dapper-dot-net)：一个超小型、快捷轻便的 ORM 框架。
*   [Dapper Extensions](https://github.com/tmsmith/Dapper-Extensions)：小型类库，对 Dapper 的功能进行补充，为你的简单传统 CLR 对象提供基础的 CRUD（Get、Insert、Update、Delete） 操作。
*   [NHibernate](https://github.com/nhibernate)：NHibernate 对象关系映射器（移植自 Java 平台的 Hibernate）。
*   [Fluent NHibernate](https://github.com/jagregory/fluent-nhibernate)：便捷、无需使用 XML、编译安全、自动化、基于约定命名的 NHibernate 映射库。
*   [FluentMigrator](https://github.com/schambers/fluentmigrator)：.net 下的便捷的迁移框架。
*   [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite)：轻量、简单、快速、基于命名约定的 POCO ORM。
*   [Massive](https://github.com/robconery/massive)：小型、令人愉悦的数据访问工具，始终关爱你直到永远。
*   [LINQ to DB](https://github.com/linq2db/linq2db)：最快的 LINQ 数据库访问库，简单、轻量、快速、类型安全，在你的对象（POCO）和数据库之间搭建桥梁。

## 包管理（Package Management）

*   [NuGet](https://www.nuget.org/)：.NET 包管理器。
*   [MyGet](http://www.myget.org/)：为 NuGet、NPM、Bower 和 VSIX 提供程序包仓库宿主，同样提供 CI 服务。 **[[开源软件免费](https://www.myget.org/opensource)]** **[$]**
*   [Paket](https://github.com/fsprojects/Paket)：.NET 的一个包依赖管理器，支持 NuGet 包和 GitHub 仓库。 [http://fsprojects.github.io/Paket/](http://fsprojects.github.io/Paket/)

## PDF

*   [ITextSharp](https://github.com/itext/itextsharp)：iText 是一个PDF库，用于创建、修改、检查和维护 Portable Document Format（PDF）格式的文档 **[$]****[开源软件免费]**

## Profiler

*   [MiniProfiler](https://github.com/MiniProfiler/dotnet)：一个简单但有效的小型 profiler，用于 ASP.NET 网站。
*   [Glimpse](https://github.com/glimpse/glimpse)：开源 web 诊断平台。

## 推送通知（Push Notifications）

*   [PushSharp](https://github.com/Redth/PushSharp)：服务器端的推送通知类库，支持 iOS、OSX、Android、Chrome、Windows Phone、Windows 8、Backberry 和 Amazon 设备。

## 队列（Queue）

*   [NServiceBus](https://github.com/Particular/NServiceBus)：.NET 平台下最流行的服务总线。
*   [RabbitMQ.NET](http://hg.rabbitmq.com/rabbitmq-dotnet-client/)：AMQP 客户端的 C# 实现，通过 WCF 绑定到已有的 AMQP 服务。
*   [NetMQ](https://github.com/zeromq/netmq)：NetMQ 是 ZeroMQ 纯 C# 移植版本。
*   [MassTransit](https://github.com/MassTransit/MassTransit)：MassTransit 是一个精简服务总线（lean service bus）的实现，使用 .NET Framework 来构建松耦合应用程序。
*   [Rebus](https://github.com/rebus-org/Rebus)：Rebus 是一个 .NET 平台的精简服务总线和 NServiceBus、MassTransit类似，只不过更加精简。
*   [EasyNetQ](https://github.com/mikehadlow/EasyNetQ)：易于使用的 RabbitMQ .NET API。
*   [Warewolf ESB](https://github.com/Warewolf-ESB/Warewolf-ESB)：易于使用的服务总线和微服务平台，可以在一个可视化 IDE 中便捷的创建应用和服务。

## 响应式编程（Reactive Programming）

*   [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET)：Reactive Extensions （Rx）库使用观察者序列（observable sequences）和 LINQ 风格的查询操作，来进行异步和基于事件的程序开发、
*   [Dynamic Data](https://github.com/RolandPheasant/DynamicData)：用于集合的响应式编程框架。

## 计划调度（Scheduling）

*   [QuartzNet](https://github.com/quartznet/quartznet)：Quartz 是 .NET 平台的企业级调度器。
*   [Hangfire](https://github.com/HangfireIO/Hangfire)：在 ASP.NET 应用中，超简单地实现自主引导（fire-and-forget）、延迟和周期重复任务。高级版需要收费。
*   [Azure WebJobs](https://azure.microsoft.com/en-us/documentation/articles/app-service-webjobs-readme/)：Azure WebJobs 是Azure中App Services一个附属服务，为Azure中运行的Web App提供后台运行环境（支持多种语言编写Job），有.NET的SDK[开源](https://github.com/Azure/azure-webjobs-sdk)，并且可以直接添加扩展[也开源](https://github.com/Azure/azure-webjobs-sdk-extensions)。

## SDK 和 API 客户端（SDK and API Clients）

*   [AWS SDK](https://github.com/aws/aws-sdk-net)：AWS SDK for .NET 让 .NET 开发者可以便捷地操作 Amazon Web Services。
*   [Azure PowerShell](https://github.com/Azure/azure-powershell)：一组 PowerShell 命令行，让开发者和管理员开发、部署和管理 Microsoft Azure 应用。
*   [Octokit.NET](https://github.com/octokit/octokit.net)：.NET 平台下的 GitHub API 客户端库。
*   [DropNet](https://github.com/DropNet/DropNet)：Dropbox API 客户端开发库。

## 搜索（Search）

*   [Elasticsearch .NET](https://github.com/elasticsearch/elasticsearch-net)：Elasticsearch.Net & NEST。
*   [PlainElastic.Net](https://github.com/Yegoroff/PlainElastic.Net)：ElasticSearch 的一个简单的 .Net 客户端。
*   [SolrNet](https://github.com/mausch/SolrNet)：.Net 平台下的 Solr 客户端。
*   [Lucene.net](http://lucenenet.apache.org/)：Lucene.Net 是 Lucene 搜索引擎库的移植，使用 C# 编写，面向 .NET 环境的用户。

## 序列化（Serialization）

*   [Protobuf.NET](https://github.com/mgravell/protobuf-net)：Protocol buffers 是 Google 使用的二进制序列化格式，在 Google 数据通讯中大量使用。
*   [Json.NET](https://github.com/JamesNK/Newtonsoft.Json)：.NET 平台下流行的、高性能 JSON 框架。
*   [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text)：在 servicestack.net 中使用的 JSON、JSV、CSV 文本序列化器。
*   [Msgpack-Cli](https://github.com/msgpack/msgpack-cli)：MessagePack 的 CLI 实现。
*   [Jil](https://github.com/kevin-montrose/Jil)：.NET 平台下快速的 JSON 序列化器，基于 Sigil （在 StackOverflow 中使用）。
*   [ProtoBuf](https://github.com/hultqvist/ProtoBuf)：根据 .proto 规范，为 protocol buffer 序列化内容生成 C# 代码。
*   [F# Data](http://fsharp.github.io/FSharp.Data/)：F# 类型提供程序，访问 XML、JSON、CSV 和 HTML 文件（基于样例文档），以及访问 WorldBank 数据。
*   [Bond](https://github.com/Microsoft/bond)：跨平台框架，用于处理系统化（schematized）数据。支持跨平台的序列化、反序列化，以及强大的通用机制来高效处理数据。

## 状态机（State machines）

*   [Stateless](https://github.com/nblumhardt/stateless)：直接使用 .NET 代码创建一个状态机和轻量的基于状态机的工作流。
*   [Automatonymous](https://github.com/MassTransit/Automatonymous)：.Net 平台的状态机库，允许你编写流式API风格的状态机。

## 静态网站生成（Static Site Generators）

*   [Pretzel](https://github.com/Code52/pretzel)：.NET 平台下的网站生成工具（包含后续的一些功能）。
*   [Sandra.Snow](https://github.com/Sandra/Sandra.Snow)：.NET 平台的静态网站生成工具，借鉴 Jekyll。
*   [Wyam](http://wyam.io)：简单易用、高度模块化、拥有强大配置能力的静态网站生成工具。

## 风格指南（Style Guide）

*   [C# Style Guide](http://stackoverflow.com/questions/4678178/style-guide-for-c)：StackOverflow 上的C#风格指南 Q & A。
*   [C# Coding Conventions](http://msdn.microsoft.com/en-us/library/vstudio/ff926074.aspx)：MSDN 官方的 C# 代码约定。

## 模板引擎（Template Engine）

*   [RazorEngine](https://github.com/Antaris/RazorEngine)：基于微软 Razor 解析器引擎的开源模板引擎。
*   [Nustache](https://github.com/jdiamond/Nustache) ：无逻辑模板的开源库。
*   [DotLiquid](https://github.com/dotliquid/dotliquid)：Ruby Liquid 模板语言的 C# 移植版本。

## 测试（Testing）

*   [AutoFixture](https://github.com/AutoFixture/AutoFixture)：AutoFixture 是一个用于 .NET 的开源框架，用于简化单元测试中的设置（Arrange）阶段。
*   [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)：.NET 平台的一个简单的 mocking 库。[http://fakeiteasy.github.io](http://fakeiteasy.github.io)
*   [Fluent Assertions](https://github.com/dennisdoomen/fluentassertions)：一组 .NET 扩展方法，可以让你更自然地指定 TDD 或 BDD 风格测试的期望值。
*   [Fuchu](https://github.com/mausch/Fuchu)：F# 的单元测试库，通过 tests-as-values 机制让你更容易创建领域特定语言（DSL）。
*   [Machine.Specifications](https://github.com/machine/machine.specifications)：Machine.Specifications （MSpec）是一个上下文、规范框架，忽略了语言本身的干扰，简化了测试。
*   [Moq](https://github.com/Moq/moq4)：.NET 平台下最流行和友好的 mocking 框架。
*   [NBuilder](https://github.com/garethdown44/nbuilder)：快速创建测试对象。
*   [NSubstitute](http://nsubstitute.github.io/)：一个友好的 .NET mocking 框架。
*   [NUnit](https://github.com/nunit/nunit-framework)
*   [Rhino Mocks](https://github.com/ayende/rhino-mocks)：.NET 平台的动态 Mocking 框架
*   [Shouldly](https://github.com/shouldly/shouldly)：Shouldly 是一个断言（assertion）框架，主要功能是在断言失败时，给出简单明了并且友好的错误信息。
*   [SpecFlow](https://github.com/techtalk/SpecFlow/)：将业务需求绑定到 .Net 代码。
*   [xUnit](https://github.com/xunit/xunit)：xUnit.net 是一个 .NET 平台下免费、开源、专注社区的单元测试框架。

## 交易（Trading）

*   [Lean](https://github.com/QuantConnect/Lean)：Lean 引擎是一个开源的，完全由 C# 托管代码编写的交易算法引擎，用于桌面和云端。 [https://lean.quantconnect.com](https://lean.quantconnect.com)
*   [StockSharp](https://github.com/StockSharp/StockSharp)：交易和算法交易（algorithmic trading）的开源平台（用于股票市场、外汇市场、比特币和期权交易） 。[http://stocksharp.com](http://stocksharp.com)

## Visual Studio 插件（Visual Studio Plugins）

*   [Web Essentials](https://github.com/madskristensen/WebEssentials2013)：Web Essentials 为 Visual Stduio 扩展了大量的特性，提供了 web 开发人员盼望多年的功能。
*   [VsVIM](https://github.com/jaredpar/VsVim)：Visual Studio 中的 VIM。
*   [Nuget Package Manager](http://visualstudiogallery.msdn.microsoft.com/27077b70-9dad-4c64-adcf-c7cf6bc9970c)：NuGet 是微软开发平台（包括 .NET）的包管理器。
*   [SideWaffle](https://github.com/ligershark/side-waffle)：Visual Studio 2012、2013 中的一组项目模板集合，让 web 开发人员更加轻松。
*   [Resharper](http://www.jetbrains.com/resharper/)：Visual Studio 开发人员生产力工具 **[$]**
*   [Refactoring Essentials](http://vsrefactoringessentials.com/)：开源 C# 和 VB.NET 重构扩展，包括代码最佳实践分析器。
*   [CodeContracts](https://github.com/Microsoft/CodeContracts)：.NET CodeContracts 工具源代码。
*   [Git Diff Margin](https://github.com/laurentkempe/GitDiffMargin)：在 Visual Studio 滚动条区域实时显示当前文件在 Git 上的差异。
*   [Productivity Power Tools](https://visualstudiogallery.msdn.microsoft.com/d0d33361-18e2-46c0-8ff2-4adea1e34fef)：一组 Visual Studio 专业版（及更高版本）的扩展，用于提高开发人员的生产力。

## Web 框架（Web Frameworks）

*   [ASP.NET MVC](https://aspnetwebstack.codeplex.com/)：ASP.NET 是一个免费的 web 框架，用于创建优秀的 web 站点和应用程序。
*   [FubuMVC](https://github.com/DarthFubuMVC/fubumvc)：.NET 平台下前端控制器（front-controller）风格的 MVC 框架。[http://fubuworld.com/fubumvc](http://fubuworld.com/fubumvc)
*   [NancyFx](https://github.com/NancyFx/Nancy)：在 .Net 和 Mono 平台上创建 HTTP 服务的一个轻量级、非正式的框架。
*   [IISNode](https://github.com/tjanczuk/iisnode)：在 IIS 中宿主 NodeJS 应用程序。
*   [Suave.IO](http://suave.io/)：一个框架/库/web 服务器，当你看到你使用优美的 F# 编写的代码提前完成了你的项目时，它的存在会让你喜极而泣。（一个用 F# 编写 Web 应用的框架和服务器端）

## Web 服务器（Web Servers）

*   [EmbedIO](https://github.com/unosquare/embedio) ：基于 Mono 编写的跨平台的 Web 服务器。
*   [XSP](https://github.com/mono/xsp)：Mono 中的 ASP.NET 宿主服务器。该模块包含了 Apache 模块、FastCGI 模块，可以用于挂载到其它 web 服务器或是作为一个测试用的独立服务器存在（类似微软的 Cassini 项目）。

## WebSocket

*   [SignalR](https://github.com/SignalR/SignalR)：ASP.NET 库，开发者可以通过它在 web 应用程序中非常简单地实现实时功能。
*   [Fleck](https://github.com/statianzo/Fleck)：Fleck 是一个 C# 实现的 WebSocket 服务器。分支自 Nugget 项目。
*   [Websocket-Sharp](https://github.com/sta/websocket-sharp)：WebSocket 协议的 C# 实现，包含客户端和服务器端。
*   [XSockets](http://xsockets.net/)：提供了一组工具，可以在微软 .NET 等平台上构建一个实时应用程序。
*   [WebSocket4NET](https://websocket4net.codeplex.com)：.NET 2.0+、Xamarin、Mono、Silverlight、Windows Phone 以及 WinRT 下的 WebSocket 客户端。

## Windows 服务（Windows Services）

*   [TopShelf](https://github.com/Topshelf/Topshelf)：一个简单的服务宿主框架，使用 .NET 构建 Windows 服务。

## 其他列表（Other Lists）

*   [.NET-libraries-that-make-your-life-easier](https://github.com/tallesl/.NET-libraries-that-make-your-life-easier)：开源的 .NET 库，让你的生活更加轻松、
*   [awesome-LINQ](https://github.com/aloisdg/awesome-linq)：一组精心挑选的超棒的 LINQ 类库、工具等。

<h3 id="websites">知名网站</h3>
*值得关注的 DotNet 技术站点。*

<h4>中文站点</h4>

待补充

<h4>英文站点</h4>

待补充

<h3 id="weibo-weixin">微信公众号</h3>
* 「DotNet」：专注 .NET 相关内容，包括：.NET 和 C# 开发心得、工具资源和相关动态。
<br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2c79isfj20460460tr.jpg" width=150 height=150>
