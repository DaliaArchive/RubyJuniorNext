Web development is an art, and as any art requires a broad collection of skills. And not all
of them are technical coding skills, there are many others related to communication, or
idenfying business value, or estimation of costs, or understanding the stakeholders' (client, users, ...)
real needs.

# Definition of the problem to solve

Before we get into code there are many steps to be completed. Coding is just executing, the
real thinking comes before.


## Work in a Pet project

No better way of getting confortable with a new skill than to use it in something practical

The scope of the project has to be very narrow or we will end up struggling with complex
business logic that generates confusion and will distract us from our main objective
which is getting confident with the basic of Web development in general and Rails development
in particular.

A nice example is the classic _"TODO list"_ project. But maybe something that you will really use
would be better idea. What about something you can share with your friends or with someone on
your family? A simple tool to decide what movie to see?

---

- **Activity**: Find a cool and, at the same time, simple App to develop

## The Business Value

What is the value your App is giving to the Users?

We developers can do a lot of things for fun. But if we want to evolve our skills
into the professional ecosystem we have to understand that we are not here to hack
around but for adding value. As soon you identify your objectives with this as more
valuable you will be for companies and business people looking for a good technical partner.

There are many approaches to force you to define the Business Value of your idea, some of them can be:

- [The Product Canvas](https://www.romanpichler.com/tools/product-canvas/)
- [The Lean Project Canvas](https://www.agile42.com/en/blog/2013/04/11/lean-project-canvas/)

---

- **Activity**: Apply any of the above concept to your idea App

## Wireframing (User stories)

Don't start coding anything until you have clear all the User's workflows of your App.

Create [User stories](https://www.google.com/search?ei=RsH1W5mZDtmugAb-xbz4Dw&q=User+stories+tutorial)
that cover all your App.

Draw clear and nice to see [Wireframes](https://www.google.com/search?q=how+to+make+Wireframes&oq=how+to+make+Wireframes). Don't understimate the part of *nice to see*, you have to put attention
to everything you do, to every step, this is an important mindset and a very good habit. And this
starts in how you massage your ideas. You don't need to use professional and expensive tools to do your
wireframes, [pen and paper](https://www.google.com/search?tbm=isch&q=hand+drawn+wireframe)
[are perfect](https://www.youtube.com/watch?v=cFRvRtA-gtU) for this task.

Drawing wireframes is an art you should master, not only because it will help you in your development
but also because it will increase your capacities to communicate ideas to others (remmember: developing
is a collaborative activity)

Maybe can be good idea to make [course about wireframing](https://www.google.com/search?q=wireframe+online+course).

---

- **Activity**: Draw all the wireframes of your App
- **Activity**: Make a course about wireframming web Apps

## The Stakeholders (talk to them)

Gathering requirements and really understanding the problem you want to solve is a very important
step we developers have the bad habit to forget.

Once we listen to the idea of the client we switch imediately to _"implementing solution"_ mode without
really trying to understand the real problem the Client (stakeholder) is really strugling with.

In the case of our Pet-project we are our own stakeholder but we can make the exercise to share
our ideas with our potential Users and ask them what do they think about it? is it useful for them? will they use it? if not, what will make it useful for them?

Use your nice Wireframes to share your idea and to collect feedback from a group of potential Users.

---

- **Activity**: Interview 2 ~ 5 potential Users and collect all the possible feedback from them

## MVP (Minimum Valuable Product)

The development process is an iterative process. It is a bad idea to set up a bunch of
very cool features then get into a cave and don't get out until your ideal App is totally
completed. Very likely you will end with a big application that doesn't match with the basic
preferences of your final User, and at this stage will be very difficult and costly to pivot.

Instead try to identify what are the most basic features your App has to have to start
showing it to your final Users and to convince them to start using it. Even if a lot of needed
things are still missing.

This is a very interesting exercise and force you to have a very analytical instint to separate
what is really necessary from what it can wait a bit. This skill will help you to develop
things in contact with the reality. You need to expose your App to the final Users as soon as possible,
so you can learn from the feedback and you can pivot as soon as you identify there
have been some wrong assumption or when you identify an opportunity you have not expected before.

---

- **Activity**: Define what can be your first iteration, your first MVP.

## Estimations

Another important skill to adquire is our capcity to estimate the cost of an implementation.
This requires:

1. Risk identification, so we are capable to smell problems before they come. To detect what are the most risky parts of our App and to have a plan to validate these risks as soon as possible
2. To have developed a lot of things so we know how much it takes to be made

---

- **Activity**: Divide your MVP in smaller parts and stimate how long do you think it will take to you to develop each part. Annotate these numbers so you can validate them when you have finished each part implementation.

# Implementation

Let's move into the coding. Let's start implementing your MVP and we will iterate over it.

A part from the functionalities that your MVP requires let's be sure that we implement this list
of basic functionalities, they are pretty common on every Web development and it is good
if we get familiar with them as soon as possible.

---

- **Activity**: Make 2 online courses or read 2 books (or a mix) about Rails development.

## Login

Implement a login mechanism, you can use already built gems that are all around.

---

- **Activity**: Implement the login mechanism of your App

## Public / Front / Admin scopes

Create the app so there are clear 3 scopes.

- 1 for Admins, who will generate and edit all the elements of the system.
- 1 for registered Users, who have limited edition access.
- 1 for non-loged users with a frontal page for welcoming visitors showing the adventages of the system and invite them to register.

---

- **Activity**: Create the different scopes and be sure only Admin Users can do Admin stuff.

## Layouts and design

Provide the App with a professional user experience, you don't need a designer for this,
you can use popular CSS frameworks such [Bootstrap](https://getbootstrap.com/), the challenge
here is that using these frameworks properly require skills and experince to create the right
professional effect.

Be sure your application is full responsive and works perfectly in small screens as
mobile devices

---

- **Activity**: Implement your web interfaces following these premises.

## Implement the MVP functionalities

Let's go for the business value stuff and let's complete the functionalities of our first MVP.

---

- **Activity**: Divide the implementation in smaller parts. Implement each part in isolation, adding all the needed code and with all the needed test coverage. Try to make one commit for each completed part/functionality.

## Testing

I have my doubts of adding _testing_ as a section by it self. Testing should be as common as
breath. There is not a separate step _test_, it is all one with the implementation. Testing is
part of the implementation in the sense that it helps you to implement, it is a tool to validate
that what you are building actually works as you expect and you don't have to do complicate
workflows just to test an edge case you want to validate, allowing you to create quick feedback loops
between your implementation and your code validation.

Forget about TDD, this is old news already. People use to get very hot with things very quick and TDD
was a very hot hype for a while. You can not be implementing tests all the time before start coding,
specially when you are in the _exploratory_ mode when you still don't know how your methods are gonna
be called.

TDD is good when you are trying to fix a bug, in this case the best approach is to write a test
that reproduces the issue then fix the issue (no the other way arround). Then you assure that
you protect your App from this bug to happen again and also you have a way to validate that your fix
is actually fixing the issue.

So use testing as a tool to helps you develop, do it in parallel. Don't implement everything blindy
and then write the tests, neither write all the test then do the implementation.
Be flexive here, sometimes implementation goes first sometimes testing goes first.
Just be sure you are testing all your code, and that your tests are covering all
the edge cases: what happens is the User insert a 0? what happens if _ini_ is after _end_? ...

---

- **Activity**: Be sure your App has a proper [test coverage](https://github.com/colszowka/simplecov) and that all the edge cases are covered.


## Database

Be sure you are fluent with SQL. Database is your source of thruth. I know you can do a lot of
things through your ORM's API but you will be much more agile if you can query the databse directly.

You don't need to be an expert on SQL (it is a World in it self) but be sure you are confident with
any kind of _SELECT_ operation including _JOIN_, _HAVING_, _GROUP BY_, _ORDER BY_, ...

Try to find [online resources about SQL](https://www.google.com/search?q=how+to+learn+SQL+by+examples). And [other interesting resources](https://news.ycombinator.com/item?id=18335723).

---

- **Activity**: Complete a basic/middle SQL course

# Post-production

Not everything is implementing the application. We have to prepare it for deployment.

- Dockerize it. If the App requieres DB or other services maybe you need to use [Docker Compose or Docker Swarm](https://stackoverflow.com/questions/42545431/when-to-use-docker-compose-and-when-to-use-docker-swarm), it is not clear for me what is the standard now.
- Create a proper README with explanations of how to build and deploy the App. And any other documentation you think is important for a future maintainer of the project
- Deploy the App somewhere
- Implement systems to monitor [use](https://analytics.google.com/analytics/web/) and/or [errors](https://rollbar.com/) on the App in production.

---

- **Activity**: Make your App/MVP ready to easily be deployed

# Other languanges

Learning one language will wired your brain in an specific way. Each language has its own
paradigm. Some languages' paradigms are similar to others.

Some languages are more _OOP oriented_, some are more _functional_, some are more _declarative_,
some are more _imperative_, ...

Try to learn at least the basics of 3 different languages better if they have different paradigms.

This will wired your brain in different ways making you more flexible in making architecture decisions.

---

- **Activity** Complete courses of at least another 3 languages that use other paradigms. As a Ruby developer maybe you would like to learn a functional language like [Elixir](https://elixir-lang.org/) or a systems language like [Golang](https://golang.org/), pick up another on your taste.

# Community and Communication

Another important area to grow as a professional developer is to be constantly in contact
with what the community is discovering, sharing and working on.

I have my scepticism about following whatever the community is labeling as hot and hype.
But it is true that you will quickly lost track of new oportunities if you don't listen to
what is happening there outside. Then you have to make your own criteria about what do you think
is interesting and what looks more like a fast burning fire ball.

## Listen to others

There are many things happening there out side, and sometimes it can look overwhelming, frustrating
and stressing. But everything looks different if we have good communicators helping us to
understand what is going on.

There are many resources online that will explain you in understandable terms and, many times, in
an entertainment way what is the new thing and why, therically, it is important to you to know.

I am old school so I was very fun of:

- [Joel on Software](https://www.joelonsoftware.com/)
- [Coding Horror](https://blog.codinghorror.com/)
- [Paul Graham](http://www.paulgraham.com/)
- [Seth's Blog](https://seths.blog/)

They are more inspirational than technical but inspiration is the ignitor and we need to keep it active :).

As a technical front page I am using recently:

- [Hacker News](https://news.ycombinator.com/news)

Find [your own sources](https://news.ycombinator.com/item?id=14842276), agregate them and subscribe yourself to their RSS (yes, old school RSS still works). There are many pleasant to use [RSS readers](https://www.google.com/search?q=rss+reader).

Don't forget podcasts, there are many of good resources that uses this format and it may be more suitable for you. I remember with huge emotion my times following [Ryan Bates and his Railscast](http://railscasts.com/).

You don't need to start following a massive list of resources, it is better starting with a small list
(3 or 4) then you will find that one place brings you to another and little by little you start creating
your own network.

---

- **Activity**: create your small list of Blog/Podcats to follow and aggreate them in a RSS/Podcast reader

## Write a blog

Force your self to share things. Writting a blog gives you a very good training what includes:

- Understanding something good enough to be able to explaining it to others
- Excercise your writting communication skills
- Wrapping up what you have learn lately
- Participate in conversations with a solid opinion

Try to write a blog post every other week about literaly _anything_. It doesn't necessary
has to be anything complex, neither it has to be something purely technical. It can be something
about an experience with a college at work, or a curiosity you have, or the last course you have done,
or the last book you have read, ...

---

- **Activity**: Write a blog, write a new post every other week

## Participe in the conversations

Find a forum that fits you and become active on it.

I was very adictive to [StackOverflow](https://stackoverflow.com/users/316700/fguillen) once.
I remember I was learning [BackboneJS](http://backbonejs.org/) and I was very active on this topic
trying to answer every question it was showing up.

If StackOverflow works for you try to pick up unaswered questions and try to help others. Another way
to participate is doing interesting and properly structured Questions. If StackOverflow doesn't work
for you try another community.

The main objective is to participate in the conversations.

---

- **Activity**: Find a forum you like, be active on it.

## Make a talk

On the same level of the Blog. Try to extract enough material to make a small talk into your
local community group. This will help you to create confident and to see that it is not
as difficult as it looks like.

Local community groups are very receptive and they appreciate anyone that makes the effort to
prepare a talk.

In the same way of the Blog, the talk doesn't require to be very complex and technical. Also
it is not needed to be a 1 hour talk, it can be [just around 5 or 15 mins](https://www.youtube.com/watch?v=F1kDW538P0I).

---

- **Activity**: Find a nice subject, prepare some slides and make a presentation.

## Create a small OpenSource project

As a Ruby developer the easier way to approach this is to create a small Gem:

- [how to create a Gem](https://www.google.com/search?q=how+to+create+a+gem+ruby)
- [how to create a Gem with Bundler](https://bundler.io/v1.17/guides/creating_gem.html), Bundler has worked for me anytime [I tried to create a Gem](https://rubygems.org/profiles/fguillen), but other approaches can work for you as well.

Try to complete all this steps:

- It has a proper name
- It has a full README explaining why and how to use it. Try to make it very attractive. Add some imagen or illustration to make it more apealing.
- It is uploaded on [RubyGems](https://rubygems.org/)
- It is fully tested

---

- **Activity**: Create a Gem based on the above premises.

## Contribute to an OpenSource Project

Reading, understanding, adapting to, improving code that is not yours brings very possitive
effects on you.

Reading code from others is a difficult task, in it self is already a very nice exercise.

If you even are able to update it in the terms of the original creator you are also growing a lot
as a developer, you are learning to adapt to the way of how other person is thinking. This, in the same
line of learning other languages, will give to your brain new connections that can be helpful
for your own projects.

Try to find OpenSource projects that are active and try to improve them or to fix some of the
issues they have open. Then you have to convince the maintainer to accept your PullRequest.

---

- **Activity**: Make through all the process of having some PRs accepted (2 ~ 3) in other's open sources projects.

# Fullstack

Fullstack is another hype now, but I consider a legitime one. Now frontend frameworks are making professional JS development more accesible and more structured. Same thing with SysAdmin challenges, thanks for the containers technologies and serverless cloud services.

- Finding some Frontend Framework courses
- Docker, Docker-compose, Kubernetes

---

- **Activity**: Make a front-end framework online course

# Mentoring

Close the circle. Teaching others how to learn helps you to learn a lot.

Try to find someone to teach him/her something, maybe a basic things about programming, or
can be anything else.

---

- **Activity**: Have recurrent mentoring sessions with someone to teach him/her something.
