# Fact_checker_Research_tryout
primitive fact checker model


This is a primitive fact checker model that I implemented in python, using the fever AI model

Fact Checking [Coding]
The goal here is to do fact checking (e.g., is a random Tweet you saw on the Internet true) in a fun and easy to validate setting.

0.  Check out relevant literature such as: https://blender.cs.illinois.edu/paper/factualerrorcorrection2023.pdf

1.  Download a model that can do the Fever task:
https://fever.ai/

2.  Make sure you can get from it the label (we mostly care about
supported or refuted), the evidence, and the confidence.

3.  Run examples from the um actually game show through it:
https://um-actually.fandom.com/wiki/Um_Actually_Episodes

This is a little different from the normal FEVER task, where you get a whole claim.  In this game, you get it one word at a time (or you can simplify it by getting K words at a time) and you need to decide *when* to declare a statement false.

So run it on each sentence in the input claim and select which one has the highest probability of being the false claim.

What to submit: Show your results on some examples.  

How this would translate into a full project: We’d build a system that could do this in real time, in the hopes of getting it on the Um, Actually web show (we have been in contact with them).
