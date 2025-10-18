# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.
I missed this lab last month from an absence, however it was a good review on how to properly create minterms vs maxterms using kmaps.
Minterms are rather easy and straight foward, but Maxterms were a bit more complicated for me since you had to take whatever made 0 and negate it.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
This is due to the way the Kmap is designed, it really is more like a map of the earth, where going off the edge will just loop you back around.
### Why are the names Sum of Products and Products of Sums?
Sum of Products comes from how Minterms are designed, where it is a bunch of ORs of ANDs like (A.B) + (A.~C).
Product of Sums is the opposite, made from Max Terms, a bunch of ANDs of ORs, like (~A+~C) * (A+B) 
### Open the test.v file – how are we able to check that the signals match using XOR?

