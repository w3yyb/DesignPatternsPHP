# PHP设计模式

[![Build Status](https://travis-ci.org/domnikl/DesignPatternsPHP.png?branch=master)](https://travis-ci.org/domnikl/DesignPatternsPHP)

这是一组(34个)已知的设计模式和一些如何在 PHP 中实现它们的示例代码。每个模式有一个小的示例列表 (他们大多数来自 Zend 框架、 Symfony2 或 Doctrine2 )。
我认为模式的问题是通常人们知道他们，但不知道什么时候使用。

## 模式

模式结构大致有三种不同的类别. 请点击 [:notebook:](http://en.wikipedia.org/wiki/Software_design_pattern) 有关的模式在维基百科上的完整说明。

### [Creational创建型模式](Creational)

* [AbstractFactory抽象工厂模式](Creational/AbstractFactory) [:notebook:](http://en.wikipedia.org/wiki/Abstract_factory_pattern)
* [Builder建造者模式](Creational/Builder) [:notebook:](http://en.wikipedia.org/wiki/Builder_pattern)
* [FactoryMethod工厂方法模式](Creational/FactoryMethod) [:notebook:](http://en.wikipedia.org/wiki/Factory_method_pattern)
* [Multiton多例模式](Creational/Multiton) (被认为是一种反模式! :no_entry:)
* [Pool对象池模式](Creational/Pool) [:notebook:](http://en.wikipedia.org/wiki/Object_pool_pattern)
* [Prototype原型模式](Creational/Prototype) [:notebook:](http://en.wikipedia.org/wiki/Prototype_pattern)
* [SimpleFactory简单工厂模式](Creational/SimpleFactory)
* [Singleton单例模式](Creational/Singleton) [:notebook:](http://en.wikipedia.org/wiki/Singleton_pattern) (被认为是一种反模式! :no_entry:)
* [StaticFactory静态工厂模式](Creational/StaticFactory)

### [Structural结构型模式](Structural)

* [Adapter适配器模式](Structural/Adapter) [:notebook:](http://en.wikipedia.org/wiki/Adapter_pattern)
* [Bridge桥接模式](Structural/Bridge) [:notebook:](http://en.wikipedia.org/wiki/Bridge_pattern)
* [Composite组合模式](Structural/Composite) [:notebook:](http://en.wikipedia.org/wiki/Composite_pattern)
* [DataMapper数据映射模式](Structural/DataMapper) [:notebook:](http://en.wikipedia.org/wiki/Data_mapper_pattern)
* [Decorator装饰模式](Structural/Decorator) [:notebook:](http://en.wikipedia.org/wiki/Decorator_pattern)
* [DependencyInjection依赖注入模式](Structural/DependencyInjection) [:notebook:](http://en.wikipedia.org/wiki/Dependency_injection)
* [Facade外观模式](Structural/Facade) [:notebook:](http://en.wikipedia.org/wiki/Facade_pattern)
* [FluentInterface流畅接口模式](Structural/FluentInterface) [:notebook:](http://en.wikipedia.org/wiki/Fluent_interface)
* [Proxy代理模式](Structural/Proxy) [:notebook:](http://en.wikipedia.org/wiki/Proxy_pattern)
* [Registry注册模式](Structural/Registry) [:notebook:](http://en.wikipedia.org/wiki/Service_locator_pattern)

### [Behavioral行为型模式](Behavioral)

* [ChainOfResponsibilities职责链模式](Behavioral/ChainOfResponsibilities) [:notebook:](http://en.wikipedia.org/wiki/Chain_of_responsibility_pattern)
* [Command命令模式](Behavioral/Command) [:notebook:](http://en.wikipedia.org/wiki/Command_pattern)
* [Iterator迭代器模式](Behavioral/Iterator) [:notebook:](http://en.wikipedia.org/wiki/Iterator_pattern)
* [Mediator中介者模式](Behavioral/Mediator) [:notebook:](http://en.wikipedia.org/wiki/Mediator_pattern)
* [Memento备忘录模式](Behavioral/Memento) [:notebook:](http://en.wikipedia.org/wiki/Memento_pattern)
* [NullObject空对象模式](Behavioral/NullObject) [:notebook:](http://en.wikipedia.org/wiki/Null_Object_pattern)
* [Observer观察者模式](Behavioral/Observer) [:notebook:](http://en.wikipedia.org/wiki/Observer_pattern)
* [Specification规格模式](Behavioral/Specification) [:notebook:](http://en.wikipedia.org/wiki/Specification_pattern)
* [State状态模式](Behavioral/State) [:notebook:](http://en.wikipedia.org/wiki/State_pattern)
* [Strategy策略模式](Behavioral/Strategy) [:notebook:](http://en.wikipedia.org/wiki/Strategy_pattern)
* [TemplateMethod模板方法模式](Behavioral/TemplateMethod) [:notebook:](http://en.wikipedia.org/wiki/Template_method_pattern)
* [Visitor访问者模式](Behavioral/Visitor) [:notebook:](http://en.wikipedia.org/wiki/Visitor_pattern)

### [More更多](More)
* [Delegation委托模式](More/Delegation) [:notebook:](http://en.wikipedia.org/wiki/Delegation_pattern)
* [ServiceLocator服务定位器模式](More/ServiceLocator) [:notebook:](http://en.wikipedia.org/wiki/Service_locator_pattern)
* [Repository仓库模式](More/Repository)
* [EAV实体属性值模式](https://github.com/domnikl/DesignPatternsPHP/blob/master/More/EAV) [:notebook:](https://en.wikipedia.org/wiki/Entity%E2%80%93attribute%E2%80%93value_model)



## License

(The MIT License)

Copyright (c) 2015 Lenix and [contributors](https://github.com/w3yyb/DesignPatternsPHP/graphs/contributors)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
