# Problems
1.观察者模式和回调函数放在一起分析。</br>
上传例子，并分析这两种模式的使用条件以及优缺点。</br>
2.服务器端websocket示例（使用wasync)。</br>
3.分析Client部分的websocket实现以及各种回调。</br>
4.设计模式</br>
（1）四个基本要素：模式名称（用一两个词来描述问题、解决方案和效果），问题（描述在何时使用该模式），解决方案（描述设计的组成以及各部分之间的相互关系和各自的职责）、效果（描述模式的应用效果以及使用时需要权衡的问题）。</br>
（2）Smalltalk MVC中的设计模式：Observer（观察者模式），Composite（组合模式，将一组对象当作一个对象来使用），Strategy（View-Controller关系）。</br>
（3）描述设计模式：模式名和分类，意图，别名，动机，适用性，结构，参与者，协作，效果，实现，代码示例，已知应用，相关模式。</br>
5.设计模式的编目：</br>
  Abstract Factory:提供一个创建一些列相关或相互依赖对象的接口，无需指定它们的具体类。</br>
  Adapter：将一个类的接口转换成希望的另一个接口。该模式可以让原本由于接口不兼容而不能一起工作的那些类可以一起工作。</br>
  Bridge:将抽象部分和它的实现部分分离，是他们可以独立的变化。</br>
  Chain of Responsibility:为解除请求的发送者和接收者之间的耦合，而使多个对象都有机会处理这个请求。将这些对象连成一条链，并沿着这条连传递请求，直到有一个对象处理它。</br>
  Command：将一个请求封装为一个对象，从而使你可以用不同的请求对客户进行参数化，对请求排队或记录请求日志，以及支持可取消的操作。</br>
  Composite：将对象组合成树形结构以表示“部分-整体”的层次结构。使对单个对象和整体的使用保持一致性。</br>
  Decotator:动态地给一个对象添加一些额外的职责。就拓展功能而言，该模式比生成子类更加灵活。</br>
  Facade：为子系统中的一组接口提供一个一致的界面。该模式定义了一个高层次的接口，这个接口使得子系统更加容易使用。</br>
  Factory Method：定义一个用于创建对象的接口，让子类决定使用哪个类来实例化。使一个类的实例化延迟到其子类。</br>
  Flyweight：利用共享技术有效的支持大量细粒度对象。</br>
  Interpreter：给定一个语言，定义他的文法的一种表示，并定义一个解释器，该解释请使用该表示来解释语言中的句子。</br>
  Iterator：提供一种方法顺序访问一个聚合对象中的各个元素，而又不需要显式内部表示。</br>
  Mediator：用一个中介对象来封装一些列对象的交互。中介使各个对象不需要相互显式的引用，从而使其松耦合，而且可以独立改变它们之间的交互。</br>
  Mementor：在部破坏封装性的前提下，捕获一个对象的内部状态，并在该对象之外保存这个状态。这样以后就可以将该对象恢复到保存的状态。</br>
  Observer：定义对象之间的一种一对多的依赖关系，以便当一个对象发生改变的时候，所有依赖它的对象的都能得到通知并自动刷新。</br>
  Prototype：用原型实例指定创建对象的种类，并且通过拷贝这个原型来创建新的对象。</br>
  Proxy：为其他对象提供一个代理以控制对这个对象的访问。</br>
  Singleton：保证一个类仅有一个实例，并提供一个访问它的全局访问点。</br>
  State：允许一个对象在其内部状态改变时改变它的行为。对象看起来似乎修改了它所属的类。</br>
  Strategy：定义一系列的算法，把它们一个个封装起来，并且是它们可以互相替换。使得算法的变化可以独立于使用它的客户。</br>
  Template Method：定义一个操作中的算法骨架，而将一些步骤延迟到子类中。使得子类可以不改变一个算法的结构即可重定义该算法的某些特定步骤。</br>
  Visitor：表示一个作用于某对象结构中的各个元素的操作。它可以使你在不改变元素的类的前提下定义作用于这些类元素的新操作。</br>
6.组织编目：</br>
  创建型，结构型，行为型。
