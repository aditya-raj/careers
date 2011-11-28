.. header :: ###Title###

.. footer :: ###Page###

==================
Careers at Votizen
==================


Preface::

This packet is designed to provide 1) an overview of Votizen, 2) what we're looking for in team members, 3) what we offer in a career, and 4) the process we use to find good matches to join our team.

Overview
========

Our Mission
-----------
Our mission is to put political power back where it belongs: in the hands of voters.

Our Vision
----------
We don't believe a broken system is capable of fixing itself.  Change must come from outside.  Social media are disrupting politics in profound ways, creating a new model for civic engagement.  

At Votizen we recognize this and are helping invert the political system, putting voters back into the position of power and influence.  Our members already have millions of friends in their existing personal networks.  We simply identify and connect those who are the most active voters and bring them together, voter-to-voter, based on common interests.  This data- and relationship-driven approach makes voters not passive targets of carefully crafted messages, but active participants in a connected election.

The recommendation of a trusted friend is infinitely more powerful than any 30-second attack ad or robocall.  This has always been true, but in the past our personal networks have been easily overpowered by broadcast networks.  No longer.  Now social networks have the power, and command the attention and respect of those we trust.  Votizen wants to empower these networks to fundamentally redefine politics in 2012 and beyond.  

Business Model
--------------
We are a network-effect business; the more voters that participate in the system, the more valuable the overall system becomes.  Network effect businesses are difficult to establish, but once built they are immensely valuable (Facebook, EBay, LinkedIn are other examples of network-effect businesses.)  Politics is a $10B a year industry that has grown 25% per year for fifty straight years; all of the industry's future growth will take place on the political graph, and we are going to be at the center of that market.


What We're Looking For
======================

We are looking for brilliant engineers with a passion for our mission.  If you think elegant code has the power to change the world, we want to talk to you.

We are not looking for accidental hackers.  We want people who have written their own framework, rather than used one to create a website.  We expect to see a CS degree *or* a ton of initiative.  A great candidate will be able to point to a body of work used by others or accepted pull requests on Github (ie, not just lots of forks.)  Inflated titles like CTO are not impressive to us; a well-followed blog or project is.  

Above all, we want really smart people committed to our goals.  Our standards are very, very high but we believe that we are solving the single-most important problem facing our country and our world.  This is a calling, not a job.

We are a Python/Django shop.  The right engineer will not have a problem switching to these but without knowledge of either the hiring process will require additional work to prove that.  Be warned.


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
Our team is very strong:  David Binetti, our CEO, has ten years' industry experience and was the creator of one of the first examples of government e-transparency:  USA.gov.  Jason Putorti, our designer, was the lead designer for Mint.com and is one of the most highly sought-after designers in the valley.  Matt Snider, our engineer, is a front-end guru and has written a book on Javascript (literally).  Jeremy Dunck is a Python expert and the Secretary of the Django foundation.  David Gouldin is a contributor to httplib2 which is the dominant python HTTP library.  You get the idea: we want to continue the tradition of only hiring the very best in a given person's field of expertise.

Agile process
-------------
We ascribe to agile development processes.  We are big believers in test-driven development.  We thoroughly document our code.  We engage in continuous deployment.  We don't have a QA department; when something escapes our test coverage and breaks we fix it immediately.  For us, it's all about reducing the iteration cycles.  Our processes favor quick identification of problems and fast recovery.  Speed is the best prevention.  

Great investors
---------------
Our lead investor is Peter Thiel who has an exceptional track record in picking winners.  Our board member is Sean Parker.  We have some of the most prescient investors in the business, including Keith Rabois, Mark Goines, Ron Conway, Chris Dixon, and David Cowan.  These investors see a huge opportunity in a space ripe for disruption, and anyone thinking about participating in this space knows that the group we've assembled is second to none. 

Fantastic culture
-----------------
We have a great culture that rewards risk-taking and creativity.  We create features by taking the perspective of the user:  "A member should be able to do FOO in order to accomplish BAR as measured by BAZ."  After that, implementation is up to the engineer.  We are very flexible in our work hours, as long as the job gets done.  And we play hard as well -- the office is very competitive, particularly in Starcraft.

