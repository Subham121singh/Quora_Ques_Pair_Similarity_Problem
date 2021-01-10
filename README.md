# Quora_Ques_Pair_Similarity_Problem

<h1><font color='cyan'>Machine Learning Problem</font></h1>

<h2><font color='orange'>Data</font></h2>
<ol type=I>
<li>Data will be in a file Train.csv</li>
<li>Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate</li>
<li>Size of Train.csv - 60MB</li>
<li>Number of rows in Train.csv = 404,290</li>
</ol>

<h2><font color='orange'>Example of Data point</font></h2>
<pre>
"id","qid1","qid2","question1","question2","is_duplicate"
"0","1","2","What is the step by step guide to invest in share market in india?","What is the step by step guide to invest in share market?","0"
"1","3","4","What is the story of Kohinoor (Koh-i-Noor) Diamond?","What would happen if the Indian government stole the Kohinoor (Koh-i-Noor) diamond back?","0"
"7","15","16","How can I be a good geologist?","What should I do to be a great geologist?","1"
"11","23","24","How do I read and find my YouTube comments?","How can I see all my Youtube comments?","1"
</pre>

<h2><font color='orange'>Mapping a Real World Problem to an ML Problem</font></h2>
<ol type=I>
<li><h3>Type of Machine Learning Problem.</h3></li>
> For a given pair of questions we need to predict whether they are duplicate or not.
<ul type='square'><li>Therefore, it is a <font color='blue'>Binary Classification or 2 - Class Classification Problem.</font></li></ul>
<li><h3>Performance Metric.</h3></li>
<ul type='square'>
<li>Log Loss-  <a href = 'https://www.kaggle.com/c/quora-question-pairs#evaluation'> Kaggle - Evaluation Metric</a> </li>
<li>Binary Confusion Matrix</li>
</ul>
