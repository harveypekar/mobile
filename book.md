# Mobile applications

## Introduction

Welcome to the course! It doesn't matter if you chose it voluntarily, look forward to it, if it's part of your specialization and you ambivalent about it, or an exceptional set of circumstances forces you to take it. Welcome.

This course has been designed with 3 goals in mind:

* To learn about mobile development: it's specific technologies, usage context, and publishing model.
* To do this in a general way, so we learn how to figure this out on your own for eg. VR applications.
* To practice several soft skills : writing a pitch, presenting a project, and writing a report.

You will do this by designing, implementing, and pitching a mobile app. "A mobile app" is a very specific term, it needs to be an app that specifically works well on mobile. We explain this in more detail in "Design of a mobile application".

The reasoning behind the structure of the course is simple. There's not that much to teach about mobile applications, so a project based course seems obvious. Even then, 6 credits is a lot, so we added practicing soft skills. This is not an arbitrary decision. In the industry, mobile applications are developed in a small team (less than 10 programmers), and it's important that you can propose and defend features and improvement. This is also generally true in the domain of digital experiences, where programmers are expected to discuss directly with artists and designers. If they make a mistake in what they ask of you, you're the one paying the price by changing your work, so it pays to catch errors as soon as possible!

An additional motivation was direct feedback from interns about what is missing from the entire degree. If you're surprised to find things like code quality in this course, it's because it acts as a bridge to your internship.

In short, I hope that you will learn a lot of things in this course. Perhaps a bit of specific mobile technologies, but, above all, general skills applicable to wherever you will end up later. Good luck, have fun!

## Practicalities

### Language

All offline material in this course will be provided in English. If anything is inaccessible to you (automatic translation is impossible, confusing language, etc...), please contact me via email. Feedback is the best way to improve this course.

All deliverables (documents you hand in on Toledo) are allowed to be in either English (any spelling) or Dutch. If you choose to write in Dutch, we encourage you to use English for IT specific terms.

We also encourage you to use a spellchecker, or use ChatGPT to have an initial text that you can correct and modify. You will never lose points in this course for language mistakes, but it's good to strive for good language. 


## Evaluation

Evaluation of this course is a bit complicated, as you will be graded on 4 separate things:

1. Your pitch : 3 points 
2. Your presentation : 3 points
3. Your report & defense : 14 points

This might be confusing, as the app you've made doesn't seem to be covered by any of these. Don't be fooled. All of these evaluations are testing whether you've thought about the application you're going to / have been implementing. The reasoning behind evaluating like this is simple: if you are employed as a mobile developer, you will almost always have no more than a handful of technical (programming) colleagues, or even none at all. This means that you would interface with non-technical people a lot, which means explaining the work you have, or are going to do. While you've already have learned some of these skills in another course, this time you will propose/defend the work you have actually done / will actually do. 

### Pitch

You will write a pitch document for your app. A pitch is basically a proposal for something that needs to be made, and it aims to receive approval or funding. A common pitch is the "elevator pitch". This is a 30 second talk, meant to sell an idea for an app. Basically, you're trying to convince someone that your idea is good, often with the idea that it's worth investing in. Another would be a "statement of work", which propose any kind of work done by one company for another. This can be several pages, or several hundreds of pages.
The proposal you will write lies somewhere at the short end. The minimum is one full page (A4). The limit of length would be 2 A4 pages. Your proposal should contain the following sections:

#### Header 

