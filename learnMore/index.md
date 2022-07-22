---
layout: default
title: About
---


# The Linking Hypothesis and Visual World Paradigm

The visual world paradigm (VWP) is a widely used methodology in psycholinguistics, whereby participants' eye movements are tracked as they hear linguistic input. Since it has been shown eye-movements are sensitive to linguistic input, researchers use the VWP to create a fine-grained record of participants' language-directed attention given linguistic input.


However, the **linking hypothesis**–the link between eye-movements, linguistic input, and cognitive processes–for the VWP is still poorly understood. One explicit proposal, for active referential tasks (in which a participant must identify and select a speaker's intended referent) is:

$$ p_{emirical}(r | u) \propto	p_{belief}(r = target | u) $$

That is, the proportion of looks ($$ p_{empirical} $$) to an object *r* in response to a speaker's utterance (*u*) reflects the participant's degree of belief ($$ p_{belief} $$) that *r* is the referent that the speaker intended.

However, assessment of this linking hypothesis has given mixed results (). We believe that this is because this linking function only accounts for **exploitation** and not **exploration**. That is, the linking function explains where participants may look, if they are familiar with the objects presented in the VWP and the utterance they hear. However, if the linguistic input or visually presented images are unexpected, participants may want to **explore** their visual space in order to establish what a speaker may refer to the images as, and why a speaker may have chosen an unexpected way to refer to the images.

Therefore we believe that the cases where the linking hypothesis does not hold are cases where the linguistic input was unexpected.

# The Project

In order to assess the explicit linking function, we re-implement active-refential-task eye-tracking experiments as incremental decision tasks. The incremental decision study gives us a direct measure of participants' explicit belief that an object is the speaker's intended target. We can thus compare eye-movements ($$ p_{emirical} $$) with participants' explicit belief ($$ p_{belief} $$). If we find a high correlation between the two, we have evidence that supports this hypothesis.

In order to assess the role of *exploration* when encountering unexpected linguistic input, we re-implement the eye-tracking study and incremental decision study as a production study. By giving participants the visual input and asking them to produce utterances, we can see which utterances people produce naturally and compare these to the utterances actually used in the eye-tracking and incremental decision tasks. To quantify how unexpected or unnatural certain utterances are, we use the measure of surprisal:

$$ Surprisal(utterance) = -log_{2}(utterance) = -log_{2}\frac{[number \: of \: occurrances \: of \: utterance]}{[number \: of \: visual \: scenes \: where \: utterance \: could \: have \: occurred]} $$

The surprisal of an utterance (or a specific word in an utterance) is the negative log of percentage of time participants *actually* produced the utterance in the production task out of all times the *could* have produced the utterance.

If *exploration* is at odds with *exploitation*, then the higher the surprisal of an utterance the lower the correlation between eye-movements and clicks. That is, surprisal and correlations between incremental decision and eye-tracking experiments should be highly correlated.


** CAROUSEL IMAGE OF THE PIPELINE **
