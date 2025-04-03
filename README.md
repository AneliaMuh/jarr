java -jar ./artifacts/aqa-shop.jar

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v2.2.1.RELEASE)

2025-04-03 13:57:56.282  INFO 12720 --- [           main] ru.netology.shop.ShopApplication         : Starting ShopApplication v0.0.1-SNAPSHOT on Vladislav with PID 12720 (C:\Users\napst\IdeaProjects\untitled2\artifacts\aqa-shop.jar started by napst in C:\Users\napst\IdeaProjects\untitled2)
2025-04-03 13:57:56.284  INFO 12720 --- [           main] ru.netology.shop.ShopApplication         : No active profile set, falling back to default profiles: default
2025-04-03 13:57:56.725  INFO 12720 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data repositories in DEFAULT mode.
2025-04-03 13:57:56.762  INFO 12720 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 31ms. Found 3 repository interfaces.
2025-04-03 13:57:56.936  INFO 12720 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration' of type [org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2025-04-03 13:57:57.294  INFO 12720 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2025-04-03 13:57:57.301  INFO 12720 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2025-04-03 13:57:57.301  INFO 12720 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.27]
2025-04-03 13:57:57.341  INFO 12720 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2025-04-03 13:57:57.341  INFO 12720 --- [           main] o.s.web.context.ContextLoader            : Root WebApplicationContext: initialization completed in 1006 ms
2025-04-03 13:57:57.467  INFO 12720 --- [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2025-04-03 13:57:57.504  INFO 12720 --- [           main] org.hibernate.Version                    : HHH000412: Hibernate Core {5.4.8.Final}
2025-04-03 13:57:57.576  INFO 12720 --- [           main] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.0.Final}
2025-04-03 13:57:57.623  INFO 12720 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2025-04-03 13:57:57.764  INFO 12720 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2025-04-03 13:57:57.776  INFO 12720 --- [           main] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2025-04-03 13:57:58.175  INFO 12720 --- [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000490: Using JtaPlatform implementation: [org.hibernate.engine.transaction.jta.platform.internal.NoJtaPlatform]
2025-04-03 13:57:58.178  INFO 12720 --- [           main] j.LocalContainerEntityManagerFactoryBean : Initialized JPA EntityManagerFactory for persistence unit 'default'
2025-04-03 13:57:58.441  WARN 12720 --- [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'shopController' defined in U
RL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/controller/ShopController.class]: Unsatisfied dependency expressed through constructor parameter 0; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean 
with name 'shopService' defined in URL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/service/ShopService.class]: Unexpected exception during bean creation; nested exception is java.lang.IllegalArgumentException: Could not resolve placeholder 'spring.credit-gate.url' in value "${spring.credit-gate.url}"
2025-04-03 13:57:58.441  INFO 12720 --- [           main] j.LocalContainerEntityManagerFactoryBean : Closing JPA EntityManagerFactory for persistence unit 'default'
2025-04-03 13:57:58.441  INFO 12720 --- [           main] .SchemaDropperImpl$DelayedDropActionImpl : HHH000477: Starting delayed evictData of schema as part of SessionFactory shut-down'
2025-04-03 13:57:58.449  INFO 12720 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown initiated...
2025-04-03 13:57:58.456  INFO 12720 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown completed.
2025-04-03 13:57:58.459  INFO 12720 --- [           main] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2025-04-03 13:57:58.473  INFO 12720 --- [           main] ConditionEvaluationReportLoggingListener : 

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
2025-04-03 13:57:58.482 ERROR 12720 --- [           main] o.s.boot.SpringApplication               : Application run failed

