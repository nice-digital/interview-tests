# Interview Technical Assignment - Stemming/frequency

## Background

As part of the interview/procurement process, we require all candidates to undertake a technical test so that we can assess your technical abilities.

Your solution will be assessed before the interview but will also form part of the interview process. You'll be asked questions about your solution and the decisions you've made.

Submit your solutions via email as a zip file (please add '.test' to the extension of the file so that it can get past email server filters, for example: *stemming.zip.test*).

## The test

At NICE Digital Services, we use Elasticsearch. Elasticsearch indexes content to provide relevant search results for a query. One aspect of indexing is stemming. Stemming is the process for reducing inflected (or sometimes derived) words to their stem, base or root form. For example the stemmed form of 'classes' is 'class'.

Please write code that processes the [input text](#input-tect) to determine the frequency of the stemmed words given in the [acceptance criteria](#acceptance-criteria). Your solution should cope with other input texts containing those terms.

### Input text

*Friends are friendlier friendlies that are friendly and classify the friendly classification class. Flowery flowers flow through following the flower flows.*

### Acceptance criteria

- frequency("following") = 1
- frequency("flow") = 2
- frequency("classification") = 1
- frequency("class") = 1
- frequency("flower") = 3
- frequency("friend") = 4
- frequency("friendly") = 4
- frequency("classes") = 1

### Instructions

- Don't use stemming libraries
- implement a solution in .NET and C#
- prove your solution meets the acceptance criteria.