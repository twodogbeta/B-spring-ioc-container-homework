1. 如果将第三方的类变成组件，又无源代码，无法使用@Component进行自动配置，这时候使用@Bean就很合适。也
当然也可以使用xml方式进行定义。
2. 因为@Bean注解的返回值是对象，所以可以在方法中为对象设置属性
3. Spring的Starter机制，就是通过@Bean注解定义Bean