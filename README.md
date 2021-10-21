<h1>uflow-project-website</h1>
<h4>University of Alabama Computer Science Capstone Project (CS 495)</h4>
<h4>Fall 2021</h4>
<h4>Group: Cassidy Baumann, Mikey McDavid, Peyton Reed, Brady Wachs</h4>
<br>

<h2>About this repository</h2>
<p>
  As part of the course the group created a project description website. This website includes bios about each group member, deliverables from each sprint, and a video of our final presentation. 
  
  <a href="https://pdreed.github.io/uflow-website/">Click here </a>
  to view the project description website. 
  
  The source code for this project description website exists in this repository. 
</p>
<br>

<h2>Find repository for software developed during project</h2>
<p>
  <a href= "https://github.com/cmbaumann/uflow/tree/main">Click here </a>
  to see the UFlow repository. This contains all the source code for the web application developed.
  
  <a href= "https://uflow-alabama.herokuapp.com">Click here </a>
  to see the deployed web application. Currently the application is hosted on heroku. 
</p>
<br>

<h2>How to run/execute the application</h2>

<h3>How to use the hosted UFlow web application</h3>
<p>
  Go to the 
  <a href='https://uflow-alabama.herokuapp.com'>UFlow project home page.</a> <br>
  Create an account, filling out all required fields on the registration page. <br>
  A user will be taken to the <code>/logged_in</code> page. <br>
  From here a user can edit any of the given flowcharts by clicking on the edit button. This takes them to the <code>/flowchart</code> page. <br>
  Currently, you can choose the <code>taken</code>, <code>in progress</code>, or <code>future</code> buttons. Once you select a button, you can click all classes associated with this status. <br>
  &emsp;- A user can toggle between these statuses at anytime. <br>
  A user can save their flowcharts from this page. The flowchart will be saved to the database before opening a new, unedited flowchart. <br>
</p>
<br>

<h3>How to run the UFlow application on a local machine</h3>
<p>
  Clone project repository to your local machine. <br>
  &emsp;- One way to clone: <code>git clone https://github.com/cmbaumann/uflow.git</code> <br>
  Navigate to the <code>uflow</code> directory. <br>
  Use the command <code>python run.py</code> to run the application. <br>
  Click on the provided hyperlink in your terminal to view the application from a local host. <br>
  The terminal output should look something like: <br>
  <pre>
    <code>
   * Serving Flask app 'sourcecode.app' (lazy loading) <br>
   * Environment: production <br>
     WARNING: This is a development server. Do not use it in a production deployment. <br>
     Use a production WSGI server instead. <br>
   * Debug mode: off <br>
   * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit) <br>
    </code>
  </pre>
</p>
