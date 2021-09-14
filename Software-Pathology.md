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

Probably the next step in self-healing systems would be preventing problems before the systems arrive. This can happen as soon as we are developing. By establishing the rules of what comprises quality Software (an evolution from linting), and possibly with the aid of AI technilogy as GitHub's co-pilot I can imagine the Software integritity being defended from their most harmful intruders: Software Developers.

While entering the realm of speculation, a protective system can go as far as task definition on project management Software. If BDD practices are well adopted and user stories are defined according to them, this is by no means an impossible task to imagine!


#### 3.8 Histology is the study of tissues or how cell are connected.

I just want to share how deep the science of medicine goes, and how far are we as Software Developers to turn our empirical knowledge into a structured, sharable understanding. After determinining that cells are the basis of health, and carefully classifying each type of cell based in their function on the human body. Doctors have also studied how cells are connected linking celular biology with anatomy and physiology.

How many times have you encountered a project that is a turmoil of functions? In the human body the connection between cells is tridimensional, but in Software it can get much more complicated: as a single dependency could be shared by the two farthest applications solving completely different problems.

Even more that understanding how histology works in detail my goal is to bring awarencess to how unconsciously do we produce Software as compared with other disciplines that have a milenary tradition. And that no matter how technologically our tools and fancy our solutions are, we can approach the consolidation of our science with awe and inspiration from those that have already faced and solved such problems.

We like to think that Software is complicated, and the ecosystem is vast full of different technologies, languages and providers but if compared with the vast creative power of evolution and the complex taxonomy that has originated in life sciences we are still early in our infancy and are no different to the Greeks and Aristotles attempting to order their world around them.



### 4. Case Study: Diagnose the health of a React Application

During the next lines, I want to imagine how the job of a consultant would look following the analogy of a doctor and a patient. And how is not entirely unlikely that in the near future just as the doctor has the possibility to request analysis to make informed decisions, our Software development process and communication with stackholders could be dramatically tranformed by using quantifiable metrics and aggregated data to make decisions.

For this hypotetical excersice I will use the opinionated architecture of a React Application because it follows a functional paradigm, with unidirectional flow of data and reusable components.


#### 4.1 Measure the health of React Components.

The first analysis a Software consultant (or Tech Lead) when approaching a new React application would be the relative health of components based on the rules highlighted on section 3.2, that include the length of a function (or component), the number of dependencies, error handling, etc. 

As an example consider the scc GitHub package that measures the lines of code, estimated cost and complexity for a project. Written in go, the package analyzes the source code in a matter of seconds. While doubters might be skeptical, an efficient measurement of the health of a component can be figured out by aggregating data from a plethora of components. The possibility to relate bug reports (or GitHub issues) to pull requests, compare and measure the development times across sections of the code and evaluating which parts are easier to onboard than others. We could, theoritically, train machine learning models to predict based on obeservable data how healthy or "injured" the overall source code is. While gaining precise insight of where the problems are.

The results could be obtained by CLI and sorted by health just as in the case of scc:

![Image of CLI]()


#### 4.2 Map the flow of data through components.

After figuring out how healthy individual components, ideally we would like to know how those components are related. I propose the traditional flow diagrams to map how data flows thorugh components. Like a river born in the midst of a mountain, React applications are pyramidal architectures where data flows downward.

![Diagram Flow]()

Using flow diagrams we could start to detect if some components are saturated, or if through some data needs to travel a long journey. We could also spot components that are reused several times and by implementing color system based on health we can learn if there are sections of the application that are severly harmed, or if the damage is evenly spread across the application. Different treatments and recommendations would apply for each case.


#### 4.3 Review the short term history of Git commits.

The final analysis I would ask is understanding where the attention and resources have been allocated during the most recent weeks. The chart I would propose is an area chart where different sections of the code would get a different color. Above the horizontal axis are the additions (as measured by lines), while below are the deletions.

![Time Chart]()


This analysis would bring me two pieces of information:
1. How productivity compares across different weeks (uniform, with spikes, declining, etc.)
2. Are there certain sections of the code that hoard resources?