Your name (and everyone else in your group if you're doing a group work). Also add your student number(s).

#### Description

A short description of your app, one or two paragraph, and optionally one or several images if they can clarify what you're trying to accomplish. It should also explain why you're app is "intrinsically mobile" (see section)

For the images, you can screenshot an existing, and manually paste over your images / text. It doesn't need to look good, it needs to get the idea across. Of course you're allowed to have fun with it.

#### Motivation

A sentence or 2 on why you want to implement the app you are pitching.

#### Inspiration

A section where you look at other existing apps, and compare features of your app to existing implementations. It's important that you go into detail why the feature works, it's not just pointing and saying "that". For example:

"We looked at tinder a lot for our basic interactions. In tinder, someone swipes left to reject someone, and right to express interest. We do the same: if someone swipes left on an internship, it means they're not interested, and the spot will never be seen again. If someone swipes right, it's added to a list of potentially interesting spots. We chose to do this, as it's proven to be fun, works as a 10-second interaction, and solves the problem of the old excel list being boring"

No need to be too detailed in your feature, the next section is a better spot for that.

#### Statement of work 

A longer section, where you detail the features you want to implement, as well as non-feature work you want to do (eg build server). You don't need to go in detail on each feature, but you do need a lot. Ideally, aim for double what you think you can realistically implement. If you have trouble coming up with a big enough list, try to imagine the most over-engineered, gold-plated Rube-Goldberg machine with all of it's yaks shaved. You don't need to implement all of them. You will split up this list into two parts:

The "need to have" list. These are features that need to be present for your app to be usable at all. This is called the "minimum viable product", or mvp for short.

The "nice to have" list. These are features that don't have to be in your app to be usable, but would make it better.

Just a quick note : need to have and nice to have are unrelated to the scope of your project. I will go more into details on how much you should implement in another section.

#### Tech stack 

A very short description of the technologies you will use to implement your "need to have" features. You can elaborate on what technologies you would use for for "nice to have" features.

Note that by technologies we mean programming languages (eg Javascript), frameworks (eg Unity, React native), external services (eg database), and libraries (eg leftpad)

#### Risks

You have to write a list of risks. These are things you know might turn out to be a problem. Typical examples are "I don't if this feature is possible in this framework", "This feature might not be a good user experience, as I haven't implemented it yet". Less typical, but equally good are "I'm a procrastinator, and I know I will be tempted to start a week before it's due.". While this might seem pointless in the moment, we'll look back on this during the exam. It's not something that is important for your grades, but it's an interesting data point on how well you know yourself. 

## Design of mobile applications

### Intrinsically mobile

Your app should be 'intrinsically mobile'. This means that the app you design has to be designed to only work on smartphones, or work much better on mobile. It is easiest to illustrate with some examples

#### Existing apps that are intrinsically mobile

##### Instagram

Instagram is a social media platform that is very focused on photo's. While you can use instagram on desktop to browse other people's posts, or post text or screenshots, the main idea is to use your phone's camera to take selfie's, pictures of coffee at a coffee shop, or while traveling. Browsing instagram is also a good fit for a mobile app : you can scroll posts for 10 seconds while waiting in line, or you can scroll too long while trying to fall asleep in bed.

##### Google Maps

Google maps is easy to see as intrinsically mobile: you tend to need to use it when you're on the road, away from your pc. It also has a better UX on mobile: if you want to find a route between two points on pc, you have to specify the start and the destination. On mobile, the app knows the start position, as it has access to the GPS on your device.

#### Existing apps that are not intrinsically mobile

##### Steam mobile app

Steam is a platform to buy and play games on pc. It also allows you to add friends and chat with them. The mobile app focuses on chatting with friends and buying new games.
You could argue that Steam as a mobile app is intrinsically mobile, as when you are behind your pc, you would like to play games. When you are on the bus, it's impossible, so at that point you would like to chat with friends and browse the store.
In the end though, the app is a poor substitute for the full pc experience.

#### Traits of intrinsically mobile apps

Your app should not fit all of these criteria, but if it fits one or multiple you've probably designed an intrinsically mobile app

* Allows for interactions in a flexible time scale : your app can be used to do something usefuls in 10 second, but it can also be used for longer timespans. Examples: Instagram, Tinder
* Has to use a unique hardware feature of mobile platforms for it's core functionin (eg GPS, camera, gyroscope). Examples: Be my eyes, Google maps, Bounden. 
* Is designed to solve a problem that occurs away from a pc. Examples: Strava, Shazam

## Glossary

* Procrastinator: someone who puts off all tasks until the last minute, or even longer. This can be something as short as sending an email (my record is 3 years), or starting to studying / working an entire course a day before the exam. If this is you, please read [This comic](https://waitbutwhy.com/2013/10/why-procrastinators-procrastinate.html). 
* [Rube Goldberg machine](https://en.wikipedia.org/wiki/Rube_Goldberg_machine) : In the context of software development, an algorithm that does a ridiculous amount of steps to accomplish a simple task. Imagine a button that increase a number by one, implemented by creating a request to a dispatcher, which will dispatches is according to a dispatching policy which is requested from an AbstractDispatchSettingsFacade, which makes the dispatching happen on a cloud server, etc... etc... (you will see all the time at work)
* Yak Shaving : a seemingly useless task that still has some excuse to contributing to the end product, no matter how far-fetched. For example : I'm automating the installation of a specific python version on development machines, because we need that for the automation of the installation of the test framework. Otherwise, every 6 months, everyone has to update manually. The team is 2 developers, and I've been doing this for 3 weeks.