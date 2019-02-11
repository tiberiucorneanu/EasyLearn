# EasyLearn
This is only for learning purposes. From me to all of you.
<p>AboutMe
 <ul>
  <li><a href="https://www.instagram.com/corneanutiberiu/">Instagram</a></li>
  <li><a href="https://www.linkedin.com/in/tiberiu-cristian-corneanu-2aaa38179/">LinkedIn</a></li>
 </ul>
</p>

<h2>CTF-related collection of information</h2>
 <p>If you search for 
  <a href="https://bitbucket.org/theiosif/learning-resources/src/91d016b31372?at=master"> security stuff (CTF-centered) </a>please check   the repository made by Iosif Andrei.
 </p>

<h2>Java</h2>
 <p>
  <ul>
    <li><p><a href="https://github.com/tiberiucorneanu/java1"> Java 1</a> Introduction to Java</p></li>
    <li><p><a href="https://github.com/tiberiucorneanu/java2"> Java 2</a> Introduction to Java EE (enterprise edition)</p></li>
    <li><p><a href="https://github.com/tiberiucorneanu/java3"> Java 3</a> Introduction to Java WebPage</p></li>
  </ul>
 </p>
<p>Need to work on:</p>
  
  <h3>Ruby programming</h1>
  <h3>JSON</h1>
  <h3>Jenkins</h1>
  <p>Connect it with vagrant https://stackoverflow.com/questions/6941547/how-to-combine-vagrant-with-jenkins-for-the-perfect-continuous-integration-envir</p>
  <p>Continuously integration, delivery, deploiment: https://www.atlassian.com/ro/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment</p>
  <h3>Docker vs kubernetes</h1>
  <h3>Vagrant</h1>
  <p>Vagrant.json  https://blog.scottlowe.org/2016/01/18/multi-machine-vagrant-json/</p>
  <p>tutorial https://www.youtube.com/watch?v=sjV4JdAw-Vs</p>
  <p>part 2 https://www.youtube.com/watch?v=X8iC5Q5lKLg< /p>
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

