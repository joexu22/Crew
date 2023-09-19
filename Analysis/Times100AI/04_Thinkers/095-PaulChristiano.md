Paul Christiano
Founder, Alignment Research Center

King Midas, a figure from Greek mythology, wished that everything he touched would turn to gold. His wish was granted, but his gift quickly became a curse as even food and his daughter were transformed.

A decade ago, many AI doomsday thought experiments involved King Midas scenarios, in which humans told an AI system what to do, and the AI, in doing so maximally and literally, caused a catastrophe. An AI system told to maximize the output of a paper-clip factory would turn all of the atoms on earth, including those that make up human bodies, into paper clips, for example.

Those who work on alignment—the problem of ensuring AI systems behave as their creators intend—no longer worry about this. Researchers can now train AI systems to iteratively learn difficult-to-articulate goals by having humans rank the responses an AI gives by how helpful they are, and having the AI system learn to produce results that it predicts will be rated as helpful as possible. With this method, humans don’t have to say what they want the AI to do, they can simply tell the AI if it has done what they wanted.

This technique is known as reinforcement learning from human feedback (RLHF). Paul Christiano is one of its principal architects. Among the most respected researchers in the field of alignment, Christiano joined OpenAI in 2017. Four years later, he left to set up the Alignment Research Center (ARC), a Berkeley, Calif.–based nonprofit research organization that carries out theoretical alignment research and develops techniques to test whether an AI model has dangerous capabilities. When OpenAI and Anthropic want to know whether they should release a model, they ask ARC.

TIME spoke with Christiano about the invention of RLHF, leaving OpenAI, his work at ARC, and the idiosyncrasies of the AI alignment community. (This interview has been condensed and edited for clarity.)

TIME: Could you describe the development of RLHF as a technology?

Paul Christiano: Starting with backstory, before I was at OpenAI, there are two relevant threads to be aware of. One is that I’ve been thinking about alignment for a pretty long time and trying to understand what a plausible alignment solution looks like. RLHF stands out as a very early and natural step.

I think a second thread to be aware of is that a bunch of people have worked, normally in much simpler settings, on learning values from humans. There’s a community of people, especially in robotics, thinking about how you learn reward functions for hard-to-specify tasks.

This first project [at OpenAI] was trying to take some domains where deep RL [reinforcement learning] works very well. The two domains where deep RL is most successful are simulated robotics tasks, and playing games. And so we just did a project in both of those domains showing that you could learn goals that are kind of fuzzy goals defined by humans. That project worked reasonably well, and then from there the next step was trying to adapt that to models that are more interesting or realistic—trying to work with language models. This went in parallel with, or was a little bit before, training GPT-1.

Why did you leave OpenAI in 2021?

I did my Ph.D. in learning theory; my natural comparative advantage was definitely doing theoretical research. I worked on empirical research for those four years in significant part because empirical research on alignment was not [well developed], and it seemed like being at OpenAI, I could help it get started and implement some very basic stuff that really should happen.

In terms of the exact timing, that was around the same time a bunch of folks who I collaborated with left to go and found Anthropic. So that somewhat increased the incentive to collaborate with people not at OpenAI and decreased the incentives to talk to people at OpenAI. I thought a little bit about policy influence. But definitely the biggest thing was wanting to return to theoretical research.

Why would having more people outside of corporate labs be good for policy influence?

Ultimately, it’s going to be important to have external pressure on labs to implement responsible policies. I think it’s going to be valuable, both as part of that and as part of engaging with the rest of the world, to have people who aren’t seen as lab partisans.

Model evaluations aim to understand what AI systems can do—their capabilities—and whether they work as their developers intend—their alignment. Alignment Research Center has done model evaluations for OpenAI and Anthropic. How did those come about? Was it through the strength of your personal relationships with those companies?

The argument for doing evaluations is quite strong. So independent of me having any relationship, that’s something that labs are excited about doing. It is helpful that I have reasonable relationships with the people at OpenAI and Anthropic, and that made it particularly easy. I also think they’re probably the two organizations most interested in doing these kinds of evaluations.

I think that the prospects are reasonably good both for ARC doing evaluations at other places, and for a broader ecosystem also having the same kind of access [to AI models before they are deployed] needed to do evaluations.

You’ve been part of the alignment community longer than most. Are there ways in which the alignment community could change to make better progress on the problems it seeks to address?

Realistically, the thing that seems most important is just bringing in a lot more people who care about alignment. Back in 2012, it made sense that this is a thing which you would think about only if you were really obsessed with humanity’s long-term future, or unusually excited about AI, or something like that. We’re not seeing the risks we’re concerned about appearing in the world today, but I think it’s much easier to draw the line between where we are today and future risks.

From a social-impact perspective, it also makes sense for just way more people to think about this. It’s something states should be taking an active interest in and broader society should be taking active interest in. Smart people are becoming interested in these questions, and it is expanding in a new different direction from the [machine-learning] academics and the Bay Area tech scene.