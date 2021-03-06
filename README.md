# EasyLearn
### How to make your [markdown](https://guides.github.com/features/mastering-markdown/)
This is only for learning purposes. From me to all of you.
### AboutMe
* [LinkedIn](https://www.linkedin.com/in/tiberiu-cristian-corneanu-2aaa38179/) (work time)  
* [Instagram](https://www.instagram.com/corneanutiberiu/) (party time)
### CTF-related collection of information
If you search for [security stuff (CTF-centered)](https://bitbucket.org/theiosif/learning-resources/src/91d016b31372?at=master) please check   the repository made by Iosif Andrei.
### Vagrant 
* [Vagrant](https://github.com/tiberiucorneanu/vagrant) introduction
### Java
* [Java 1](https://github.com/tiberiucorneanu/java1) Introduction to Java
* [Java 2](https://github.com/tiberiucorneanu/java2) Introduction to Java EE (enterprise edition)
* [Java 3](https://github.com/tiberiucorneanu/java3) Introduction to Java WebPage
### What is + name ?
 * [Spring framework](https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/htmlsingle/#testing-introduction) everithing about it  
 * [Sprring Test](https://spring.io/guides/gs/testing-web/) Testing the Web Layer REST API. This guide walks you through the process of creating a Spring application.  
 * [JAX-RS vs Jersey](https://stackoverflow.com/questions/17888757/what-difference-between-jersey-vs-jax-rs)   
   * JAX-RS is an specification and Jersey is a JAX-RS implementation.   
   * This can be understood relating it to OOPS principles JAX-RS is an Interface and Jersey is a class implementing that interface.   
   * These Specification creates a STANDARD for developing and using the web services.  
   * There are other JAX-RS implementations too like wink, RestEasy.  
   * JAX-RS is a specification which specifies how can we implement the web services,that what would be input type, input format, output type, its format, its configuration etc.Its Just a type declaration and its implementation are these libraries, Jersey, wink RestEasy etc.   
   * Further, Java also have specification like JPA(Java Persistence API) and like mentioned above there is Hibernate which is an implementation of JPA
 * [Jersey](https://www.vogella.com/tutorials/REST/article.html) REST with Java (JAX-RS) using Jersey  
 * [Jax-RS](https://github.com/resteasy/resteasy-examples) exemples of cod from the book "Restful Java With Jax-Rs (2009, Oreilly)"  
 * [Eclipse Web Tool Platform (WTP)](https://www.vogella.com/tutorials/EclipseWTP/article.html#installation-of-wtp) Java web development with Eclipse WTP - Tutorial  
 * [Mockito](https://static.javadoc.io/org.mockito/mockito-core/2.27.0/org/mockito/Mockito.html) The Mockito library enables mock creation, verification and stubbing.  
 * [Run cmd](https://drive.google.com/file/d/0B-PizWTHf9T_SldwcVI4NXctRWM/view) from java project and [youtube](https://www.youtube.com/watch?time_continue=41&v=7-VAepy_r-8)   
* [HashMap](https://www.youtube.com/watch?v=j442WG8YzM4) in java
  * **Unit tests** should be testing code without any outside dependencies. These dependencies are mocked using a framework like, for   example, JMock.  
  * **Integration tests** are important too but the major drawback of them is that they take a long time to run. You can run thousands of true unit tests in a couple of seconds, but it's not the same with integration tests.
 * [In-memory database](https://medium.com/@denisanikin/what-an-in-memory-database-is-and-how-it-persists-data-efficiently-f43868cff4c1) 
 * [Hibernate mapping and Unit testing](https://gist.github.com/prakashdayal/4699481) code example  
 * [DBUnit](http://dbunit.sourceforge.net) extension of JUnit. an way to avoid problems that can occur when the test case corrupts the DB. DBUnit expo and impo DB to and from XML dates. Can help to verify data from DB = expected set of values  
 * [How to Unit test DAO layer](https://howtodoinjava.com/best-practices/how-you-should-unit-test-dao-layer/) To testDAO we need access to DB and could use in-memory database( clean the database tables before each test)  
 * [The minimal configuration for testing Hibernate](https://vladmihalcea.com/the-minimal-configuration-for-testing-hibernate/) To test Hibernate you can simply rely on Hibernate flexible configuration options  
 
 <br>
 <p></p>
 <p><a href="https://dzone.com/articles/testing-databases-junit-and">Testing Databases with JUnit and Hibernate</a> Part 1: One to Rule them</p>
  <p><a href="https://dzone.com/articles/testing-databases-junit-and-0">Testing Databases with JUnit and Hibernate Part 2</a>The Mother of All Things</p>
  <p><a href="https://dzone.com/articles/testing-databases-junit-and-1">Testing Databases with JUnit and Hibernate Part 3: </a>Cleaning up and Further Ideas</p>
  <p><a href=""></a></p>
  
 <br>.<br>.<br>.<br>
 
 
<h1>Need to work on:</h1>

  <h3><a href="https://www.google.ch/search?client=opera&q=java+reflextion&sourceid=opera&ie=UTF-8&oe=UTF-8">Java reflection</a></h3>
  <h3>Ruby programming</h1>
  <h3>JSON</h1>
  <h3>Jenkins</h1>
  <p>Connect it with vagrant https://stackoverflow.com/questions/6941547/how-to-combine-vagrant-with-jenkins-for-the-perfect-continuous-integration-envir</p>
  <p>Continuously integration, delivery, deploiment: https://www.atlassian.com/ro/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment</p>
  <h3>Docker vs kubernetes</h1>
 
  
  
<h1>EasyMock in porgress</h1>
<ul>
  <li>Link1: http://easymock.org/user-guide.html</li>
      <p>introduction to the EasyMock</p>
  <li>Link2: https://www.tutorialspoint.com/easymock/index.htm</li>
  <li>Link3: https://www.baeldung.com/easymock</li>
      <p>More code exemple for introduction to the EasyMock</p>
 
  <li>Link4: https://www.ibm.com/developerworks/library/j-easymock/index.html </li>
  <pre>present EasyMock on an currency example using interface for ExchangeRate</pre>
  <pre>Testing an XML parser</pre>
  
  <p> EasyMock has similar methods for the primitive data types:</p><ul class="ibm-bullet-list"><li><code>EasyMock.anyInt()</code></li><li><code>EasyMock.anyShort()</code></li><li><code>EasyMock.anyByte()</code></li><li><code>EasyMock.anyLong()</code></li><li><code>EasyMock.anyFloat()</code></li><li><code>EasyMock.anyDouble()</code></li><li><code>EasyMock.anyBoolean()</code></li></ul><p>For the numeric types, you can also use <code>EasyMock.lt(x)</code> to accept any
                value less than <code>x</code>, or <code>EasyMock.gt(x)</code> to accept any value
                greater than <code>x</code>. </p>
   
  
</ul>
<p>Flow of EasyMock framework</p>
<ul>
  <li><b>createMock</b></li>
  <li>support exceptions</li>
  <li><b>assert</b> (to say that something is certainly true)</li>
  <li><b>verify</b></li>
    <p>EasyMock verify() method is used to make sure that all the stubbed methods are being utilized and there are no unexpected calls. The behavior for unexpected calls changes for nice mock objects where it doesn’t throw any error.</p>
    <p>verifyAll(); // verify all mocks at once but you need to ad an extension to the class EasyMockSupport</p>
    <p>If an unexpected method is called on a strict Mock Object, the message of the exception will show the method calls expected at this point followed by the first conflicting one. verify(mock) shows all missing method calls.</p>
</ul>



<h1>Hibernate</h1>
<p>
<b>Hibernate ORM( object/relational mapping )</b><br>
  -concerned with data persistance as it applies to relational databases( via JDBC). As simple it can be convert classes to tables and objects to rows, and vice versa;<br>
  -persistance = some of our objects to live beyond JVM in order to be availabel later;
In addition is also an implementation of the JPA (Java Persistence API)<br>
<ul><b>JDBC (Java Databases Connectivity) </b> application interface that enables app to access the DB.<b>workflow:</b>
 <li>Open the DB;</li>
 <li>Send SQL queries to DB using JDBC driver;</li>
 <li>JDBC driver connects to the database;</li>
 <li>Execute the queries to get the result set;</li>
 <li>Send the data to the application via the driver manager;</li>
 <li>When results are returned, it processes the data;</li>
 <li>Finally, the connection is closed.</li>
</ul>

<ul><b>Hibernate workflow:</b>
 <li>Connects with the DB itself using <b>bHQL</b> (Hibernate Query Language) to execut queries, them maps the rsults to Java objects;</li>
 <li>Send SQL queries to DB using JDBC driver</li>
 <li>JDBC driver connects to the database</li>
 <li>Execute the queries to get the result set</li>
 <li>Send the data to the application via the driver manager</li>
 <li>When results are returned, it processes the data</li>
 <li>Finally, the connection is closed</li>
</ul>
<h3><a href="https://dzone.com/articles/15-reasons-to-choose-hibernate-over-jdbc"> Hibernate vs. JDBC</a> (<a href="https://www.devteam.space/blog/hibernate-vs-jdbc-which-to-choose/">another opinion</a>)</h3>
 <b> Impedance Mismatch </b> hibernate solved this problem when relation DB are connected by app weitten in OOP; <br>
 <b> Object Mapping </b> while in JDBC you need to write code to map the object model's data representation to a relational model and its cerresponding schem, hibernate maps Java classes to database tables using XML or annotations; <br>
 <b> Hibernate's HQL </b> provides full support for polymorphic queeries, understands inheritance and association; <br>
 <b> Database Independent </b> being easy to migrate to a new database; <br>
 <b> Minimize code changes </b> when we add a new column to a database table; <br>
 <b> Reduce repeat code </b>; <br>
 <b> Lazy Loading </b> by fetching the documents where you want using hibernate initialize method;  <br>
 <b> Avoiding Try-Catch Blocks </b> beacuse Hibernate handles this using unchecked exceptions; <br>
 <b> Transaction Management </b> performed under one task. In JDBC if transaction is a success you need to commit or rollback. In Hibernate you don' need to do this beacuse is omplicitly provided; <br>
 <b> Associations </b> between tables is easyer uning Hibernate; <br>
 <b> Versioning </b> if two users use the same datas from DB and afther the first one update DB the second one wil have an error; <br>

<h3><a href="https://www.java4s.com/hibernate/main-advantage-and-disadvantages-of-hibernates/">Disadvantages of Hibernates</a></h3>
 <b>Lots of API to learn:</b> A lot of effort is required to learn Hibernate. So, not very easy to learn hibernate easily. <br>
 <b>Debugging:</b> Sometimes debugging and performance tuning becomes difficult. <br>
 <b>Slower than JDBC:</b> Hibernate is slower than pure JDBC as it is generating lots of SQL statements in runtime. <br>
 <b>Not suitable for Batch processing:</b> It advisable to use pure JDBC for batch processing. <br>
 <b>Not suitable for Small projects:</b> For small project having few tables it is useless to work with hibernate. <br>
 <b>Does not allow multiple inserts:</b> Hibernate does not allow some type of queries which are supported by JDBC. For example It does
   not allow to insert multiple objects (persistent data) to same table using single query. Developer
   has to write separate query to insert each object. <br>
 <b>Generates complex quires with many joins :</b> For complex data, mapping from Object-to-tables and vise versa reduces performance      and increases time of conversion. (query conversion) <br>
</p>