Benefits, Perks
---------------
Our benefits and perks are quite light compared to other large companies.  We do have have full health coverage for families, offer commuter checks, and generally try to be as flexible as possible in responding to team members' needs.  But you can forget things like 401Ks, massage therapists and stuff like that.  Our goal is to make our equity so valuable that all those things become rounding errors in our personal net worth.

Compensation
---------------
We place a premium on equity participation and not salary.  Our belief is,  "Salary to live on; Equity to retire on."  In fact, we have a hard cap on our salary of $120,000.  No one in the company makes more than that.  

Tools
-----
We don't have religion on tools.  Our basic principle is to use the simplest tool that will get the job done.  While things may change, you should have a good understanding of the following:

- Amazon Web Services
    - EC2 for front-end servers
    - S3 for serving content
    - RDS for backend MySQL databases
    
- Redis 
    - Use for our newsfeed and other streams

- Python
    - We use Django for our front-end CRUD
    - twisted (for our asynch API)

Process
=======
Following is the hiring process to which we aspire:


Portfolio Review
----------------
Once submitted, we review a candidate's resume to assess experience and qualifications.  After the review, there should be one of two outcomes:

    1.  Schedule `Sell & Evaluation Screen`_
    2.  `No Match`_

Sell & Evaluation Screen
------------------------
The Sell & Evaluation screen is a 20-30 minute interview where the screener's goal is to sell the Votizen vision, feel out the candidates interest, and read whether or not they would be a good fit. This screener should notify the candidate that the next step is an involved 3-6 hour mandatory coding problem. After the screen, a decision should be immediately made according to one of two outcomes:

    1.  Send `Remote Coding Problem`_
    2.  `No Match`_

Remote Coding Problem
---------------------

The coding problem is included in this repository as RemoteCodingProblem.rst, and is a task that shows they know or can learn Django, Python, and Apache. The completed project should be checked into a public Github account, which we can pull down and run locally. The problem should take 3-6 hours, depending on the candidates understanding of our technology stack, and the amount of extras they add.

    1.  If above bar, schedule `On Site Pair Programming`_
    2.  `No Match`_


On Site Pair Programming
------------------------
The on site pair programming is an in-person interview, where the candidate will be tasked to code a multi-layered problem on a computer while being paired with one of our engineers. The candidate should be asked to bring a laptop with them (and they can use the language of their choice), or we will provide one.  After the on-site, a decision should be immediately made according to one of two outcomes:

    1.  If good fit, schedule `On Site Team`_
    2.  `No Match`_

On Site Team
------------
The on site team is the final step meant to give all team members an opportunity to assess culture fit. Generally, this should immediately follow the "On Site Pair Programming" step and include a lunch or dinner, but if pressed for time, simply a meet-and-greet. Prior to the team meeting, the focus should be on matching the skills to the role. The team meeting is for matching the personality to the culture of the company. After the on site team interview, all team members should come together to make a determination as follows:

    1.  `If good fit, Reference Check`_
    2.  `Hold`_
    3.  `No Match`_

Reference Check
---------------
Reference check should be the final assessment of skills.  It is designed really as a veto in case any material information has been misstated or other major issues surface.: 

    1.  `If passes, Hire`_
    2.  `No Match`_


Hire
----
Once the decision to hire has been made, the hiring manager must put together and present an offer package within one business day.  **No exceptions**

Hold
----
Periodically we might find good candidates that would be a good match aside from timing (on one side or another.)  These should be placed in a `Hold`_ status.  Ideally, when candidates are placed on hold there should be a defined trigger to bring them out of that state.  Examples include: vesting fully, finishing school, campaign ending, etc.  It should not be a catch-all category: the supposition should be that all candidates are either hired or declined.

No Match
--------
Most candidates will not be a match.  While each case may be handled individually, all candidates who have on site visits should be informed of no-match via phone.  Others may be informed via email.  All candidates should be treated respectfully.  

Applicant Tracking System
=========================

To apply, please use our links from our main job page at https://www.votizen.com/jobs.  

Special Note for Recruiters
===========================

At Votizen we love recruiters!  If you haven't already done so, please see our instructions on how to work with us at http://www.votizen.com/recruiters.  


Questions/Contact Information
=============================

If you have any additional information or questions please contact Marty Schneider at marty@votizen.com or 415.690.8683.