org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'shopController' defined in URL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/controller/ShopController.class]: Unsatisfied dependency expressed throu
gh constructor parameter 0; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'shopService' defined in URL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/service/ShopService.class]: Unexpected exception during bean creation; nested exception is java.lang.IllegalArgumentException: Could not resolve placeholder 'spring.credit-gate.url' in value "${spring.credit-gate.url}"
        at org.springframework.beans.factory.support.ConstructorResolver.createArgumentArray(ConstructorResolver.java:787) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.autowireConstructor(ConstructorResolver.java:226) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.autowireConstructor(AbstractAutowireCapableBeanFactory.java:1358) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBeanInstance(AbstractAutowireCapableBeanFactory.java:1204) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:557) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:517) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:323) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:321) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:202) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.preInstantiateSingletons(DefaultListableBeanFactory.java:879) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:878) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:550) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:141) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:747) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:397) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.run(SpringApplication.java:315) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.run(SpringApplication.java:1226) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.run(SpringApplication.java:1215) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at ru.netology.shop.ShopApplication.main(ShopApplication.java:10) ~[classes!/:0.0.1-SNAPSHOT]
        at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[na:na]
        at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[na:na]
        at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[na:na]
        at java.base/java.lang.reflect.Method.invoke(Method.java:566) ~[na:na]
        at org.springframework.boot.loader.MainMethodRunner.run(MainMethodRunner.java:48) ~[aqa-shop.jar:0.0.1-SNAPSHOT]
        at org.springframework.boot.loader.Launcher.launch(Launcher.java:87) ~[aqa-shop.jar:0.0.1-SNAPSHOT]
        at org.springframework.boot.loader.Launcher.launch(Launcher.java:51) ~[aqa-shop.jar:0.0.1-SNAPSHOT]
        at org.springframework.boot.loader.JarLauncher.main(JarLauncher.java:52) ~[aqa-shop.jar:0.0.1-SNAPSHOT]
