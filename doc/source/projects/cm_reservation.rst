Cloudmesh Resource Reservation
======================================================================

Team
----------------------------------------------------------------------

* Natiele Bohn, nattibohn@gmail.com
* Gregor von Laszewski, laszewski@gmail.com
* Oliver Lewis, oliverlewis7@gmail.com


Problem
----------------------------------------------------------------------

Cloudmesh Resource Reservation is being developed to
create and manage reservations inside Cloudmesh.
Cloudmesh is a project that includes the ability to conduct
bare metal provisioning. It is important that this is supported
in a multiuser environment. We will be developing for this a
time based reservation system in which users will have
access to resources based on time slices. This project will
develop such a reservation system as a commandline tool and
also as a GUI (if time permits while leveraging the work
done by von Laszewski for this project). As a result we will
have a simple commandline tool that allows the administrator
or user to choose a reservation or query the system to find a
suitable reservation. Limits will be put in place so that users
do not reserve too many resources and block the systems
while not allowing others to use it. The system will have an
abstract plugin that allows the integration of a real bare metal
provisioning. However, for this project, we will simulate it
and focus only on the management of the reservation itself
and not how they are used or how machines are leveraged for
the actual bare metal provisioning. Convenient tables and
views are developed as part of the GUI development which is
doable as the GUI framework is already included in the
project developed by von Laszewski.

Plan of Action:

The follow information is a temporary plan of actions that
can bring more details about the daily lab activities proposed
by von Laszewski:

Week 1: Learn the basics: python, git, mongo, get
familiar with the old reservation code developed by
Oliver Lewis who is a grad student here at Indiana
University
Week 2: Develop a mongo database to generate
random reservations and display them in an image
via Ploticus
Week 3: Complete the database design while using
Mongoengine and create commandline tools using
Docopts to interact with the database (rewrite
Olivers code)
Week 4: Improve the flask interface that von
Laszewski developed and create better views, work
with Fugang on this in case help is needed.
Week 5: Develop a mechanism that restricts access
in various ways through policies. For example: a
user is time limited on all or some machines, the user has not access to all machines, the user has
restrictions based on project memberships
Week 6: Write commandline tools to manage
policies, write GUI forms and use forms to manage
policies in mongo. Use Mongoengine for all of this
Week 7: Continue development and code cleanup
Week 8: Complete the 2 page paper that you
worked on until now, complete the documentation,
code and transition ownership to Gregor von Laszewski and Fugang. Discuss the possibility of
this code can be introduced into the production
code of Cloudmesh.



First week
----------------------------------------------------------------------

The follow information are some of the tasks already done on
the first week of work:

* Install Ubuntu
* Learn commands on Linux shell
* Learn Python and its syntax
* Create account on GitHub
* Read the old code of Reservation
* Learn commands like git clone, git pull, git commit
and git push to bring the code of reservation to my
workstation and after make changes in the code
push it back to GitHub to allows another users to
see the changes in the code and work in parallel

Second week
----------------------------------------------------------------------
The follow information are some of the tasks already done on
the second week of work:

* Learn about how Mongodb works on the
background of Mongoengine
* Created a database to integrate and generate
random reservations on Cloudmesh
* Test the code on generate.py on reservations
* Develop new functions inside model.py on reservations. 
The functions developed were responsible for find different information inside
the random reservations that were created.

Design
----------------------------------------------------------------------


Implementation
----------------------------------------------------------------------


Links
----------------------------------------------------------------------

Some documentation that I read can be found at:

* http://www.pythonforbeginners.com/
* http://docs.mongoengine.org/
* http://docopt.org/
