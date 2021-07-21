# Multi-language Data Wrangling and Acquisition Conversational Agents
[Orlando Machine Learning and Data Science](https://www.meetup.com/Orlando-MLDS/events/278910791)   
2021-07-26   
Tutorial and software architecture presentation   

[This presentation](https://www.meetup.com/Orlando-MLDS/events/278910791), [AA1],
was a combination of 

1. A previous data wrangling presentation, [AAr1, AAv2]
2. New material on data acquisition, [AAr2, AAr3]

Compared to other presentations this one was much more software-architecture content.

Here is the mind-map used for the presentation:

[![OMLDS-Meetup-June-2021-mind-map](https://github.com/antononcube/antononcube.github.io/raw/master/MarkdownDocuments/Diagrams/OMLDS-Meetup-June-2021/OMLDS-June-2021-mind-map.png)](https://github.com/antononcube/antononcube.github.io/raw/master/MarkdownDocuments/Diagrams/OMLDS-Meetup-June-2021/OMLDS-June-2021-mind-map.pdf)

Here is the abstract:

> In this month's talk, Anton will be showcasing his work on 
> Multi-language Data Wrangling and Acquisition Conversational Agents. 
> Current data acquisition and wrangling methods require user knowledge in multiple packages and languages. 
> These agents address this knowledge gap by simplifying the process of building data acquisition and 
> data wrangling pipelines using natural language, enabling data scientists to quickly get a feel for their data 
> in a fast and language agnostic manner. 
> The talk comes with a number of references, including Anton's own repositories and 
> other talks he gave on the subject.

Here is a recording of the presentation at YouTube, [AAv1]:

- ["Multi-language Data Wrangling and Acquisition Conversational Agents"](https://youtu.be/8B4_mkU_XW0).

That video recording is long, over 2 hours. (The timings in the mind-map were very loosely followed...)

A few notes:

- I developed the presented Domain Specific Language (DSL) functionalities were developed with Raku.
  
- The Raku packages generate code for Julia, Python, R, Wolfram Language (WL).
 
   - And related packages in those programming languages.
  
- I implemented the discussed utilization of [ZeroMQ](https://zeromq.org) 
  a few weeks after the presentation, see [AA2, AAr4].

------

## References

### Articles, announcements

[AA1] Anton Antonov,
["Multi-language Data Wrangling and Acquisition Conversational Agents"](https://www.meetup.com/Orlando-MLDS/events/278910791),
(2021),
[Orland Machine Learning and Data Science Meetup](https://www.meetup.com/Orlando-MLDS).

[AA2] Anton Antonov,
["Raku Text::CodeProcessing](https://rakuforprediction.wordpress.com/2021/07/13/raku-textcodeprocessing/),
(2021),
[RakuForPrediction at WordPress](https://rakuforprediction.wordpress.com).

### Repositories

[AAr1] Anton Antonov,
[DSL::English::DataQueryWorkflows Raku package](https://github.com/antononcube/Raku-DSL-English-DataQueryWorkflows), 
(2020), 
[GitHub/antononcube](https://github.com/antononcube).

[AAr2] Anton Antonov,
[DSL::English::DataAcquisitionWorkflows Raku package](https://github.com/antononcube/Raku-DSL-English-DataAcquisitionWorkflows), 
(2021), 
[GitHub/antononcube](https://github.com/antononcube).

[AAr3] Anton Antonov,
["Data Acquirer"](https://github.com/antononcube/ConversationalAgents/tree/master/Projects/DataAcquirer), 
(2021), 
[ConversationalAgents at GitHub/antononcube](https://github.com/antononcube/ConversationalAgents).

[AAr4] Anton Antonov,
[Text::CodeProcessing Raku package](https://github.com/antononcube/Raku-Text-CodeProcessing), 
(2021), 
[GitHub/antononcube](https://github.com/antononcube).

### Video recordings

[AAv1] Anton Antonov,
["Multi-language Data Wrangling and Acquisition Conversational Agents"](https://www.youtube.com/watch?v=8B4_mkU_XW0),
(2021),
[OMLDS YouTube channel](https://www.youtube.com/channel/UCoTuN2KVQHpnAOO9nM9354Q).

[AAv2] Anton Antonov,
["Multi-language Data-Wrangling Conversational Agent"](https://www.youtube.com/watch?v=pQk5jwoMSxs),
(2020),
[Wolfram Technology Conference, 2020](https://www.wolfram.com/events/technology-conference/2020/).

[AAv3] Anton Antonov,
["Multi language Data Wrangling Translation - talk advertisement"](https://www.youtube.com/watch?v=OHY64ezgnm4), 
(2020), 
[Anton Antonov YouTube channel](https://www.youtube.com/channel/UC5qMPIsJeztfARXWdIw3Xzw).

[AAv4] Anton Antonov,
["How to simplify ML workflows specifications"](https://www.youtube.com/watch?v=b9Uu7gRF5KY), 
(2020), 
[R Consortium YouTube channel](https://www.youtube.com/channel/UC_R5smHVXRYGhZYDJsnXTwg).
