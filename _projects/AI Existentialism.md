---
title: 'AI Existentialism'
subtitle: 'Using LSTMs that was trained on works of Kierkegaard, Nietzsche, Marx for the purpose of text-generation'
date: 2020-5-28
description: 'Using LSTMs that was trained on works of Kierkegaard, Nietzsche, Marx for the purpose of text-generation'
featured_image: '/images/AI Existentialism/friedrich-nietzsche-19.jpg'
---

![](/images/AI Existentialism/nietzsche_main.jpg)

<div style="text-align:center">
  <a href="https://github.com/Coldestadam/Existentialism-Text-Generation" class="button button--large">View Code Here</a>
</div>


# Project Goal:
In this course, we have learned how to create Statistical/ML models that use non-sequential data, such as images or variables for the use of regression tasks. These are considered non-sequential since the dataset presumes that each sample share no relationship in terms of time. Sequential data presumes that the samples are connected through time, and text is an example of this. An example is this sentence, “The doctor recommends to eat an apple a day.”, here we see that the verb ‘eat’ connects the subject ‘doctor’ and the object ‘apple’.

In this project, we explore sequential modeling more in-depth and how we can predict the next word from a sequence of words. For example, if the sequence is, “In this morning, I usually drink \_\_\_\_”, the model should predict ‘coffee’ or ‘tea’. I will gather great works from different authors and have the model learn from the text for the use of text generation.