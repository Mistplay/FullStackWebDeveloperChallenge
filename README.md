# Full Stack Web Developer Challenge
## Task Description
Your task for this challenge is to create a small search engine comprising of two parts, a web-based user interface and a server component that exposes a REST API which provides search results retrieved from a corpus of text that will be provided to you in `corpus/hemingway.txt`.

Your submission will be evaluated for conforming to the specifications outlined below as well as code quality (maintainability, scalability, performance etc.). You are permitted to use any resources and libraries you wish, however, you should be able to justify design choices in your code. We also encourage the usage of any automated AI tools you may want to use to augment your ability to code e.g. ChatGPT, Claude, etc.


## Requirements
The basic search engine should be capable of the following three operations.

1. Given a query consisting of a single word `w`, display the 3 most similar words in the search corpus according to some similarity metric of your choosing. You should return results even if `w` is not in the corpus.
2. Given a single word `x`, update the search corpus with `x`. The new word `x` should immediately be 
queryable.
3. Given a single word `y`, remove **_the most similar word_** to `y` in the corpus from further search results. 
### User Interface
The user interface should be a browser-based application developed using your JavaScript web framework of choice. It should support the three aforementioned operations. How this is done should follow the Figma outlined [here](https://www.figma.com/file/o9f9V0OM6i1Zdfu3dNTCIM/FSE-Test-UI?type=design&node-id=0-1).

### REST API
The REST API can be implemented using whatever language and frameworks of your choosing. Again, like the UI, it needs to support the three operations listed above. How you choose to accomplish this task is up to you.

## Deliverables
To submit your challenge, fork this repository and provide the link to your forked repository.
You should also update this README to include instructions on how to run your search engine.
Tests are not mandatory but will be considered bonus points if you provide them.

This challenge should take half a day to day at most (please do not over invest time in this as we will talk about the progress made in a subsequent interview). It is not expected to be a production ready application and thus will not be evaluated in such a context.
