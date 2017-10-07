<h1>Udacity Logs Analysis Project</h1>

<p>By: Giovanny Pacheco <p>
<p> <strong>Full Stack Web Developer Nanodegree - Project 3 </strong> </p>


<h2>Description</h2>
<p>Project Overview </p>
<pre><code>
The database contains newspaper articles, as well as the web server log for the site. 
The log has a database row for each time a reader loaded a web page.
Using that information, the code will answer questions about the site's user activity.
This project will run from the command line.
It won't take any input from the user.
Instead, it will connect to that database, and use SQL queries to analyze the log data, and print out the answers to some questions
</code></pre>

<h3>Need</h3>
<p> - Python3</p>
<p> - Vagrant</p>
<p> - VirtualBox</P>


<p><strong>1st Step:</strong> Launch Vagrant VM by running vagrant up, you can then log in with vagrant ssh </p>
         
<p><strong>2nd Step:</strong> To load the data, use the command <strong>psql -d news -f newsdata.sql</strong>
          to connect a database and run the necessary SQL statements. </p>
          
<p><strong> The database includes three(3) tables: </strong></p>
<p>1.The authors table includes information about the authors of articles.</p>
<p>2.The articles table includes the articles themselves.</p>
<p>3.The log table includes.</p>

<p>To run the program, run <strong>newsdata.py</strong> from the command line.</p>
</body>