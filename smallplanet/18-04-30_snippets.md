Monday. April 30, 2018
==============
* 10:30-6:10
* Setup with Adrienne
  * MacOs
  * Github Account
  * Slack
* Setup Env
  * OpenGrok
  * Atom
  * Android Studio
* Meeting with team:
  * Mike Shin: Developer
  * Mike Seidler: Producer
  * Ji: Designer
  * Julian: Lead Designer
  * Review existing app
* Meeting with Mike and Mike: Technical decision Zamarain vs Native
* Meeting with Mike: Thoughts and backend system proposal
* Code review: Voter Pal, and various existing projects
* Research exiting State voter systems

Tuesday. May 1, 2018
====================
* 10:15-6:20
* Standup
* Meeting with Mike, Mike, Ji, Fred: wireframe review
* Research api End Points
  * Google Civics
    * Provides Election Information
    * Polling Locations
  * Rock the Vote https://www.rockthevote.org
    * api [information](https://rock-the-vote.github.io/Voter-Registration-Tool-API-Docs/#overview)
    * Voting Information Project: https://votinginfoproject.org
      * Voter Information Tool
      * Data backend by Google Civics
    * TargetSmart: https://targetsmart.com
      * _seems to provide the data that backs Voter Registration Lookup Tool_
* Investigate data store solutions
  * SimpleDB (managed)
  * DynamoDB (managed)
  * MongoDB (unmanaged)

Wednesday. May 2, 2018
======================
* 10:00-6:30
* Standup
* Meeting with Mike, Mike, Ji, Fred: Discussed round 2 wireframe, statment of work open ended items, agreed to reveiw wireframe after discussion with client
* Research
  * Rock the Vote api. extracted api key and partner id to check out Data
    * so far this year 600 Registrations
    * this and last year 1000 registrations
  * Created Google Civics api key
* initial check-in to GitHub codebase

Thursday. May 3, 2018
=====================
* 10:00-6:45
* Standup
* Meeting with Mike, Mike, Ji, Fred, VotoLatino: Kickoff meeting to discuss expectations, process and time table
* Start setting up backend on my aws account.
  * Lambda Serverless Service
  * DynamoDb
  * Simple Email Service

Friday. May 4, 2018
====================
* Standup
* Continue setting up backend on my aws account.
  * Lambda Serverless Service
  * DynamoDb
  * Simple Email Service
  * deployed at: https://gxue2wcd08.execute-api.us-east-1.amazonaws.com/dev
  * https://github.com/SmallPlanetiOS/votolatino_VoterPal_Backend
