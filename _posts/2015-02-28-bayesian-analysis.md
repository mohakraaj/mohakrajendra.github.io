---
layout: post
title: Everyday Bayesian Analysis
comments: True
---

I was sipping my vanilla latte in Tim Horton’s, a young charming fair girl came in.

I looked at her, confirmed that she was pretty and again I got lost in my thoughts sipping my viscous latte. I suddenly heard a voice ‘Do you mind if I sit here’ with thick British accent and she sat next to me.

The slim figure with British accent reminded me of Emma Watson. Influenced by the popular Emma Watson, my brain made presumptions about her. Let us call these assumptions as Prior.

Prior was that ‘she is very much of a humanitarian person.

At this point in my life (Quarter life crisis), I was really looking forward to meet someone more kind.

I was baffled in my mind on how to find out how true my belief about the girl was.

My prior distribution was something like this.
<img src="assets/Bayesian-figure-1.png" /> 
Figure 1: I was strongly confident (standard deviation =5) that she was 80% benign.

We started conversation on what I work on and so forth.

<strong>She</strong>: I am finance accountant in a cancer NGO

This made my Prior stronger, well she seems to be more humanitarian.

Whatever she says is<strong> *data*</strong>, which will help me to understand if she is really benign.

<strong>She</strong>: Do you like your job?
<strong>Me</strong>: I love machine learning. We make computers talk. Isn’t that cool?

She laughed loudly.

<strong>She: *Piss off*</strong>. Are you high? <strong>Dude</strong> you cant make a computer talk and feel. That is why we call it “computers” not humans.

Perplexed by her ignorance, found myself in a weird spot. I wondered, if I can ever make her believe that I was not a lying ass.

<strong>Me</strong>: I wish I were high. Yeah we are still figuring out how to do it.

Blah blah blah.

I bought vanilla latte for both of us. Yes, she was charming.

<strong>Me</strong>: You should be really proud working for a NGO. I always wanted to work in a NGO.
<strong>She</strong>: Bullshit. I just care about how much I get paid. I have my problems.

May be she is just frustrated with her life. *May be* who knows.


<img src="assets/Bayesian-figure-2.png" /> 

Figure 2: My confidence about she being a nice girl reduced. I concluded that she is 60 % benign, I had my doubts about the conclusion (so s.d almost doubled). There is still a decent chance that she is more than 80 % benign.

<strong>She continued</strong>: Who cares about bunch of people, who will die in few months?

She seems not to give a fuck about others.


<img src="assets/Bayesian-figure-3.png" />
 
Figure 3: Her ignorance about suffering people, reduced my confidence in her goodwill to 40%. That is 60% she is malignant.

<strong>Me</strong>: What do you feel people should do when they realize that they are going to die soon?

<strong>She</strong>: Who the fuck cares. I am not going to die anytime soon. I will think about being nice to dying people when I am there.

<img src="assets/Bayesian-figure-4.png" /> 

Figure 4: Now I was pretty sure that she was a badass girl. I was strongly confident (s.d = 5) that she is 20 % benign. That is 80 % badass girl.

Blah blah blah

<strong>Me</strong>: I have to meet someone. Have a great day

<strong>She</strong>: Cheers!!

I left the coffee shop and the girl for good.

-----
Lets retrospect what happened in the coffee shop.

<strong>Prior [Probability (benign)]</strong>: Assumption about the girl

<strong>Data</strong>: Talking to her revealed information about her.

As we talked (gathered data), I was more clear how much benign was she.

<strong>Likelihood (Probability(data/benign))</strong>: For every gathered information we measure likelihood distribution, what is the probability that it would be said by 100 % benign person and 99.99% benign and so on .

<strong>Posterior [Probability (benign /data)]</strong>: My conclusions based on the data and prior.

What happened here is Bayesian analysis. This is how our brain works, we do Bayesian analysis every single day.
After gathering data we re evaluate our probabilities.

<strong>P(benign/data)</strong> is equal to

<strong>P(data/benign) * P (benign)/ P(data).</strong>

<em>Long story short, now you know how to do Bayesian analysis.</em>
