# Social Learning and Decision Making - relevance for voting mechanisms.

These notes have been inspired and mostly informed by the podcast from the series "Complexity: Physics of Life", [Mirta Galesic on social learning & decision-making](https://open.spotify.com/episode/7m3lEMqnkEDgZcKesiepcn?si=eVM78EcYRJ6Hfd9o6oRHDw&nd=1&dlsi=3e3854f7ea6b476f). I summarise some of the most interesting concepts, provide bibliography for the research and point out their relevance to the voting mechanism design, or governance in general. This is early draft, I plan to smooth it out later...


## Areas of relevance:

1. Voting **algorithm**
2. **Communication** related to voting
3. Interaction with the community more broadly
4. Which **values** should (ideally) be consistent with the voting mechanism
5. What functions should be fulfilled by the voting mechanism.
6. Understanding possible **behaviours**: motivations, biases etc.
7. **Analysing** the proposed mechanisms.


## Summary of the concepts / research.

### Impact of social networks on learning and decision making.

>  One of the main points from the podcast and from research by Prof Mirta Galesic is that the social network element impacts both learning and decision making, and especially the aspect related to bias, in a way that has been underappreciated or misunderstood by a lot of research. Further, Galesic conjectures that there are a lot of biases that are products of imperfect measurements, and that they go away after incorporating information about social networks.

One of the important pieces of research that Galesic refers to, is the one that shows that:
* People are very good at predicting preferences of their social circle, to the extent that the social circle question can predict election results better than asking about own voting intentions.
* While people have a good understanding of opinions of people from their social circle, this will not be the case for people outside of that social circle.
* People are less biassed when judging opinions from own social circles, but are more biassed when asked to make judgement about opinions of other circles, and the biases tend to be connected to what they know about those social circles.

Consequently: ***the more biased is the social network, the more biased will be the estimate for the whole population.*** These structures of social networks is what explains overall biases of judgement of the broader population, rather than some cognitive deficits of motivational biases. 

How can one **correct for this handicap**?
* People who have most diverse social networks are the most able to predict societal trends.
* Policy makers should have as big social networks as possible, they should include those people who are often not there.



### When smaller groups outperform bigger groups in decision making.

> What's the best way to approach a problem and decision-making if we don't know the complexity of the problem in advance?

Three elements to consider:
1. Rule used to make decision
2. Network structure, especially: how many diverse opinions are in the person’s network
3. Problem being solved.

Examples:

* If there is a simple problem, it might be the best to use a simple decision rule that says ti follow the opinion of a group member who currently has best solution. But if a problem is complex, this strategy might lead to choosing suboptimal solution. 
* If there is a complex problem, for example writing a scientific paper, arranging a political system, etc. then following many voices migh be the best way to arrive at an optimal solution. 
* However if a solution exists and is known, or is easy to find, diversity of opinions can be a problem here. **Controversial issue**: once a society has come to a solution to a long standing problem, for example a scientific fact, then inviting people to have opinions about it can be detrimental.

The above is supposed to demonstrate that different rules can be needed for different problems, making it difficult to choose a good decision rool in advance. The second aspect that might not be clear in the examples above, but that's of a gret relevance here that the decision rules and their effectiveness will be affected by the social networks at play.


> Idea: if you don’t know what to do, then to make a decision go for a small group… But note that you get benefit from a small group even if it’s chosen at random.

>Important point: separation of information gathering from decision making.


Now, there are different stages of the decision-making process.
1. The first step is to gather information, and here we can profit from large groups, diverse opinions and experiences. 
2. The second step is making the actual decision, where arguably a smaller group is better. However, the assumption is that the decision making group has collected all possible information on the problem, and so that at least in the longer run we’re confident that this group is making decision better than random. (Note, if the decision making group is ignorant, then it’s either best to have a dictator, or as large a group as possible).


### Bias due to social network reasons.

There's quite a lot of research about behavioural biases and how they affect people's decision and potentially prevent them from acting rationally. On the other hand games theory and mechanism design often make strong assumptions of rationality or bounded rationality.

This interesting piece of research talk about how social network can affect peoples' decisions, and investigates forming or changing beliefs. 

Science communicators, typically, when presenting new piece of scientific knowledge to people would concentrate on providing facts, often devoid of context. Girvan explains that the context is vitally important, and it is what allows people to place the new piece of information with regards to two types of networks: social networks (what we believe other people in our network think about the issue), and semantic networks (all kinds of values that are related to the issue).

Being wrong about something can be less damaging than losing the social network. And on the other hand, if a new piece of knowledge is in dissonance with person’s values and moral beliefs, it will be difficult to accept. So convincing a person to accept a new piece of knowledge, or to change their belief on an issue, is likely to require resolving these moral or social concerns.

Example: a person whose social network consistd of people strongly opposing covid vaccination was very likely to not want to get the vaccination themselves as well. 

## Bibliography:

“Asking about Social Circles Improves Election Predictions Even with Many Political Parties”, Wändi Bruine de Bruin, Mirta Galesic, Rasmus Bååth, Jochem de Bresser, Lars Hall, Petter Johansson, Thomas Strandberg, Arthur van Soest
https://academic.oup.com/ijpor/article-abstract/34/1/edac006/6567647


Barkoczi, D., Galesic, M. Social learning strategies modify the effect of network structure on group performance. Nat Commun 7, 13109 (2016). https://doi.org/10.1038/ncomms13109


Smaller Crowds Outperform Larger Crowds and Individuals
in Realistic Task Conditions
Mirta Galesic, Daniel Barkoczi, and Konstantinos Katsikopoulos

Online First Publication, May 30, 2016. http://dx.doi.org/10.1037/dec0000059

Michelle Girvan on reservoir computing: adding a little chaos to a ML algorithm can help not to get stuck in local optimum…
“Stabilizing machine learning prediction of dynamics: Novel noise-inspired regularization tested with reservoir computing”
Alexander Wikner, Joseph Harvey, Michelle Girvan, Brian R. Hunt, Andrew Pomerance, Thomas Antonsen, Edward Ott
https://www.sciencedirect.com/science/article/pii/S0893608023006159


Science Communication in Light of Moral and Social Concerns: Testing a Statistical Physics Model of Belief Change
Tamara van der Does, Daniel L. Stein, Nina Fedoroff, and Mirta Galesic
https://osf.io/preprints/osf/zs7dq
