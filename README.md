@Component一般作用在类上，当启动应用时，Spring会自动检测并配置被注解的类。
而@Bean是方法级别的，可以作用在方法上，更加灵活。而且可以按需选择注入的方法。
所以，@Component不会将bean的声明与类的定义解耦，而@Bean会将bean的声明与类的定义解耦
对于Spirng容器外的类，也可以用@Bean来选择注入，@Component就不可以。