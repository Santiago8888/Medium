Principles of Software Pathology

------------------------------------------------------------------------------

How do you measure the health of a Software System?
When you have pain and go to a doctor, you'll be given an answer.
And possibly some medicaments or treatment recomendations.
Besides, the doctor will explain what disease you have, syntomps and possible consequences.

But what happens in Software Engineering? 
There is no lexicon to explain the status of the system.
Recommendations are often subjective, based on experience.
And there are no analysis to make a precise diagnosis.
And treatments is often reduced to a refactor.

My goal in this post, is to explain how Pathology, the study of suffering 
is studied in Medicine. By analogy, my hope is to have at the end of the post
a glimpse of how a scientific approach to Software Development might look.

The post will be based on the classic textbook Robbins' Principles of Pathology 10th edition.
The book is used across multiple universities, and is often an elementary step of a doctor's education. It is also used by the GEMS MIT speciality tailored to students foreign to the medical industry that need an introduction to the subject.

In the post, I will explain what health is from a medical point of view and how it can be translated to Software. How the cells in the body get injured, and either recover or die. I will speak about aging, genetic diseases, the immune system and the primary causes of disease in the human body: failure to adapt. I will also speak about the ciruculatory system which has the mission to bring nutrients and oxigen to the rest of the cells. Serious diseases are often a symptom of an underlying failure in the circulatory system. Finally, I will speak about inflamation the prefered choice for the body to self-heal a part of the body.

Most importantly, in this essay I will talk about Software Engineering. How can we understand health in a system, how to build and measure resillency, and ability to adapt. How to monitor it, and develop static code analysis to overviwew in a glimpse a whole system. Finally I will talk about the steps that Software Engineering needs to take to have a comprehensive understanding of how to build and develop robust systems.

Medicine has gone a long way, extending the expected life and dramatically reducing child mortality. More importanly, quality of life has significantly gotten better and there are cheap remedies to treat common diseases. New diseases, are studied, analyzed and cured or prevented with vaccines. And there is Hypocratical oat that brings a common level of ethic among practicioners.

------------------------------------------------------------------------------
 
Table of Contents:

1. Previous Work.
2. Health in the human body.
3. Celular Injury, death and disease.
4. Inflamation a self-healing mechanism.
5. Hearth & Circulation.
6. Genetic Disorders.
7. The inmmune system.
8. Cancer


------------------------------------------------------------------------------

Pathos is Greek for suffering. 
And in medicine, pathology is the study of the causes and effects of disease or injury. 

As a Software developer I learn the arts of clean code including KISS, DRY and SOLID.
While learning my favorite was the Zen of Python, succint and beautiful.
And as I moved to AWS I learned the 5 pillar of a well-architected framework.

But today, I'm no longer a developer. 
My job is not to develop new features, nor mantain a system.
I'm a Software the kind of guy you call when things are not working anymore.
Maybe new development has stalled, or bugs are appearing more often.
Regardless, there is always a deeper cause and is my job to find what.

For a couple of years, I've been searching for a taxonomy to classify systems.
Not having found one in Software I looked into other areas to find a blueprint
to later translate. 
My first instinct was to look in architecture, 
after all the name is already implied in Software Architecture.
I wanted to understand how different architectural styles are classified.
And different constructions are appraised.

But I found little use in it, architecture is after all a fine art.
And most of the information I found was mnemonic, subjective and without a thread 
of logic to connect the distinct parts.

Last year, as I was studying self-healing systems I stumble on information of how 
the body self-heals. That got me thinking, I was searching for answers in the anals of human knowledge, while nature is often cited as wise, and the human the body as the perfect machine.

I got confirmation from that earlier when studying how vision works.
Interestingly, the architecture of a deep neural netowrk 
is not that different from how neurons are arranged from the retina to the optic nerve.
The same recongnized patterns start to emerge as with convolutional layers.


A second hint, that nature might provide the framework I was searching 
was when studying the distribution mechanisms of viruses.
Faszcintaing, effective and lethal viruses have perfected their infiltration and
replication techniques to million of years. 
I applied those learnings to creating viral go to market strategies.

And six months ago I was ready to start learning about medicine and apply 
it to diagnosing the health of Software systems. Except, there was a problem:
Doctors spend several years learning about medicine, how to absorb that knowledge quickly? I started at anatomy, but it also proved a mostly mnemonic excersice.

The answer came while learning about Machine Learning in healthcare at MIT.
They have a program called GEMS, for non-medical students that need rapid exposure to the industry.
And the first course is principles of pathology using the mythical Robbins textbook.
During the last 2 months I've been abosribing the informaton.
And here in so forth present to you my findings.

------------------------------------------------------------------------------

As I make the transition from Software Developer to Consultant
I face the following problem: how to objectively evaluate a code base in a short time.

Even as a neophyte, I have encountered wide variety of projects
from the ones very well-engineered, sophisticated and even difficult to understand.
To others absolutely rudemntary, even more difficult to understand.

As a consultant, the ideal experience I would like to offer my customers
is similar to a doctor's appointment, the customer reaches out to me
followig a set of questions, and perhaps some analysis
I'm able to determine the problem and suggest a treatment.

My niche is pre-seed startups where usually their main goal 
is to reduce the go-to market time and accelerate new features development.
Others, already have an MVP built and shown signs of product market fit and 
their goal is to bolster their platform to prepare to scale.

I specialize in AWS, DevOps. 

------------------------------------------------------------------------------

 

