# EasyLearn
This is only for learning purposes. From me to all of you.
<p>Need to work on:</p>
  
  <h3>Ruby programming</h1>
  <h3>JSON</h1>
  <h3>Jenkins</h1>
  <h3>Docker vs kubernetes</h1>
  <h3>Vagrant</h1>
<h1>EasyMock</h1>
<ul>
  <li>Link1: http://easymock.org/user-guide.html</li>
      <p>introduction to the EasyMock</p>
  <li>Link2: https://www.tutorialspoint.com/easymock/index.htm</li>
      <p>More code exemple for introduction to the EasyMock</p>
  <li>Link3: https://www.baeldung.com/easymock</li>
  <li>Link4: https://www.ibm.com/developerworks/library/j-easymock/index.html </li>
  <p>present EasyMock on an currency example using interface for ExchangeRate</p>
  <p> EasyMock has similar methods for the primitive data types:</p><ul class="ibm-bullet-list"><li><code>EasyMock.anyInt()</code></li><li><code>EasyMock.anyShort()</code></li><li><code>EasyMock.anyByte()</code></li><li><code>EasyMock.anyLong()</code></li><li><code>EasyMock.anyFloat()</code></li><li><code>EasyMock.anyDouble()</code></li><li><code>EasyMock.anyBoolean()</code></li></ul><p>For the numeric types, you can also use <code>EasyMock.lt(x)</code> to accept any
                value less than <code>x</code>, or <code>EasyMock.gt(x)</code> to accept any value
                greater than <code>x</code>. </p>
  
</ul>
<p>Flow of jsf framework</p>
<ul>
  <li><b>createMock</b></li>
  <li>support exceptions</li>
  <li><b>assert</b> (to say that something is certainly true)</li>
  <li><b>verify</b></li>
    <p>EasyMock verify() method is used to make sure that all the stubbed methods are being utilized and there are no unexpected calls. The behavior for unexpected calls changes for nice mock objects where it doesn’t throw any error.</p>
  
    <p>verifyAll(); // verify all mocks at once but you need to ad an extension to the class EasyMockSupport</p>
    <p>If an unexpected method is called on a strict Mock Object, the message of the exception will show the method calls expected at this point followed by the first conflicting one. verify(mock) shows all missing method calls.</p>
</ul>

<h3>Components</h3>
  <p>1. Interface who have metods e.g. add(int a, int b), sum(int a, int b), div(int a, int b) etc.</p>
  <p>2. Class who make a coll to the Interface e.g. pubic addInterface(A a){
                                                          a.add(10, 20);
                                                    }
  </p>
  <p>3. Test class</p>
