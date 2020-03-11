# Spring快速入口

### Spring注解方式启动测试类

```java
AnnotationConfigApplicationContextTests.java
AnnotationConfigWebApplicationContextTests.java
```

### 类型转换服务测试类

```java
GenericConversionServiceTests.java
```

### 资源获取类
```java
PathMatchingResourcePatternResolverTests.java
ClassPathResourceTests.java  
```
### Properties属性加载
```java
//spring运行时注入熟悉
PropertiesLoaderUtils.loadProperties(propertyResource);

//properties属性注入给某个对象
// spring boot2 可以用 org.springframework.boot.context.properties.bind.Binder
new RelaxedDataBinder(configFromListener).bind(new MutablePropertyValues(properties));
```
### AOP测试类

```java
SimpleScanTests.java
```
### Aspectj表达式测试类
```java
TrickyAspectJPointcutExpressionTests.java
```
### AOP代理对象创建类

```java
AspectJAwareAdvisorAutoProxyCreator.java
ProxyFactoryTests.java
```

