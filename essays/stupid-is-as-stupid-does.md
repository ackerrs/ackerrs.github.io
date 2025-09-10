---
layout: essay
type: essay
title: "Stupid Is As Stupid Does"
# All dates must be YYYY-MM-DD format!
date: 2025-09-09
published: true
labels:
  - Questions
  - Answers
  - Getting help
  - RTFM
---

"Cunningham's Law states 'the best way to get the right answer on the internet is not to ask a question; it's to post the wrong answer'" (Wikimedia, 2025)[[1]](#1). Generally, this is sound advice; it is particularly effective on "casual" sites such as Facebook or Reddit. One should note that there exists an exception to this law, however: technical questions that require specialized or intricate responses will be scorned by this tactic. Instead, for sites like Stack Overflow, answer seekers will be better served following the advice of Eric Raymond's *How to ask questions the smart way*[[3]](#3).

## Winning Friends and Influencing People

An excellent example of asking a question the smart way is a post by GManNickG[[2]](#2). They opened with a well defined question about processing sorted vs. unsorted arrays, presented operational code used to test the example and the resultant data, and lastly posted links to related information. These are all important qualities that will draw the attention of qualified responses.

By establishing a definite problem in the title, other users who have knowledge on the subject will readily identify an opportunity to demonstrate their skills. These users are likely already lurking the forum for the purpose of answering questions: make it easy for them to find you.

By posting code that can be used to test the problem, GManNickG has enabled anyone to look at the problem first hand. This demonstrates the problem is real, the author has invested time into trying to solve the dilemma themself, and gives potential subject matter experts a basis from which to explain why the behavior exists.

By including links to relevant, but not identical, issues the author has demonstrated an attempt at researching the answer and some capacity for identifying some of the answer without fully comprehending the solution. Responders are more likely to provide solutions to people who are more interested in the comprehensive learning than a rote answer they'll likely forget within days.

The result of this approach is many detailed answers that walk readers through the basics of branch prediction, modern computing, and even a how-to on rewriting conditionals to use the relatively simple nature of bitwise operations to optimize performance across any type of array (for the problem stated). Furthermore, the clearly stated problem will result in future users having similar problems being able to quickly find the thread and benefit.

## Death of a Luser

In counterpoint, Gan Uesli Starling[[4]](#4) asks a question that fails the sniff test. Even after modification, the title asks how to convert decimal to hexadecimal: this is an extremely basic operation that any amount of research would have presented many solutions. It could additionally benefit from being formatted in the "object-deviation" style that Raymond recommends, although that would first require Starling to have presented an actual problem.

Another reason to reformat the title is the realization that the post does not explicitly state an issue. There is an *implication* of an issue with the conversion, but the author has not demonstrated any attempt at implementation, troubleshooting, or even that the problem actually exists: it reads more as "Write my code for me" than "Help me fix my code." Paired with the statement that Starling does not want to rely on existing libraries, this seems contrary to the proclaimed objecting of "doing it all by [themself], without relying on other libraries" (Starling, 2025)[[4]](#4).

There are many other details to pick at, but the result of this poorly executed thread is two responses. Neither of these presents an answer, and the entire thread has been closed for need of details or clarity. Starling is left without a solution, entirely because he asked a question as a "luser."

## Obtaining Enlightenment

As a 36 year old denizen of the internet and veteran, very little of this information was revelatory. Stupid questions absolutely exist, and stupid answers usually follow close behind. These lessons are not restricted to software engineering, of course. In every situation that requires a solution, the first step is to identify your problem. Look at your symptoms, and find the fewest problems (preferably one) that could cause them.

Once you have identified your problem(s), take tests halfway between the start and end of the possible problem area to quickly isolate the issue. As (presumably) a person familiar with software engineering, you should be familiar with binary searches and why they are valuable at saving time! During these tests remember "Garbage In, Garbage Out." If the inputs are bad, the outputs certainly are as well.

With the problem isolated, research solutions. This can be manuals, internet searches, colleagues, subject matter experts, the list goes on. Only once these resources have been exhausted and the problem is still not resolved should the problem be posted. By then, you have accumulated a detailed understanding of where the problem exists, what the symptoms are, and can intelligently answer any followup questions other users will present.

With these steps, you too can obtain enlightenment -- until the next bug appears, anyway.

## Works Cited

<a id="1">[1]</a> 
Contributors to Wikimedia projects. (2025, June 14).
*Cunningham's Law*.
Wikimedia Foundation, Inc.
[https://meta.wikimedia.org/wiki/Cunningham%27s_Law](https://meta.wikimedia.org/wiki/Cunningham%27s_Law)

<a id="2">[2]</a> 
GManNickG. (2012, June 27).
*Why is processing a sorted array faster than processing an unsorted array?* [Online forum post].
Stack Overflow.
[https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array)

<a id="3">[3]</a> 
Raymond, E. S. (2014, May 21).
*How to Ask Questions The Smart Way*.
[http://www.catb.org/esr/faqs/smart-questions.html#before](http://www.catb.org/esr/faqs/smart-questions.html#before)

<a id="4">[4]</a> 
Starling, G. U. (2025, September 9).
*How to convert an arbitrary large integer from base 10 to base 16 in Forth? [closed]* [Online forum post].
Stack Overflow.
[https://stackoverflow.com/questions/79759119/how-to-convert-an-arbitrary-large-integer-from-base-10-to-base-16-in-forth](https://stackoverflow.com/questions/79759119/how-to-convert-an-arbitrary-large-integer-from-base-10-to-base-16-in-forth)
