---
layout: post
title: Why reflective services?
description: Looking at the background to how reflective practice might work in service delivery
summary: ...
tags: service-design reflective-practice
minute: 1
---

> "I have said that poetry is the spontaneous overflow of powerful feelings: it takes its origin from **emotion recollected in tranquility**."
> – William Wordsworth, Lyrical Ballads (1798-1800), Preface.

The idea of turning the events of the day into something new was first put to me by an English teacher who explained that Wordsworth's modus operandi was to go for a solitary wander (_lonely as a cloud..._) and then latest revisit the experience in memory - using the prism of hindsight to translate feelings into words, words into poems, and poems back into feelings. This is not so much _feedback_ as _feedforward_, and Wordsworth was actively experiencing, reflecting and writing about nature. This might make him an early example of a reflective practitioner using recollections to develop craft.

> "despite  being  born  with  cognitive potential,  humans  do  not  arrive  with either pre-installed empirical knowledge or methodological rules. Neither do we acquire knowledge ready-formed or pre-packaged by directly perceiving it. On the whole, knowledge, our criteria and methods for knowing it, and the disciplines to which this knowledge contributes are constructed" - Light and Cox, Learning and teaching in higher education: The reflective professional, (2001)

Fast forward twenty years and whilst working as a teacher, I was given a book that applied what seems a similar idea to the pratice of honing the skills of an educator. In the book, the writers make the case that a good way to develop as a professional teacher is to use reflection to develop the practice of teaching by actively logging and considering what the events of the day mean for the future, so that when similar or related events happen again, a sound association is made with prior experience, making the new event as well-prepared-for as it can be.

> "&hellip;from the perspective of technical rationality, professional practice is a process of _problem solving_. Problems of choice or decision are solved through the selection, from available means, of the one best suited to established ends. But with this emphasis on problem solving, we ignore problem _setting,_ the process by which we define the decision to be made, the ends to be achieved, the means which may be chosen....When we set the problem, we select what we will treat as the "things" of the situation, we set the boundaries of our attention to it and we impose upon it a coherence which allows us to say what is wrong and in what directions the situation needs to be changed. Problem setting is a process in which, interactively, we _name_ the things to which we will attend and *frame* the context in which we will attend to them." - Schon, D., The Reflective Practitioner, (1983)

| Experience            | Reflection           | Learning                                   |
| --------------------- | -------------------- | ------------------------------------------ |
| What?                 | So what?             | Now what?                                  |
| Description of events | Unpicking the events | What has been learned? What is the impact? |


{% graphviz some title %}
digraph {
bgcolor="#131418"
node [color="whitesmoke", fontcolor="whitesmoke"]
edge [color="whitesmoke"]
graph [fontcolor="whitesmoke"]
Action -> Reflection
{rank=same Learning -> Reflection [dir=back]}
Learning -> Action
}
{% endgraphviz %}
{% graphviz some title %}
digraph {
bgcolor="#131418"
node [color="whitesmoke", fontcolor="whitesmoke"]
edge [color="whitesmoke"]
graph [fontcolor="whitesmoke"]
What -> "So What"
{rank=same "Now what" -> "So What" [dir=back]}
"Now what" -> What
}
{% endgraphviz %}
{% graphviz some title %}
digraph {
bgcolor="#131418"
node [color="whitesmoke", fontcolor="whitesmoke"]
edge [color="whitesmoke"]
graph [fontcolor="whitesmoke"]
"Service Owner" -> "Data Scientist"
{rank=same "Service Designer" -> "Data Scientist" [dir=back]}
"Service Designer" -> "Service Owner"
}
{% endgraphviz %}
{% graphviz some title %}
digraph {
bgcolor="#131418"
node [color="whitesmoke", fontcolor="whitesmoke"]
edge [color="whitesmoke"]
graph [fontcolor="whitesmoke"]
"Act" -> "Review"
{rank=same "Plan" -> "Review" [dir=back]}
"Plan" -> "Act"
}
{% endgraphviz %}
{% graphviz some title %}
digraph {
bgcolor="#131418"
node [color="whitesmoke", fontcolor="whitesmoke"]
edge [color="whitesmoke"]
graph [fontcolor="whitesmoke"]
{"concrete experience" -> "testing implications of concepts in new situation" [dir=back]}
{"testing implications of concepts in new situation" -> "formation of abstract concepts and generalisations" [dir=back]}
{"formation of abstract concepts and generalisations" -> "observations and reflections" [dir=back]}
{"observations and reflections" -> "concrete experience" [dir=back]}
{ rank=same; "testing implications of concepts in new situation"; "observations and reflections"; }
label = "kolb 1984"
}
{% endgraphviz %}
