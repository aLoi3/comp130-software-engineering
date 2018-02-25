# comp130-software-engineering

## How artificially intelligent agents can be improved in flexibility in a test-driven development?

## What programming paradigms are more suitable for artificially intelligent agents?

Throughout the last few centuries "computer" has become one of the most important technologies we have now.
Therefore, the field of engineering has become very powerful today.
Software engineering refers to the disciplined and scientific approach to developing advanced software.
The field has made a wide range of software that supports different systems and applications.
Such are artificially intelligent agents, which are going to be discussed in this paper.
Moreover, in this paper will be discussed what programming paradigms are better for this area.

An agent is anything that can perceive its environment through sensors and act through actuators depending on the environment.
This can be anything, starting from simple machines, such as thermostats (which are programmed to act depending on the conditions) to worms (which can learn a small repertoire of behaviour) to humans (which can learn very quickly).
And for humans sensors are ears, eyes and other organs and for actuators - it's hands, legs, voice and other.
In general, "*An agent's choice of action at any given instant can depend on the entire percept sequence observed to date, but not on anything it hasn't perceived*". (Russel and Norvig, p.34)
There are a few intelligent agents, some are simple and the others are more complex.
And each following is an improved version.
Improved versions are more adaptable and flexible agents.
By Stuart Russell and Peter Norvig, there are five classes that differ from their perceived intelligence and capability:
* Simple reflex agent.
* Model-based reflex agent.
* Goal-based agent.
* Utility-based agent.
* Learning agent.

**The simple reflex agent** follows the *condition-action rule*, which is described as - if condition then action.
This type of agents do not learn, rather they act depending on its environment.
Infinite looping for such agent is unavoidable.
**The model-based reflex agent** is more complex.
Rather than immediately reacting to its environment, it has a list of rules.
Even if there are hundreds of reactions to a given percept, the agent looks up at the list that programmers have already considered and then execute that reaction.
The only difference from the simple reflex agent is that the model-based reflex agent requires a program that is not connected to the environment.
**The goal-based agent** is very similar to the model-based agent.
This time it is further expanded the capabilities.
As the name says, it has a goal to aim for.
This allows the agent to look for the best outcome that best reaches its goal.
For this reason, search and planning are the subfields of artificial intelligence.
That's why it first considers different scenarios before acting.
**The utility-based agent** is more adaptive by adding a utility function.
Unlike the previous one, a utility-based agent has "happiness" to consider.
It compares how "happy" will the agent be for every outcome.
As the programmer cannot predict all possible outcome that our world can give, the given goals can help constantly reassess its situation.
It will make the agent learn through errors adding new ways of reaching the best possible outcome.
And finally for **the learning agent**, as the name speaks for itself, it can act in an unknown environment.
This type of agents has the "learning element", which improves the agent and the "performance element", which selects external actions.
This is kind of self-improving agent, which can solve problems and act depending on its environment even without the necessary knowledge.