You can start to see how many variations of these analysis could be performed to learn particular characteristics of the code. But now we get to the interesting part of consulting where creativity, experience and design matters.


#### 4.4 Classify the encountered pathologies.

Imagine the scenario of planning a new feature, or a system that is not performing as expected. Maybe the organization is contemplating a migration or they are evaluating a new member. Each of these scenarios present different options and there is not a solution that fits all. Before suggesting a treatment, a doctor first diagnosis the disease based on an array of well understood classes each one having distinctive symptoms, causes and affecting different patients.

The consultant in this scenario would need to classify the problem (or circumstnance) based on a predefined well known list of problems. However, as opposed to doctors we do not have that list so the best we could do is ennounce a diagnostic that could liik like:

* Feature specification  and expected outcomes are ambiguous.
* Shared dependencies are blocking new development.
* Insufficient monitoring infrastructure.


#### 4.5 Recommend a treatment.

Only when the problem is diagnosed can a treatment be proposed. If different stackholders agree on the problem finding the best solution is easier. Examples:

* Insufficient experience in front & back but there are only resources for one new hire: in that scenario a senior consultant could be hired while junior developers are trained. As a benefit the headcount would not increase in the long-term.
* A new feature is requested in a section where there is enough technical debt to disencourage development: maybe an alternative solution can be found to achieve the business outcome without involving the Software team. In that scenario, the team would in turn work on paying back the technical debt.
* Tasks usually take longer than expected: perhaps there is oportunity for automation, or better guidelines could be proposed for code reviews, or maybe revisiting scrum practices.

Ideally these treatments are based on data, just as medical treatments and new drugs are pushed. As software engineers we are used to apply logic to our problems, not understanding that we are dealing with probabilistic scenarios where cognitive bias are disguised as logical thoughts.


### 5. Next Steps: Turning Software Pathology into a Science

Medicine was not always scientifical, in the past doubtious remedies like bleeding or trepanation where used despite their limited efficiency, often worsening injuries. Medical theory was based on humours and elements, and closely tied to Alchemy and Astrology, treatments were based on induction instead of observation and the scientific method. Future Software scientistis would look in the same astonishment our artisictic crafting of Object Oriented Principles with the hope of stumbling the right architechture for an everchanging landscape.

Software development, a nascent science is not that different from medieval science fighting religously the Black Death. While sofisticated our software practices are no different, based on argumentation dialectics, power dynamics and mysticism. Hopefully, there is a solution and in with time and by destinating resources in 3 directions we might change the fate of Software, improve the success rate of projects and create a common understanding of our practice. Hence, following the analogy I present the 3 required directions:


#### 5.1 A lexicon of diseases

In biology, species are classified by family often using names derived from latin. This enables to communicate about them. However, in Software our lexicon to speak about problems is limited, we often we use terms interchangigly or the same term to refer to multiple problems. This creates communication problems, inefficiencies and lack of scientific rigour.

I often thought of the labor of classifying as boring and pointless but only when appreciating how important foundations truly are can I contemplate the activity in its full complexity. Today, classifying animals in vertebrates and invertebrates appears obvious also in their respective kingdoms: birds, mammals, insects, etc. But you have to wonder: how many iterations did those classifications went through to stumble into such precise classes? And how will a taxonomy of software would look like?

While the Principles of Software Pathology would only focus on the classification of maladies, this is by no means the only goal. And in fact, the taxonomy of diseases would need to be build from deeper foundations which correctly identify the components of a Software project in both terms: human and technological, as well as allocating room for constant innovation.


#### 5.2 An understanding of causality

Autopsies were a major breakthrough for medicine, this was because of the possibility to examine causes of death, learn anatomy and validate hypothesis. Today, it seems irrational that at some point they were perceived as sacrilagious yet today the same happens to Software. In favor of today sacred values like intelectual property, business interests or the pride of participants the process of analysing the causes of failure in software projects is left to the painstaking process of accumulating experience. And there is little possibility to compare, aggregate and discuss at a deep level our own experiences.


#### 5.3 A plethora of treatments

The science of causality is key to linking diagnostics with treatments.

### 6. Conclusion


### 7. Bibliography


