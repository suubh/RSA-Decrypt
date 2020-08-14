# RSA-Decrypt
It include a task that explains RSA algorithm and tries to decipher the plain text using some online services for mathematical calculations.
<h2>First try the question yourself using the below instructions and resources for RSA Algorithm</h2>
<p><strong>RSA algorithm</strong> is use to encrypt and decrypt messages and also used for Key exchange. </p><br>
<p>There are steps to create Public key and private key which is used for encryption and decryption </p>
<ol>
  <li>Take two prime number 'p' and 'q' ,such that they are very large prime numbers.</li>
  <li>Find 'n' using n=p*q .</li>
  <li>Now find phi(n)=(p-1)*(q-1) .</li>
  <li>Select 'e' such that 'e' is a co-prime to phi(n) .</li>
  <li>Calculate 'd' such that e*d*mod(phi(n))=1 .</li>
  <li>
    <ul>
      <li>Public key : (e,n)</li>
      <li>Private key : (d,n)</li>
    </ul>
  </li>
</ol>
<p><strong>Note : </strong> 'd' is find using <a href="https://en.wikipedia.org/wiki/Extended_Euclidean_algorithm">Extended Eucledian Algorihm.</a></p>
</hr>
<h2>Now in the given question we have the Cipher text(C), and the public key(e,n)</h2>
<p>Our first step will be to find <strong>'p'</strong> and <strong>'q'</strong> using given <strong>'n'</strong> ,because we know that n=p*q and it can be factored.For finding <strong>'p'</strong> and <strong>'q'</strong> we use online services.<a href="https://www.alpertron.com.ar/ECM.HTM">Click here to find yours.</a></p><br>
<img src="https://suubh.github.io/RSA-Decrypt/Images/IMG_20200814_141902.png">
<p>After finding <strong>'p'</strong> and <strong>'q'</strong> we need to find <strong>'d'</strong> . Using <strong>'p'</strong>,<strong>'q'</strong> and <strong>'e'</strong> we cannot perform the steps manually so we will use any online services to find <strong>'d'</strong>. <a href="https://www.cryptool.org/en/cto-highlights/rsa-step-by-step" >Click here to find yours.</a></p><br>
<img src="https://suubh.github.io/RSA-Decrypt/Images/IMG_20200814_142043.png">
<img src="https://suubh.github.io/RSA-Decrypt/Images/IMG_20200814_142112.png">


<p>After getting the value for <strong>'d'</strong> and finding the Plain text using the above steps.Now it depends on how Plain text was created. For the above problem the message is stored in the hex of the plain text. For finding the hex of Plain text.<a href="https://codebeautify.org/hex-string-converter">Visit</a></p><br>
<img src="https://suubh.github.io/RSA-Decrypt/Images/IMG_20200814_142005.png">


  