Caused by: org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'shopService' defined in URL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/service/ShopService.class]: Unexpected exception during bean creation; nested exception is java.lang.IllegalArgumentException: Could not resolve placeholder 'spring.credit-gate.url' in value "${spring.credit-gate.url}"
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:530) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:323) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:321) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:202) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.config.DependencyDescriptor.resolveCandidate(DependencyDescriptor.java:276) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.doResolveDependency(DefaultListableBeanFactory.java:1287) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.resolveDependency(DefaultListableBeanFactory.java:1207) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.resolveAutowiredArgument(ConstructorResolver.java:874) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.createArgumentArray(ConstructorResolver.java:778) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        ... 27 common frames omitted
Caused by: java.lang.IllegalArgumentException: Could not resolve placeholder 'spring.credit-gate.url' in value "${spring.credit-gate.url}"
        at org.springframework.util.PropertyPlaceholderHelper.parseStringValue(PropertyPlaceholderHelper.java:178) ~[spring-core-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.util.PropertyPlaceholderHelper.replacePlaceholders(PropertyPlaceholderHelper.java:124) ~[spring-core-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.core.env.AbstractPropertyResolver.doResolvePlaceholders(AbstractPropertyResolver.java:236) ~[spring-core-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.core.env.AbstractPropertyResolver.resolveRequiredPlaceholders(AbstractPropertyResolver.java:210) ~[spring-core-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.context.support.PropertySourcesPlaceholderConfigurer.lambda$processProperties$0(PropertySourcesPlaceholderConfigurer.java:175) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.resolveEmbeddedValue(AbstractBeanFactory.java:908) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.doResolveDependency(DefaultListableBeanFactory.java:1228) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.resolveDependency(DefaultListableBeanFactory.java:1207) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.resolveAutowiredArgument(ConstructorResolver.java:874) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.createArgumentArray(ConstructorResolver.java:778) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.autowireConstructor(ConstructorResolver.java:226) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.autowireConstructor(AbstractAutowireCapableBeanFactory.java:1358) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBeanInstance(AbstractAutowireCapableBeanFactory.java:1204) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:557) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:517) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        ... 36 common frames omitted

PS C:\Users\napst\IdeaProjects\untitled2> java -jar ./artifacts/aqa-shop.jar

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v2.2.1.RELEASE)

2025-04-03 14:10:42.014  INFO 996 --- [           main] ru.netology.shop.ShopApplication         : Starting ShopApplication v0.0.1-SNAPSHOT on Vladislav with PID 996 (C:\Users\napst\IdeaProjects\untitled2\artifacts\aqa-shop.jar started by napst in C:\Users\napst\IdeaProjects\untitled2)
2025-04-03 14:10:42.016  INFO 996 --- [           main] ru.netology.shop.ShopApplication         : No active profile set, falling back to default profiles: default
2025-04-03 14:10:42.451  INFO 996 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data repositories in DEFAULT mode.
2025-04-03 14:10:42.490  INFO 996 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 34ms. Found 3 repository interfaces.
2025-04-03 14:10:42.669  INFO 996 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration' of type [org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2025-04-03 14:10:43.048  INFO 996 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2025-04-03 14:10:43.054  INFO 996 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2025-04-03 14:10:43.055  INFO 996 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.27]
2025-04-03 14:10:43.089  INFO 996 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2025-04-03 14:10:43.089  INFO 996 --- [           main] o.s.web.context.ContextLoader            : Root WebApplicationContext: initialization completed in 1024 ms
2025-04-03 14:10:43.221  INFO 996 --- [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2025-04-03 14:10:43.274  INFO 996 --- [           main] org.hibernate.Version                    : HHH000412: Hibernate Core {5.4.8.Final}
2025-04-03 14:10:43.354  INFO 996 --- [           main] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.0.Final}
2025-04-03 14:10:43.401  INFO 996 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2025-04-03 14:10:43.546  INFO 996 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2025-04-03 14:10:43.559  INFO 996 --- [           main] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2025-04-03 14:10:43.930  INFO 996 --- [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000490: Using JtaPlatform implementation: [org.hibernate.engine.transaction.jta.platform.internal.NoJtaPlatform]
2025-04-03 14:10:43.933  INFO 996 --- [           main] j.LocalContainerEntityManagerFactoryBean : Initialized JPA EntityManagerFactory for persistence unit 'default'
2025-04-03 14:10:44.206  WARN 996 --- [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'shopController' defined in URL
 [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/controller/ShopController.class]: Unsatisfied dependency expressed through constructor parameter 0; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean wi
th name 'shopService' defined in URL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/service/ShopService.class]: Unexpected exception during bean creation; nested exception is java.lang.IllegalArgumentException: Could not resolve placeholder 'spring.credit-gate.url' in value "${spring.credit-gate.url}"
2025-04-03 14:10:44.207  INFO 996 --- [           main] j.LocalContainerEntityManagerFactoryBean : Closing JPA EntityManagerFactory for persistence unit 'default'
2025-04-03 14:10:44.207  INFO 996 --- [           main] .SchemaDropperImpl$DelayedDropActionImpl : HHH000477: Starting delayed evictData of schema as part of SessionFactory shut-down'
2025-04-03 14:10:44.214  INFO 996 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown initiated...
2025-04-03 14:10:44.219  INFO 996 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown completed.
2025-04-03 14:10:44.222  INFO 996 --- [           main] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2025-04-03 14:10:44.229  INFO 996 --- [           main] ConditionEvaluationReportLoggingListener :

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
2025-04-03 14:10:44.233 ERROR 996 --- [           main] o.s.boot.SpringApplication               : Application run failed

org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'shopController' defined in URL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/controller/ShopController.class]: Unsatisfied dependency expressed throu
gh constructor parameter 0; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'shopService' defined in URL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/service/ShopService.class]: Unexpected exception during bean creation; nested exception is java.lang.IllegalArgumentException: Could not resolve placeholder 'spring.credit-gate.url' in value "${spring.credit-gate.url}"
        at org.springframework.beans.factory.support.ConstructorResolver.createArgumentArray(ConstructorResolver.java:787) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.autowireConstructor(ConstructorResolver.java:226) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.autowireConstructor(AbstractAutowireCapableBeanFactory.java:1358) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBeanInstance(AbstractAutowireCapableBeanFactory.java:1204) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:557) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:517) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:323) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:321) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:202) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.preInstantiateSingletons(DefaultListableBeanFactory.java:879) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:878) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:550) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:141) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:747) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:397) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.run(SpringApplication.java:315) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.run(SpringApplication.java:1226) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at org.springframework.boot.SpringApplication.run(SpringApplication.java:1215) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
        at ru.netology.shop.ShopApplication.main(ShopApplication.java:10) ~[classes!/:0.0.1-SNAPSHOT]
        at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[na:na]
        at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[na:na]
        at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[na:na]
        at java.base/java.lang.reflect.Method.invoke(Method.java:566) ~[na:na]
        at org.springframework.boot.loader.MainMethodRunner.run(MainMethodRunner.java:48) ~[aqa-shop.jar:0.0.1-SNAPSHOT]
        at org.springframework.boot.loader.Launcher.launch(Launcher.java:87) ~[aqa-shop.jar:0.0.1-SNAPSHOT]
        at org.springframework.boot.loader.Launcher.launch(Launcher.java:51) ~[aqa-shop.jar:0.0.1-SNAPSHOT]
        at org.springframework.boot.loader.JarLauncher.main(JarLauncher.java:52) ~[aqa-shop.jar:0.0.1-SNAPSHOT]
