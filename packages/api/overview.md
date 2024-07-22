# 1️⃣ 概览

## Spring框架概览 <a href="#page-title" id="page-title"></a>

Spring 使创建 Java 企业应用程序变得简单。它提供了在企业环境中使用 Java 语言所需的一切，支持 Groovy 和 Kotlin 作为 JVM 上的替代语言，并可根据应用程序的需要灵活创建多种架构。从 Spring Framework 6.0 开始，Spring 需要 Java 17+ 版本。&#x20;

Spring 支持多种应用场景。在大型企业中，应用程序通常会存在很长时间，而且必须在 JDK 和应用程序服务器上运行，其升级周期超出了开发人员的控制范围。其他应用程序可能以嵌入服务器的单个 jar 的形式运行，也可能在云环境中运行。还有一些可能是不需要服务器的独立应用（如批处理或集成工作负载）。

&#x20;Spring 是开源的。它拥有一个庞大而活跃的社区，根据各种实际用例不断提供反馈。这有助于 Spring 在很长一段时间内成功发展。

## 我们对Spring的理解

The term "Spring" means different things in different contexts. It can be used to refer to the Spring Framework project itself, which is where it all started. Over time, other Spring projects have been built on top of the Spring Framework. Most often, when people say "Spring", they mean the entire family of projects. This reference documentation focuses on the foundation: the Spring Framework itself.

The Spring Framework is divided into modules. Applications can choose which modules they need. At the heart are the modules of the core container, including a configuration model and a dependency injection mechanism. Beyond that, the Spring Framework provides foundational support for different application architectures, including messaging, transactional data and persistence, and web. It also includes the Servlet-based Spring MVC web framework and, in parallel, the Spring WebFlux reactive web framework.

A note about modules: Spring’s framework jars allow for deployment to JDK 9’s module path ("Jigsaw"). For use in Jigsaw-enabled applications, the Spring Framework 5 jars come with "Automatic-Module-Name" manifest entries which define stable language-level module names ("spring.core", "spring.context", etc.) independent from jar artifact names (the jars follow the same naming pattern with "-" instead of ".", e.g. "spring-core" and "spring-context"). Of course, Spring’s framework jars keep working fine on the classpath on both JDK 8 and 9+.

