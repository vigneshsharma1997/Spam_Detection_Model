# Spam_Detection_Model
Naieve_Bayes Model
<!DOCTYPE html>
<html>
<body>
  <h1>Objective</h1>
  <p>Your task is to predict whether a message will be spam or not. In the class we used the <code>sklearn.countvectorizer</code> to find vectors for each message. Now you need to do the same task but rather than using <code>CountVectorizer</code>, you are required to use <code>TF-IDF Vectorizer</code> to find the vectors for the messages.</p>
  
  <h2>TF-IDF Vectorizer</h2>
  <p>You will use <code>TF-IDF Vectorizer</code> to convert a collection of text documents (SMS corpus) into a 2D matrix. One dimension represents documents, and the other dimension represents each unique word in the SMS corpus.</p>
  <p>If the <em>n</em>th term <em>t</em> has occurred <em>p</em> times in the <em>m</em>th document, the value at position (<em>m</em>, <em>n</em>) in this matrix will be <em>TF-IDF(t)</em>, where:</p>
  <ul>
    <li><strong>Term Frequency (TF):</strong> A measure of how frequent a term occurs in a document.</li>
    <li><strong>TF(t) =</strong> Number of times term <em>t</em> appears in document (<em>p</em>) / Total number of terms in that document</li>
    <li><strong>Inverse Document Frequency (IDF):</strong> A measure of how important a term is.</li>
    <li><strong>IDF(t) =</strong> log(Total number of documents / Number of documents with term <em>t</em> in it)</li>
  </ul>
  <p>At the end, we will have normalized vectors of equal length (unit length) for every message, equal to the size of the vocabulary (number of unique terms from the entire SMS corpus).</p>
</body>
</html>
