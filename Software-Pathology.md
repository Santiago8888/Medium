# Principles of Software Pathology
## Uncovering the path to the scientifc diagnosis of Software Systems

**Abstract:**


### 1. Introduction


### 2. Background


### 3. Eight Concepts to know about Medical Pathology

#### 3.1 The human body is the epitome of a well engineered system.
Futile is to attempt to describe the level of sophistication of the human body. But here are two example to give you an idea about it:

1) Each cell holds about 750MB of data in its DNA, about the same as a legacy CD.
We have about 1 trillion cells in our body, or close to a XXbyte of data.
That means that a single human stores the same amount of data as we collectively created as a society up to 20XX. Impressive!

2) Our brain has 100 billion neurons, that's about the same number of stars in our galaxy. Each neuron has on average 1,000 connections with other neurons. As a civilization, humankind has yet to reach 8 billion people, and on average the 2+ billion Facebook users have 300 "friends". Arguably, our the brain is a network more complex that our society as a whole by a factor of at least 25x.

That is why as a Software Engineer, I approach the study and appreciation of the human body with humbleness. My understanding is that every problem worth solving has already been solved by nature as first explained in The Viral Startup.


#### 3.2 Cells are the basis of human health.

A symptomatic disease in the human body is the result of many individual cells. In retrospect, this is obvious but when I first learned the concept it was not. 

In Software this can be applied to understand that technical debt is the result of many poorly desigend individual functions acting together.

Adopting the function as a minimal unit of Software Health analysis enables us to define concepts as "homeostasis" or "steady state" to empircally determine the characteristics of how a healthy function looks and consequently the health of a Software System. Some hints as to how this would look include:

* The number of lines code, variables (internal state), and even tokens or characters.
* How clear the function and its variables are named.
* The number of input parameters and return types.
* Ciclomatic complexity (dependencies). 
* The number of conditionals and iterations or recursions called.
* How well errors and exceptions are handled.
* The number of times and diversity of how the function is invoked.


#### 3.3 Cells die due to injury, failure to adapt or age.

The first interesting concept is aging, cells are programmed to die. But hardly think of functions that way, we like to believe they will be used forever. Imagine if a function would be programmed to deprecate? And include in the comments when the function was created, and how long is expected to endure. One year? Three? Or maybe only some months.

Even more intersting are the types of cell death. Cells reproduce by mitosis splitting by half creating two distinct new cells. A single cell can die, but also a cell can stop to reproduce, this happens after about 22 times it has reproduced. Could we in software start tracking the number of times a cell is modified and deprecate it once it reaches a certain limit?

We are still far to think about stem cells that have the ability to shape and differentiate into every type of cell in the human body. But I do envision having a repository of template stem functions classified by what they do. In that sense Software developers would only clone them and adapt them to their needs.

***

The second interesting concept is that of failure to adapt. Think of it: how many Software projects have failed due to failure to adapt to market conditions? It's not that different for cells that experience external shocks due to exogenous conditions like lack of oxigen, changes in temperature or pathogen (virus, bacteria, etc).

This leads me to think that Software development is a human activity unlikel every other done in the past. Consider an artist: a painter, sculptour or even architect once their work is finished it's over; they don't need to account for changes in external conditions or even how art will be valued in the future.

The same happens to certain extent with more traditional branches of engineering like civil, chemistry or aeronautical that while facing external conditions they are usually known or planned before-hand. Even scientists, that aim to formulate theories mostly assume the invariability of the laws that govern the they try to understand.

Software is a science of change, and ability to adapt as experienced by different species in nature during their evolution. The only human activities that to my knowledge experience such an uncertain environment are social sciences and business in their continious attempt to predict and adapt to what the future brings.

In my opinion, we need a new word to capture the complex relation that Software (creators) exhibit with change.


#### 3.4 Inflamation is the mechanism for cells to heal.

When you cut and blood the skin turns redder as it heals. During flu, you cough and get fever as the body fights the virus. Both are symptoms of inflamation the mechanism to bring extra blood (white blood cells - leukocytes) to the damaged area.

How does healing ocurrs in a Software system? This is also done by bringing resources (developers) to the afflicted area. When the bug is found, and the soultion is pushed we also leave trails found in the history of Git. Curiously, the area is also stained in red as a fix usually involves more deleted lines of code that new development. There is a second sign of the fix and is the abscence of work in other areas. As more attention and resources are devoted to a bug, the overall productivity of a Software team falls.

As the science of Software Pathology is discovered, consultants, or Software Medics will use the Git history to diagnose which areas are in pain and need treatment. 


#### 3.5 Blood (or its lack of) is the biggest source of cell disease.

Everything that a cell has or needs is provisioned by blood. That is why cardiovascular diseases are the leading cause of deaths globally (18%). If a cell stops receiving oxigen and nutrients its health will deterioriate. That's partly why we excercise to keep the hearth healthy and strong and flux blood to the whole body.

The food of a function is data, if data is low quality arriving with errors or too complex a function will suffer and data hygiene is one of the first steps to improve the health of system.

The circulatory system is immpresive in it's own right: it stretches more than 66,000 thousand miles, each cell carries more than 1 million molecules of blood and the heart pumps on average 2.5 billion times during a human life [1].

Speaking of the heart, software systems also have one: the database. How data is queried and fetched is the first step of determining the health of a the Software's circulatory system.

A software consultant can start by mapping how data is flowing to find the potential causes of technical debt.


#### 3.6 A surprinsingly number of diseases can be attributed to genes.

Before my research I used to consider genes as static, highly reliable compnents exhibiting a low degree of variance. However, almost 70% of humans suffer from a disease attributed to genetic disorders.

The concept of genetics is foreign and difficult to translate to Software. Fortunately, through my experience I've participated and initiated a fair ammount of Software projects. And I could argue that a portion of those projects where doomed from the begining, a majority of which due to business reasons. After several iterations, these projects have accumulated so much technical debt that is impossible to develop new features. Others, because of poor technical decisions may be better to start them from scratch.

When developing software we hardly stop to think of the history of a project but it is often the case that the people behind a project are often more rigid than the source code itself. And there is a whole set of unexplored maladies that involve the interaction between software development and stackholders or team members. Either because a key member left, a difference in vision or the lack of agile frameworks to guide the project when evaluation the health of a Software project is not enough to consider code.


#### 3.7 We have an inmune system to heal ourselves.

Self-healing systems have been increasingly part of the the SREs toolbox, with complex canary configurations in Kubernetes clusters. A predominant acceptance on the benefits of testing and the automation of code reviews and other Git workflows the concept of an inmune system in Software is closer to reality that we might think.

The next step is learning from how it works in the human body. The inmune system is divided in 2: innate and adaptative. The innate has learned from diseases and pathogens that have accompanied us during our evolution. The adaptative, on the contrary, learns only from the comparatively short period of time that comprises our lives and sometimes that of our close ancestors.



#### 3.8 Histology is the study of tissues or how cell are connected.



### 4. Case Study: Diagnose the health of a React Application

#### 4.1 Measure the health of React Components.


#### 4.2 Map the flow of data through components.


#### 4.3 Review the short term history of Git commits.


#### 4.4 Classify the encountered pathologies.


#### 4.5 Recommend a treatment.


### 5. Next Steps: Turning Software Pathology into a Science


### 6. Conclusion


### 7. Bibliography


