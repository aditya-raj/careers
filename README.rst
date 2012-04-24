.. _USA.gov: http://www.usa.gov
.. _Mint.com: http://www.usa.gov
.. _Django: https://www.djangoproject.com/foundation/
.. _book on javascript: http://http://www.packtpub.com/yahoo-user-interface-library-2x-cookbook/book
.. _Requests: http://http://docs.python-requests.org/en/latest/index.html
.. _David Binetti: http://davidbinetti.com
.. _Jason Putorti: http://jasonputorti.com/
.. _Matt Snider: http://mattsnider.com  
.. _Jeremy Dunck: http://www.linkedin.com/pub/jeremy-dunck/1/323/64b
.. _David Gouldin: http://www.facebook.com/dgouldin
.. _Emily Leathers: http://www.linkedin.com/in/eleather
.. _Erik Rose: https://github.com/erikrose

==================
Careers at Votizen
==================

This packet is designed to provide:

    1. An `Overview`_ of Votizen

    2. `What We're Looking For`_ in team members 
    
    3. `What We Offer`_ in a career
    
    4. The `Process`_ we use to find good matches to join our team

Overview
========

Our Mission
-----------
Our mission is to create a new political currency based on voter-to-voter connections, reducing the influence of money and increasing the importance of relationships in civic engagement.

Our Vision
----------
We don't believe a broken system is capable of fixing itself.  Change must come from outside.  Social media are disrupting politics in profound ways, creating a new model for civic engagement.  

At Votizen we recognize this and are helping invert the political system, putting voters back into the position of power and influence.  Our members already have millions of friends in their existing personal networks.  We simply identify and connect those who are the most active voters and bring them together, voter-to-voter, based on common interests.  This data- and relationship-driven approach makes voters not passive targets of carefully crafted messages, but active participants in a connected election.

Business Model
--------------
We are a network-effect business; the more voters that participate in the system, the more valuable the overall system becomes.  Network effect businesses are difficult to establish, but once built they are immensely valuable (Facebook, eBay, and LinkedIn are other examples of network-effect businesses).  Politics is a $10B a year industry that has grown 25% per year for fifty straight years; all of the industry's future growth will take place on the political graph and we are going to be at the center of that market.

Our Technology
--------------
We are data-driven company.  We start with a database of the nearly 200 million registered voters in the United States with more than a billion rows of voter history.  We then graph this data against the social networks of our members, empowering them to campaign for the candidates and causes they believe in.  On the front end, we employ a LAMP stack: specifically Ubuntu, Apache, MySQL/PostgreSQL, and Python (within the Django framework.)  We also use cool stuff like Redis, Celery, Rabbit, Memcached, Puppet, Selenium, Nagios, Vagrant, HA Proxy, and Elastic Search.  And everything operates in the cloud, of course: specifically on Amazon Web Services using EC2, S3, Route 53 and other cloud goodness.

How We Code
-----------

Our development philosophy is based on one principle -- speed.  We practice Continuous Deployment: commits are pushed to production within about ten minutes.  We don't have a staging server or QA department.  This means that we need to have high discipline on test coverage to ensure that our build stays green.  The emphasis is on fixing things quickly more than writing bug-free code from the outset.  We have weekly sprints with daily standups at 9:58AM and PivotalTracker keeps us on target, but otherwise we try to keep process to an absolute minimum.  It's all about developing features and shipping them to our users as quickly as possible.


What We're Looking For
======================

Engineer
--------

We want strong engineers to work on building new features and products related to the Votizen website and API.  We want very smart people who are accustomed to moving fast under conditions of uncertainty and who share our vision for improving democracy.

Responsibilities
++++++++++++++++

- Analyze, architect, and develop applications on LAMP stack: Ubuntu, Apache, MySQL/PostgreSQL, Python (within Django framework).

