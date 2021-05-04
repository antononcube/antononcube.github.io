# A method for developing computational conversational agents

## Introduction

During the last few years I worked on building software packages and conversational agents 
for computational workflows. Mostly for Machine Learning and Data Science, but also Scientific Computation.

The "computational" part is implemented using 
[R](https://www.r-project.org)
and
[Wolfram Language (WL)](https://www.wolfram.com/language/) 
(or
[Mathematica](https://www.wolfram.com/mathematica/).) 
Of course, implementations with other languages can be included, say, Julia or Python. 

The "conversational agent" part can be implemented using 
[Raku](https://raku.org),
[ANTLR](https://www.antlr.org),
[Scala Parser Combinators](https://github.com/scala/scala-parser-combinators),
or other similar systems.

The computational and conversational parts are equally important. 
Nevertheless, we can see the conversational part to be both 
"the start" and "the end" of the overall process:

- Computational specifications do occur in our heads through a certain "inner speech"
  
- Conversational interfaces to computations means the underlying computational systems 
  (programming languages and packages in them) are brought to a fairly advanced level of maturity.   

### Outline

In this document we describe a method for developing computational conversational agents
and the general strategy.

Here is the document outline:

1. The considered two types of users.
   
2. Overall design
   Describes the Overall design of the proposed method.
   
3. Monadic pipelines


## Two types of users

We have two types of users in mind and hence two types of Computational Conversational Agents (CCA).

- The **Developers**:
  - Want to jump start their software coding of a certain problem domain
  - Are sufficiently familiar with problem domain and want to be able 
    rapidly specify the generation of the programming code of related computational workflows
  - Want to be capable to generate the programming code 
    for different programming languages and related libraries
  - Are expected to want (and be able) to change, specialize, or refine 
    the programming code or results of CCA
  
- The **End users**:
  - Simply want to obtain the results of computational workflows by giving
    colloquial, not necessarily precise commands
  - Might have very limited understanding of CCA's problem domain 
  

## Overall design

The following diagram summarizes the Overall design:

![MoandicMakingOfMLCAs](https://github.com/antononcube/ConversationalAgents/raw/master/ConceptualDiagrams/Monadic-making-of-ML-conversational-agents.jpg)

Here is the description of the Overall design:

- We have decided to create a system that facilitates the rapid specifications of computational 
  workflows in a certain problem domain. 
  
  - Like, Latent Semantic Analysis (LSA), or food preparation.
    
- We brainstorm over the primary (and secondary) use cases and the available computational algorithms
  and methodologies.
  
- From the brainstorming process we derive and continuously refine two types grammars for 
  specification of computational workflows:
  
  - One type based on programming languages and related software packages or libraries
  
  - The other type is based on natural language specifications or commands 

- We program the computational part and endow it with a "monadic pipelines" interface.

- We develop a grammar for the natural language commands that can be used to specify the 
  computational workflows.
  
- We make a "single line interpreter" that translates natural language commands into 
  programming code.
  
- We further develop the "single line interpreter" to  

## Monadic pipelines

TBD...

## Domain specific languages

*Here is where Raku is used the most.*

TBD...

### Lower level

### Higher level

## Complete conversational agents

TBD...

## Connection to other projects

### Raku for prediction

### Simplified Machine Learning Workflows

The book 
["Simplified Machine Learning Workflows"](https://github.com/antononcube/SimplifiedMachineLearningWorkflows-book),
[AAr2],
describes the software monads and natural language commands of CCA's for Machine Learning and
Data Science workflows.

## References

### Articles

[AA1] Anton Antonov,
[Creating and programming domain specific languages](https://mathematicaforprediction.wordpress.com/2016/03/22/creating-and-programming-dsls/),
(2016),
[MathematicaForPrediction at WordPress](https://mathematicaforprediction.wordpress.com).

### Repositories

[AAr1] Anton Antonov,
["ConversationalAgents"](https://github.com/antononcube/ConversationalAgents),
[GitHub/antononcube].

[AAr2] Anton Antonov,
["Simplified Machine Learning Workflows"](https://github.com/antononcube/SimplifiedMachineLearningWorkflows-book),
[GitHub/antononcube].
