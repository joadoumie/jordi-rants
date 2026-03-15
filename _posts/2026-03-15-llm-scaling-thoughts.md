---
title: "Random Thoughts on LLM Scaling and the Future of AI"
date: 2026-03-15
---

# Random Thoughts After Reading Empire of AI

I just finished reading Karen Chao's ["Empire of AI"](https://www.penguinrandomhouse.com/books/743569/empire-of-ai-by-karen-hao/). It is:

A) really, really good.
B) Ridiculously thought provoking.
C) Upsetting. Terribly upsetting.

I highly recommend the read to everyone.

At a high level, the book tracks the rapid development of the latest AI Research Labs (OpenAI, DeepMind, Anthropic, etc.) and their similarities to colonial empires of our past. Again, **I highly recommend that you read the book**. I won't be going deep into the details it provides because, well, I won't be able to accurately represent all the amazing journalism and storytelling Karen Hao has already done. BUT the TLDR relevant to this blog post is that these large corporations make grand promises about the future of AI: it will cure diseases, it will solve climate change, it will eliminate poverty. With these grand claims they justify the extraction of enormous amounts of land and natural resources from the [global south](https://commonslibrary.parliament.uk/what-is-the-global-south/) to build massive AI data centers and push horrible working conditions on desparate humans to train their AI models. Roughly the calculus is: if you could solve the world's most difficult challenges, don't the ends justify the means? These same ~~nonprofits~~ massive corporations with profit seeking shareholders also love to refer to `p(doom)` or the chance that AI completely wipes out all of humanity (more or less). You wouldn't want this technology falling into the wrong hands! The thinking goes something like this: it's inevitable that this technology will be created, so we need good humans to build it and harness its power before the bad humans do!

Now, clearly a lot of this thinking is deeply problematic. The actions taken by these few powerful AI empires increasingly feels similar to how I imagine religous humans have justified their horrendous actions of the past. Like, if you truly thought that every single human who doesn't accept Jesus Christ as their lord and savior would one day live in eternal hell... wouldn't you be pretty animated about converting folks to your branch of Christianity? Wouldn't, once again, the ends justify the means?

It's this ^ faulty thinking that has me really questioning where we go from here. There are really compelling arguments you can make to justify practically anything at all when there is a shared assumption about how extreme and inevitable an outcome is. For the sake of argument: assume it is truly inevitable that if done properly AI:

A) will cure humanities worst diseases
B) will end poverty
C) will solve our climate crisis
D) will massively increase the average standard of human life globally

Also assume that if not done correctly, AI will:

A) lead to the end of all humanity.
B) There is no B. I JUST SAID IT WILL LEAD TO THE END OF ALL HUMANITY! Whether it is painful or not, it's not good!

IF (big IF) we believe the above, then clearly it is difficult to argue against anything that gets in the way of properly developing AI. I don't fault people who believe in this way of thinking either. There is something really appealing about it. But the problem is that there is no guarantee that AI will have the massive benefits these empires claim it will. There is also no evidence that AI has the existential threat of eliminating all human existence (or y'know other really bad outcomes).

# Somewhat Related Random Thoughts on LLM Scaling vs. The Human Brain

Let's try to put some of these grand claims in perspective by comparing LLMs to the thing we actually know can reason, create, and discover: the human brain.

The human brain has roughly **100 trillion synaptic connections** -- that's the biological equivalent of model weights (I know, I know... anthropomorphizing these systems is sometimes deeply problematic). A frontier LLM like GPT-5 likely has somewhere in the range of [2–5 trillion parameters](https://lifearchitect.ai/gpt-5/) — though OpenAI hasn't officially disclosed the number, and estimates vary widely depending on whether the model uses a [Mixture-of-Experts](https://en.wikipedia.org/wiki/Mixture_of_experts) architecture (where total parameter count and _active_ parameter count are very different things). So we're not even in the same ballpark yet, parameter count-wise. On top of that, your brain runs on about **20 watts** which is less than the light-bulb in your fridge. Training a large frontier model can consume [millions of dollars worth of electricity](https://arxiv.org/abs/2104.10350), and inference at scale isn't cheap either. And of course, your brain learns _continuously_ from every experience you have, while LLMs are frozen in time the moment training ends (yes, fine-tuning, advanced context management techniques, and RLHF exist, but it's not quite the same thing).

So, **even if we do scale these systems up dramatically, why would that suddenly unlock capabilities we don't already have?** I mean... it totally could. I actually do believe that is entirely possible. But it's not super intuitive to me that it 100% will?

Because, idk, we already have like 7 billion human brains running around on the planet right now. Seven. Billion. Each one individually capable of creativity, reasoning, and learning in ways that current LLMs demonstrably cannot replicate. Even if you granted that a cutting-edge AI system has the reasoning capacity of, say, 1/100th of a human brain, we still have a staggering amount of that kind of intelligence walking around, going to the grocery store, watching Netflix, and occasionally doing science (some better than others for sure).

And we've had large concentrations of human intelligence applied to hard problems before. Cancer research alone has consumed the working lives of hundreds of thousands of brilliant scientists across decades. Climate science, drug discovery, poverty reduction — these aren't fields starved of intelligence. They're fields that are _hard_. Often because the problems themselves are deeply complex, or because the bottleneck is something other than raw cognitive throughput — things like data quality, experimental iteration speed, coordination failures, political will, or just plain bad luck.

So what is it exactly that scaling an LLM changes? The optimistic case — and it's a real one — is that computers bring genuine advantages that humans don't have. To just throw a few at the wall:

- **Speed**: an AI can read and synthesize the entire scientific literature in hours. No human can do this. That is pretty compelling. I would love to have this superpower.
- **Consistency**: no cognitive fatigue, ~~no cognitive bias~~ (well, different biases actually explicitly encoded in the mathematical functions of the model and the way training data is generated/sampled... sooo ok yes bias. lots of it)
- **Parallelism**: you can run thousands of instances simultaneously.
- **Pattern recognition at scale**: finding weak signals across enormous datasets that would be really tough for humans to do.

It's entirely plausible that an AI system good enough at synthesizing and hypothesizing across all of biomedical literature could surface drug candidates or protein interactions that would have otherwise taken decades to find. That seems reasonable to me. That seems plausible.

But _"plausible"_ and _"inevitable"_ are very different words. The leap from "this tool is useful" to "this tool will cure cancer" requires a lot of assumptions to hold simultaneously: that the bottleneck in cancer research is pattern recognition over existing literature (and not, say, wet lab throughput or fundamental unknowns), that scaling model size actually improves the _right_ kinds of reasoning, and that we can trust the outputs enough to act on them in high-stakes domains.

None of those assumptions are obviously true. Which is why I find myself holding two thoughts at once: AI could absolutely accelerate scientific discovery in genuinely meaningful ways — and the specific grand promises made to justify the enormous costs being extracted right now deserve much more scrutiny than they currently receive.

I don't blame or judge passionate people who believe that this technology can either be the best thing to ever happen to humanity or... the end of it. I do believe it is _plausible_ that either of those things could be true. But I don't think it's _inevitable_. And while we work to build out these technologies I think it is incredibly important to be more aware of the active and current harm we are perpetuating globally. There are real costs that I believe with proper coordination and alignment could be avoided.
