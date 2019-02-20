# EasyLearn

This is only for learning purposes. From me to all of you.
<h2>AboutMe</h2>
<p>
 <ul>
  <li><a href="https://www.linkedin.com/in/tiberiu-cristian-corneanu-2aaa38179/">LinkedIn </a>(work time)</li>
  <li><a href="https://www.instagram.com/corneanutiberiu/">Instagram</a> (party time)</li>
 </ul>
</p>

<h2>CTF-related collection of information</h2>
 <p>If you search for 
  <a href="https://bitbucket.org/theiosif/learning-resources/src/91d016b31372?at=master"> security stuff (CTF-centered) </a>please check   the repository made by Iosif Andrei.
 </p>
<h2>Vagrant</h2>
 <p>
  <ul>
    <li><p><a href="https://github.com/tiberiucorneanu/vagrant"> Vagrant</a> introduction</p></li>
    
  </ul>
 </p>
<h2>Java</h2>
 <p>
  <ul>
    <li><p><a href="https://github.com/tiberiucorneanu/java1"> Java 1</a> Introduction to Java</p></li>
    <li><p><a href="https://github.com/tiberiucorneanu/java2"> Java 2</a> Introduction to Java EE (enterprise edition)</p></li>
    <li><p><a href="https://github.com/tiberiucorneanu/java3"> Java 3</a> Introduction to Java WebPage</p></li>
  </ul>
 </p>
 
 <h2>What is + name ?</h2>
 <p><a href="https://www.youtube.com/watch?v=j442WG8YzM4">HashMap</a> in java</p>
 <p><b>Unit tests</b> should be testing code without any outside dependencies. These dependencies are mocked using a framework like, for   example, JMock.<br>
 <b>Integration tests</b> are important too but the major drawback of them is that they take a long time to run. You can run thousands of true unit tests in a couple of seconds, but it's not the same with integration tests.</p>
 <p><a href="https://medium.com/@denisanikin/what-an-in-memory-database-is-and-how-it-persists-data-efficiently-f43868cff4c1">In-memory database</a></p>
 <p><a href="https://gist.github.com/prakashdayal/4699481">Hibernate mapping and Unit testing</a> code example</p>
 <p><a href="http://dbunit.sourceforge.net">DBUnit </a>extension of JUnit. an way to avoid problems that can occur when the test case corrupts the DB. DBUnit expo and impo DB to and from XML dates. Can help to verify data from DB = expected set of values</p>
 <p><a href ="https://howtodoinjava.com/best-practices/how-you-should-unit-test-dao-layer/">How to Unit test DAO layer </a>To testDAO we need access to DB and could use in-memory database( clean the database tables before each test)</p>
 <p><a href="https://vladmihalcea.com/the-minimal-configuration-for-testing-hibernate/">The minimal configuration for testing Hibernate </a>To test Hibernate you can simply rely on Hibernate flexible configuration options</p>
 
 <br>
 <p></p>
 <p><a href="https://dzone.com/articles/testing-databases-junit-and">Testing Databases with JUnit and Hibernate</a> Part 1: One to Rule them</p>
  <p><a href="https://dzone.com/articles/testing-databases-junit-and-0">Testing Databases with JUnit and Hibernate Part 2</a>The Mother of All Things</p>
  <p><a href="https://dzone.com/articles/testing-databases-junit-and-1">Testing Databases with JUnit and Hibernate Part 3: </a>Cleaning up and Further Ideas</p>
  <p><a href=""></a></p>
  
 <br>.<br>.<br>.<br>
 
 
<h1>Need to work on:</h1>
  
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
<h3><a href="https://dzone.com/articles/15-reasons-to-choose-hibernate-over-jdbc"> Hibernate vs. JDBC</a></h3>
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
</p>
