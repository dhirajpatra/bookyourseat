This application have following features:
Create the web application backend with the following requirements:
================================================================================================================

How to install:

Backend installation:-
Requirements:
Laraval 5.3, Mysql 5.6, Apache along with CROS [Header set Access-Control-Allow-Origin "*"
                                                Header set Access-Control-Allow-Methods "POST, GET, OPTIONS, DELETE, PUT"
                                                Header set Access-Control-Max-Age "1000"
                                                Header set Access-Control-Allow-Headers "x-requested-with, Content-Type, origin, authorization, accept, client-security-token"]
So that if you run witin same localhost front end here it is AngularJs can call our back end easily without any error.

Steps:
First run the sql script to mysql after creating database named cross [you can change database and other configuration from laravel].
Copy paste the whole back end folder/application into your document room.
Create virtual host of name of your application.
Give proper permission to that folder with recursive way.

How to run:
Start the apache. Check your localhost is running.

Another isolated API created to send a mail report to admin.

REST API :eg.
http://cross/api/v1/bookmystand
[]
http://cross/api/v1/bookmystand/geteventdetails
[{"id":"1"}]
http://cross/api/v1/bookmystand/getallstands
[{"event_id":"1"}]
http://cross/api/v1/bookmystand/reservestand
[{"company_name":"good company","admin":"good admin","admin_email":"goodadmin@good.com","phone":"461333","add1":"good add1","add2":"good add2","zip":"64613", "stand_id":"2"}]