Caused by: org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'shopService' defined in URL [jar:file:/C:/Users/napst/IdeaProjects/untitled2/artifacts/aqa-shop.jar!/BOOT-INF/classes!/ru/netology/shop/service/ShopService.class]: Unexpected exception during bean creation; nested exception is java.lang.IllegalArgumentException: Could not resolve placeholder 'spring.credit-gate.url' in value "${spring.credit-gate.url}"
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:530) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:323) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:321) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:202) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.config.DependencyDescriptor.resolveCandidate(DependencyDescriptor.java:276) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.doResolveDependency(DefaultListableBeanFactory.java:1287) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.resolveDependency(DefaultListableBeanFactory.java:1207) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.resolveAutowiredArgument(ConstructorResolver.java:874) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.createArgumentArray(ConstructorResolver.java:778) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        ... 27 common frames omitted
Caused by: java.lang.IllegalArgumentException: Could not resolve placeholder 'spring.credit-gate.url' in value "${spring.credit-gate.url}"
        at org.springframework.util.PropertyPlaceholderHelper.parseStringValue(PropertyPlaceholderHelper.java:178) ~[spring-core-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.util.PropertyPlaceholderHelper.replacePlaceholders(PropertyPlaceholderHelper.java:124) ~[spring-core-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.core.env.AbstractPropertyResolver.doResolvePlaceholders(AbstractPropertyResolver.java:236) ~[spring-core-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.core.env.AbstractPropertyResolver.resolveRequiredPlaceholders(AbstractPropertyResolver.java:210) ~[spring-core-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.context.support.PropertySourcesPlaceholderConfigurer.lambda$processProperties$0(PropertySourcesPlaceholderConfigurer.java:175) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractBeanFactory.resolveEmbeddedValue(AbstractBeanFactory.java:908) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.doResolveDependency(DefaultListableBeanFactory.java:1228) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.DefaultListableBeanFactory.resolveDependency(DefaultListableBeanFactory.java:1207) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.resolveAutowiredArgument(ConstructorResolver.java:874) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.createArgumentArray(ConstructorResolver.java:778) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.ConstructorResolver.autowireConstructor(ConstructorResolver.java:226) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.autowireConstructor(AbstractAutowireCapableBeanFactory.java:1358) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBeanInstance(AbstractAutowireCapableBeanFactory.java:1204) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:557) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:517) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
        ... 36 common frames omitted

