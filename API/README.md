Itsyourskills Developer API Test
==================================

# Coding Test

Itsyourskills has a Test API available at https://test-api.t2scdn.com/ that you can use to get a stores information.

As an example, https://test-api.t2scdn.com/?store=123 returns a the details of store, including the contact information.

The API requires you specify a set of valid request headers before it'll respond.

        Accept-Tenant: uk
        Accept-Language: en-GB
        Accept-Charset: utf-8
        Authorization: Basic YXBpOnRlc3RhcGkh
        Host: test-api.t2scdn.com

* User is api
* Password is testapi!

The task is to create a command line application using C++/Qt, Android SDK, X Code or a basic script in PHP. The application should accept a store ID as a parameter. The application should then display the following information about the store.

* Name
* Address
* Opening times for the current day
* If the store is current open or closed


## Task requirements

- All stories to be completed with an appropriate level of testing.
- Feel free to use whatever testing, mocking or stubbing frameworks you prefer, along with any other packages you like.
- Your code should be of production quality.
- Clone our git repository locally and work on your solution


## User stories

### Story 1 - Accepting command line ( or $_GET in PHP)

As a **user running the command line application**<br />
I can **supply a valid store ID on the command line**<br />
So that **I can query the Itsyourskills API for results**

#### Acceptance criteria

* Command line parameter accepted

---

### Story 2 - Querying the API

As an **API consumer**<br />
I want to **query the store API**<br />
So that **I can output core store details**

#### Acceptance criteria

* Must provide valid headers
* For known store ID 123, some results are returned

---

### Story 3 - Outputting results

As a **user running the command line application**<br />
When I **search for a valid store ID**<br />
I want **store details printed into active window**

#### Acceptance criteria

* Name, Address and Open times for the store printed into active window

---

### Story 4 - Sorting results

As a **user running the command line application**<br />
When I **output core store details**<br />
I want **to see if the store is open or closed, and the open times for the today**

#### Acceptance criteria

* Store open / close status is outputted on screen
* Store opening times are outputted for today only

# Technical questions

Please answer the following questions in a markdown file called `Answers.md`.

* Did you have time to complete the coding test? What would you add to your solution if you had more time?
* What's your favourite programming language? Why?
* How would you track down a performance bottleneck in an application? Have you ever had to do this?
* How would you improve the Itsyourskills API?
* Please describe yourself using either XML or JSON.


Thanks for your time, we look forward to hearing from you!
- Itsyourskills Dev Team
