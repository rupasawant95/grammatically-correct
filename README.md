# grammatically-correction

Correction of grammar of input sentence

# Formulation of the problem:

The problem is a sequence to sequence problem. Given an input sequence the model learns the probability of occurrence of the output sequence. For this task, the input sequence is a grammatically incorrect sequence and the output is the grammatically correct version of it.

As a starting point, we define the kinds of errors we aim to solve. a. What does the model have to do? Predict the grammatically correct version of the grammatically incorrect text which was given as input; produce the unchanged text as output if the input text is grammatically correct b. What is the ideal outcome? The ideal outcome is that once we figure out if the errors we are targeting is learned properly by the model, we can use our resources to target more errors, so we can finally on a long term target most common errors. c. What output should the model produce? A sequence of most probable words learned by the model.

# Business Constraints:

We want the system to have high precision and prefer the system predict correctly rather than predict incorrect predictions.

Low latency is always preferred.

Also, since the problem involves taking a grammatically incorrect text as input, when deployed on a server we want optimized handling of input data with low computational resources and power preferably.

Output URL link - https://18179.gradio.app

Output video link - 
