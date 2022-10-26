# Interview Technical Assignment - Stemming/frequency

## Background

As part of the interview/procurement process, we require all candidates to undertake a technical test so that we can assess your technical abilities.

Your solution will be assessed before the interview but will also form part of the interview process. You'll be asked questions about your solution and the decisions you've made.

- provide your solution in either **C#** or **Javascript (nodejs)**
- this test helps us to assess
  - your knowledge of a programming language
  - your knowledge of software design principles
  - your knowledge of test driven development
- we expect you to submit what you believe is “production-quality” code that you would be able to run, maintain and evolve
- you don’t need to “gold plate” your solution, but we are looking for something more than a bare-bones algorithm - we suggest spending a couple of hours.

Submit your solutions via a github repo that is shared directly with the recruiting team

## The test

At NICE Digital Services, we use Elasticsearch. Elasticsearch indexes content to provide relevant search results for a query. One aspect of indexing is stemming. Stemming is the process for reducing inflected (or sometimes derived) words to their stem, base or root form. For example the stemmed form of 'classes' is 'class'.

Please write code that processes the some input text to determine the frequency of the stemmed words within it.  Please see the acceptance criteria below. Your solution should cope with other input texts containing those terms.


### Acceptance criteria

#### Input text

*"Friends are friendlier friendlies that are friendly and classify the friendly classification class. Flowery flowers flow through following the flower flows."*

Given the input text above, when asked for the following words, return the associated frequency count of the stem of the word as specified below

| Word             | Frequency |
|------------------|---------- |
| "following"      | 1         |
| "flow"           | 2         |
| "classification" | 3         |
| "class"          | 3         |
| "flower"         | 3         |
| "friend"         | 5         |
| "friendly"       | 5         |
| "classes"        | 3         |

### Instructions

- Don't use stemming libraries
- prove your solution meets the acceptance criteria.
