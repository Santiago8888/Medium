# Principles of Software Pathology

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




#### 3.4 Inflamation is the mechanism for cells to heal.


#### 3.5 Blood (or its lack of) is the biggest source of cell disease.


#### 3.6 A surprinsingly big number of diseases are attributed to genes.


#### 3.7 We have an inmune system to heal ourselves.


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