- Research, analyze, implement and integrate new mechanisms and technologies to solve technical problems (don't reinvent the wheel).

- Be prepared to move fast and be flexible.


Experience
++++++++++

- Experience with developing LAMP-based applications is required.

- Solid knowledge of engineering principles, religion in unit-testing code, and an understanding of regular expressions.

- Experience with the APIs from social networks like Facebook and Twitter.

- Experience with database design and optimizations.

- Experience with Python, Django and PostgreSQL is preferred.

- Experience with HTML, JavaScript, and CSS is desired.

DevOps
------

We are looking for an operationally focused engineer to be our DevOps lead.  This person will own the entire application release process, ensuring coordination between all developers and automating the process to the greatest extent possible.


Responsibilities
++++++++++++++++

- Ensure high-availability of our cloud-based production environment.

- Build effective deployment systems that are fully contributory to our development environment.

- Build effective monitoring systems that alert us to problems at the earliest possible moment with infrequent false positives.

- Develop scalability plans with our development stack clearly in mind.

- Ensure the highest degree of security in our systems, both internally and externally.


Experience
++++++++++

- Experience developing web applications

- Experience deploying in a cloud-based environment

- Knowledge of continuous deployment strategies is a huge plus.

- Experience with tools such as Puppet, Vagrant, Nagios (or their equivalent) is required.

- Experience with database administration and ETL is a huge plus.

What We Offer
=============

Change the world potential
--------------------------
First and foremost, we're working on something that truly has the potential to change the world in profound ways.  We're ensuring our democracy will be around for our grandkids, and that's a lot more important than building a revolutionary way to sell grilled cheese or running a quick flip on a Groupon clone.

Hard technical challenges
-------------------------
We have huge challenges in machine learning, classification, and scale.  Our database already has every voter in the United States plus their voting history -- in some cases going back thirty years.  This is a billion rows of data and we've barely even started.  We need to figure out how to process this information in way that is meaningful to each and every voter starting in the US (200 million voters) and eventually abroad (Democracy is a growth business.)  Moreover, we have a new approach to social networking that uses dynamic linking, meaning: forming and re-forming the interest graph as opinions change, accommodating new nodes and edges in realtime along the way.  No one has done this before, and it represents the future of social networks.

Lasting Impact
--------------
As our success grows, more and more real people are going to rely on our tools to help form decisions about the future of our country.  This means that millions of voters will use the tools our engineers create, and will use them every day.  It will be a badge of honor that Votizen engineers work on something so important and fundamental to the lives of everyday citizens.

Top-notch team
--------------
Our team is very strong:  `David Binetti`_, our CEO, has ten years' industry experience and was the creator of one of the first examples of government e-transparency:  `USA.gov`_.  `Jason Putorti`_, our designer, was the lead designer for `Mint.com`_ and is one of the most highly sought-after designers in the valley.  `Matt Snider`_, our engineer, is a front-end guru and has written a `book on Javascript`_ (literally).  Jeremy Dunck is a Python expert and the Secretary of the `Django`_ foundation.  David Gouldin is contributing to the `Requests`_ library, the successor to httplib2.  `Erik Rose`_ built large-scale Django sites at Mozilla and is a published author and conference speaker. You get the idea: we want to continue the tradition of only hiring the very best in a given person's field of expertise.

Agile process
-------------
We ascribe to agile development processes.  We are big believers in test-driven development.  We thoroughly document our code.  We engage in continuous deployment.  We don't have a QA department; when something escapes our test coverage and breaks we fix it immediately.  For us, it's all about reducing the iteration cycles.  Our processes favor quick identification of problems and fast recovery.  Speed is the best prevention.  

Great investors
---------------
Our lead investor and board member is Sean Parker, who has been at the forefront of several disruptive companies: Napster, Plaxo, Facebook, Causes, Spotify, and Airtime.  We have some of the most prescient investors in the business, including Keith Rabois, Mark Goines, Ron Conway, Chris Dixon, and David Cowan.  These investors see a huge opportunity in a space ripe for disruption, and our investors are an incredible asset to the company. 

Fantastic culture
-----------------
We have a great culture that rewards risk-taking and creativity.  We create features by taking the perspective of the user:  "A member should be able to do FOO in order to accomplish BAR as measured by BAZ."  After that, implementation is up to the engineer.  We are very flexible in our work hours, as long as the job gets done.  And we play hard as well -- the office is very competitive, particularly in Starcraft2.

Benefits, Perks
---------------
Our benefits and perks are quite light compared to other large companies.  We do have have full health coverage for families, offer commuter checks, and generally try to be as flexible as possible in responding to team members' needs.  But you can forget things like 401Ks, massage therapists and espresso machines.  Our goal is to make our equity so valuable that all those things become rounding errors in our personal net worth.

Compensation
---------------
We place a premium on equity participation and not salary.  Our belief is,  "Salary to live on; Equity to retire on."  In fact, we have a hard cap on our salary of $120,000.  No one in the company makes more than that.  

Process
=======
Following is the hiring process to which we aspire.  It is designed to be transparent, challenging, respectful, and above all -- fast.:

Prescreen
----------
Once a resume has been received, our HR Director will arrange a 5-10 minute call to discuss the following questions:

    1. Have you done any web development?
    2. What is your experience in Python/Django?
    3. Are you familiar with startup environments?
    4. Are you willing to work out of our Mountain View office daily?
    5. What is your interest in politics?

After the discussion a decision will be made based on one of two outcomes:

    1.  Send resume for `Qualifications Review`_
    2.  `No Match`_

Qualifications Review
---------------------
We review a candidate's resume/code repositories to assess experience and qualifications.  After the review, there should be one of two outcomes:

    1.  Schedule `Company Vision Presentation`_
    2.  `No Match`_

Company Vision Presentation
---------------------------
The Company Vision Presentation is a 10-15 minute phone conversation interview where David Binetti, our CEO, has the opportunity to present the company vision, answer any candidate questions, and generally assess whether there is a first-order match.  This step is more for the benefit of the candidate learn about us, and to determine if it is worth investing time in the `Remote Coding Problem`_.

    1.  If match and willing, conduct `Remote Coding Problem`_
    2.  `No Match`_

Remote Coding Problem
---------------------

The coding problem is included in this repository as RemoteCodingProblem.rst, and is a task that shows they know or can learn Django, Python, and Apache. The completed project should be checked into a public Github account, which we can pull down and run locally. The problem should take 3-6 hours, depending on the candidate's understanding of our technology stack and the amount of extras they add.

    1.  If above bar, schedule `On Site Pair Programming`_
    2.  `No Match`_


On Site Pair Programming
------------------------
The on site pair programming is an in-person interview, where the candidate will be tasked to code a multi-layered problem on a computer while being paired with one of our engineers. The candidate should be asked to bring a laptop with them (and they can use the language of their choice), or we will provide one.  After the on-site, a decision should be immediately made according to one of two outcomes:

    1.  If good fit, schedule `On Site Team`_
    2.  `No Match`_

On Site Team
------------
The on site team is the final step meant to give all team members an opportunity to assess culture fit. Generally, this will be a half-day of interviews. Prior to the team meeting, the focus should be on matching the skills to the role. The team meeting is for matching the personality to the culture of the company. After the on site team interview, all team members should come together to make a determination as follows:

    1.  If good fit, `Reference Check`_
    2.  `Hold`_
    3.  `No Match`_

Reference Check
---------------
Reference check should be the final assessment of skills.  It is designed really as a veto in case any material information has been misstated or other major issues surface.: 

    1.  If passes, `Extend Offer`_
    2.  `No Match`_


Extend Offer
------------
Once the decision to extend an offer has been made, the hiring manager must put together and present an offer package within one business day.  **No exceptions**

Hold
----
Periodically we might find good candidates that would be a good match aside from timing (on one side or another.)  These should be placed in a `Hold`_ status.  Ideally, when candidates are placed on hold there should be a defined trigger to bring them out of that state.  Examples include: vesting fully, finishing school, campaign ending, etc.  It should not be a catch-all category: the supposition should be that all candidates are either hired or declined.

No Match
--------
Most candidates will not be a match.  While each case may be handled individually, all candidates who have on-site visits should be informed of no-match via phone.  Others may be informed via email.  All candidates should be treated respectfully.  

Applicant Tracking System
=========================

To apply, please use our links from our main job page at https://www.votizen.com/jobs.  

Special Note for Recruiters
===========================

At Votizen we love recruiters!  If you haven't already done so, please see our instructions on how to work with us at http://www.votizen.com/recruiters.  


Questions/Contact Information
=============================

If you have any additional information or questions please contact Marty Schneider at marty@votizen.com or 415.690.8683.

