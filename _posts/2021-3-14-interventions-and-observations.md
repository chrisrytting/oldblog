---
layout: post
title:  "Interventions and Observations"
date:   2021-3-14 15:31:00 -0600
categories: jekyll update
---

I wrote this in response to the idea in the field of causality that you can't learn how the world works by observational data, that instead you need experimental data where interventions are performed. It became a little thousand-word essay about data awe, and about how I think that the causal ban on observational data and the causal embrace of interventional data is overly sure of itself.

If there were ever a century where people preferred datasets to the world itself, it would be the 21st. Which makes sense, in the context. Datasets are, of course, useful, and since they are brand new to the arc of history, they give us the same excitement as a toy that is both new __and__ interesting. 

Fun new toys never come out of nowhere, though. We've recently found many mor ways to make data, to record at astounding scope and to store all those records. 

The astonishment comes when you consider how much manual labor would be required to gather all the information that is gathered and how similar the result is. To make the common crawl dataset with all its terabytes of text data, there is no person getting that data in the way we would get it without computers, which is to say, finding answers to questions by asking around and recording them in a notebook. There is no person calling up experts and jotting down all the detail they share about a kalman filter that is today ready-crafted in a wikipedia article. There is no person gathering an assembly of people to talk about politics and recording the back and forth that emerges. But the result is the same as if they did. The miracle of recording is right at the juxtaposition of the common-sense of recording things that happen and the impossibility of just how much gets recorded. Datasets in this sense are lives both expanded and compressed, where you can ask more questions and get more answers than you could in a whole lifetime but do it in far less time. 

This leads us to hope that datasets also have many orders of magnitude more answers than previously we've laid hold to. Every dataset is ultimately designed by people, and whatever we include or miss, they will include or miss. They are nothing more than snapshots of the real world, taken specifically and only of things we decide to remember. We call this stuff signal, and before it was memorialized as data, it was neighbored by an infinity of other information, which we forgot by calling it noise. Dataset formation is the ultimate exercise in mindful focus on the essential.

Of course, people collect data not so much to remember as to make sense of. To answer questions. The irony of people collecting data from which to extract wisdom is that they seek the very understanding which would dictate what data should be gathered in the first place, and they might gather noise instead of signal or ignore signal instead of noise.

Remember that this whole useful practice of collecting data comes from our learning from it before we ever called it data. Humans are able to learn things pretty intuitively from paying attention to incoming perceptual data streams. Maybe I have some gravitational prior built into me, but I certainly learn from watching things fall that, in general, heavy things don't stay suspended in the air. Watching something fall, then, the signal for that phenomenon includes information about the item's density, its position in space, everything else's position in space (or, more efficiently, what is in a neighborhood of proximity to it). These are the types of information that we learn from and use to make predictions and decisions in real life.

Learning about the world by reasoning about what we observe is science. You can also test out what you hypothesize by doing experiments. If you decide you think an apple will fall if you let go of it, you can do a ton of experiments and see it in action a million times. Then, on the million and first time you drop the apple, you'll be pretty smart about what's gonna happen.

But if you watch somebody else drop the apple a million times and then you guess what happens on the million and first time, I bet the same thing happens. All else being equal, you probably conclude that letting go causes falling.

Causal people say that observational data won't illustrate causality. They say that because if you have cross-sectional data of a couple of variables $$X$$ and $$Y$$, and you care about determining whether one causes the other (either $$X \rightarrow Y$$ or $$X \leftarrow Y$$), then if either of those things are true, the observational data will be the same. I.e. they will be positively or negatively correlated, but you don't know whether it's $$X$$ driving $$Y$$ or $$Y$$ driving $$X$$, or whether there is some other variable $$Z$$ driving both ($$X \leftarrow Z \rightarrow Y$$).

But it probably isn't whether the data is observational or interventional that determines whether it will help you answer questions about causality, and that's basically because observational data can be very detailed, in theory. Data can be as rich as watching someone drop an apple time and time again, and if the data is that rich, nothing is to stop an observer from making an informed guess about the outcome of trial one million and one.

Now, of course that assumption could break in the same way that if you assume that temperature is causal on altitude, and not the other way around, you will be very disappointed when you crank up the thermostat and your house stays perfectly still (change your house's altitude, however, and the temperature __will__ change).

But conclusions drawn from interventional data can also break, like if you released an apple in midair in every one of your experiments, you're results would hold if you went to a different country but not if you went a hundred feet under water.

Any dataset, interventional or causal, will likely be causally insufficient, meaning that there will be variables influencing the observed distributions which are omitted or ignored. Thus, the conditions of the dataset will not be equal to the conditions of the world in which you're trying to make decisions. That's an uncertainty we have to live with. The gold standard will remain for both types of studies to change just one thing about the world and observe effects of interest, and the question is whether observational data will ever be rich enough to be causally sufficient without actually having to take the ethical risk of a trolley-problem decision. Hopefully Judea Pearl figures it out.
