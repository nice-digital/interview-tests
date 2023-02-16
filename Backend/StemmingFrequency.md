# Technical Assignment - Stemming/frequency

## Background

As part of the interview/procurement process, we require all candidates to undertake a technical test so that we can assess your technical abilities.

Your solution will be assessed before the interview but will also form part of the interview process. You'll be asked questions about your solution and the decisions you've made.

- this test helps us to assess:
  - your knowledge of a programming language
  - your knowledge of good software design 
  - your knowledge of test driven development
- we expect you to submit what you believe is production-quality code that you would be able to run, maintain and evolve
- we suggest spending no more than two hours on your solution.  If you struggle to finish in the suggested timeframe, please just submit what you have done so far, as this might still be enough code to get an impression of your skills.

Please submit your solution by emailing our recruitment team a link to your solution hosted in a web-based version control system of your choice (we use GitHub and recommend that, but others are fine)

## The test

At NICE Digital, we use Elasticsearch to provide text-based search on our website content. Elasticsearch indexes text-based content to provide relevant search results for a query. One aspect of indexing is called stemming.  Word stemming is the process for reducing more complex words to their stem. For example the stemmed form of the word 'classes' is 'class'.

Please write code that processes input text containing words to determine the frequency of the stemmed words within it.  Please see the acceptance criteria below. Your solution should cope with other input texts containing those terms.


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
