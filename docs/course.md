# Mobile applications

## Introduction

Welcome to the course! It doesn't matter if you chose it voluntarily, look forward to it, if it's part of your specialization and you ambivalent about it, or an exceptional set of circumstances forces you to take it. This course has been designed with 3 goals in mind:

* To learn about mobile development: it's specific technologies, usage context, and publishing model.
* To do this in a general way, so we learn how to figure this out on your own for eg. VR applications.
* To practice several soft skills : writing a pitch, presenting a project, and writing a report.

The reasoning behind it is simple. There's not that much to teach about mobile applications, so a project based course seems obvious. Even then, 6 credits is a lot, so we added practicing soft skills. This is not an arbitrary decision. In the industry, mobile applications are developed in a small team (less than 10 programmers), and it's important that you can propose and defend features and improvement. This is also generally true in the domain of digital experiences, where programmers are expected to discuss directly with artists and designers.

An additional motivation was direct feedback from interns about what is missing from the entire degree. If you're surprised to find things like code quality in this course, it's because it is a bridge to your internship.

In short, I hope that you will learn a lot of things in this course. Perhaps a bit of specific mobile technologies, but, above all, general skills applicable to wherever you will end up later. Good luck, have fun!

## Evaluation

Evaluation of this course is a bit complicated, as you will be graded on 4 separate things:

1. Your pitch
2. Your presentation
3. Your report 
4. Your defense

This might be confusing, as the app you've made doesn't seem to be covered by any of these. Don't be fooled. All of these evaluations are testing whether you've thought about the application you're going to / have been implementing. The reasoning behind evaluating like this is simple: if you are employed as a mobile developer, you will almost always have no more than a handful of technical (programming) colleagues, or even none at all. This means that you would interface with non-technical people a lot, which means explaining the work you have, or are going to do. While you've already have learned some of these skills in another course, this time you will propose/defend the work you have actually done / will actually do. 

### Pitch

You will write a pitch document for your app. A pitch is basically a proposal for something that needs to be made, and it aims to receive approval or funding. A common pitch is the "elevator pitch". This is a 30 second talk, meant to sell an idea for an app. Basically, you're trying to convince someone that your idea is good, often with the idea that it's worth investing in. Another would be a "statement of work", which propose any kind of work done by one company for another. This can be several pages, or several hundreds of pages.
The proposal you will write lies somewhere at the short end. The minimum is one full page (A4). The limit of length would be 2 A4 pages. Your proposal should contain the following sections:

#### Description

A short description of your app, one or two paragraph, and one or several images if they can clarify. eg

"Our app is a Tinder-like for internships, Internder. The profile pictures are replaced with logo's of technologies, picture of the city it is in, the manager, the office, etc... There is no "match", but students can export a list of the internships they're interested in. The idea is a fun way to narrow down the list of potential places to apply for."

For the images, you can screenshot Tinder, and manually paste over your images / text. It doesn't need to look good, it needs to get the idea across. Of course you're allowed to have fun with it :)

#### Inspiration

A longer section where you look at other existing apps, and compare features of your app to existing implementations. It's important that you go into detail why the feature works, it's not just pointing and saying "that". For example:

"We looked at tinder a lot for our basic interactions. In tinder, someone swipes left to reject someone, and right to express interest. We do the same: if someone swipes left on an internship, it means they're not interested, and the spot will never be seen again. If someone swipes right, it's added to a list of potentially interesting spots. We chose to do this, as it's proven to be fun, works as a 10-second interaction, and solves the problem of the old excel list being boring"

No need to be too detailed in your feature, the next section is a better spot for that.

#### Statement of work 

A longer section, where you detail the features you want to implement, as well as non-feature work you want to do (eg build server). You don't need to go in detail on each feature, but you do need a lot. Ideally, aim for double what you think you can realistically implement. If you have trouble coming up with a big enough list, try to imagine the most over-engineered, gold-plated Rube-Goldberg machine with all of it's yaks shaved. You don't need to implement all of them. You will split up this list into two parts:

The "need to have" list. These are features that need to be present for your app to be usable at all. This is called the "minimum viable product", or mvp for short.

The "nice to have" list. These are features that don't have to be in your app to be usable, but would make it better.

TODO refer to implementation section

Just a quick note : need to have and nice to have are unrelated to the scope of your project. I will go more into details on how much you should implement in another section.

#### Risks

You have to write a list of risks. These are things you know might turn out to be a problem. Typical examples are "I don't if this feature is possible in this framework", "This feature might not be a good user experience, as I haven't implemented it yet". Less typical, but equally good are "I'm a procrastinator, and I know I will be tempted to start a week before it's due." While this might seem pointless 

## Glossary


* Procrastinator  : someone who puts off all tasks until the last minute, or even longer. This can be something as short as sending an email (DN my record is 3 years), or starting to studying / working an entire course a day before the exam. If this is you, please read [This comic](https://waitbutwhy.com/2013/10/why-procrastinators-procrastinate.html). 
* Procrastinator / Procrastinator : iemand die alles uitstelt tot de laatste minuut, of zelfs langer. Dit kan iets kort zijn zoals het sturen van een email (DN mijn record is 3 jaar), of beginnen met studeren / werken aan een volledig vak een dag voor het examen. Als je je hierin herkent, kan je best [deze cartoon](https://waitbutwhy.com/2013/10/why-procrastinators-procrastinate.html) lezen.
* [Rube Goldberg machine](https://en.wikipedia.org/wiki/Rube_Goldberg_machine) : In the context of software development, an algorithm that does a ridiculous amount of steps to accomplish a simple task. Imagine a button that increase a number by one, implemented by creating a request to a dispatcher, which will dispatches is according to a dispatching policy which is requested from an AbstractDispatchSettingsFacade, which makes the dispatching happen on a cloud server, etc... etc... (DN you will see all the time at work)
* [Rube Goldberg machine](https://en.wikipedia.org/wiki/Rube_Goldberg_machine) : In de context van software development, een algorithm die belachelijk veel stappen nodig heeft om iets simpels te bereiken. Bijvoorbeeld een knop dat 1 optelt bij een getal, geimplementeerd door een request aan een dispatcher te creeren, die dat gaat dispatchen volgens een dispatching policy die gehaald wordt van een AbstractDispatchSettingsFacade, die de dispatching laat gebeuren op een cloud server, etc... etc... (DN je zal dit heel veel zien op je job)
* Yak Shaving : a seemingly useless task that still has some excuse to contributing to the end product, no matter how far-fetched. For example : I'm automating the installation of a specific python version on development machines, because we need that for the automation of the installation of the test framework. Otherwise, every 6 months, everyone has to update manually. The team is 2 developers, and I've been doing this for 3 weeks.
* Yak Shaving : een ogenschijnlijk onnutige taak die waar toch een reden is dat toch bijdraagt tot het eindresultaat, ongeacht hoe absurd de logica is. Bijvoorbeeld : Ik automatiseer het installeren van een specifieke python versie op computers van het programmeursteam, want we moeten dat hebben voor het automatiseren van de installatie van het test framework. Anders moeten we om de 6 maanden manueel updaten. We zijn met 2 developers, en ik ben er al 3 weken mee bezig. 