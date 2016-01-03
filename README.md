# DeviseAuth

<h4>User Authentication using Devise.</h4>

inside root directory:<br>
<tt>$ bundle install</tt><br>
<tt>$ rake db:migrate</tt><br>
<tt>$ rails server</tt>  

------------------------

view in heroku:<br>
https://warkentien2-deviseauth.herokuapp.com/

<strong>note:</strong> <p> Used Heroku e-mail authentication with <a href="https://devcenter.heroku.com/articles/sendgrid">SendGrid </a><br>
must pay to enable a worker process to handle job  
after paying, run:<br>
<tt>$ heroku ps:scale worker=1</tt>
</p>
