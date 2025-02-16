# The Arbor Project

Welcome! 
Arbor (**A**nalysis of **R**easoning **B**ehavior through **O**pen **R**esearch)  is a radically open collaborative project where people across the internet can work together publicly and in real time, to collectively analyze and interpret AI reasoning models. 
By sharing partial progress and early results, we aim to eliminate duplicative work and dramatically accelerate progress.
To get started, see [Discussions](https://github.com/ArborProject/arborproject.github.io/discussions).

Our goal is to create a central clearinghouse where people can:
* Ask, discuss, and prioritize research questions
* Post, discuss, and analyze early and partial experimental results
* Serve as a clearinghouse for what the research community has learned.
  
The goal is to make this as open as possible, and to find ways to let people of all types of backgrounds participate.
All of our on-going projects can be found in [Discussions](https://github.com/ArborProject/arborproject.github.io/discussions).

## Why is interpretability research urgent for reasoning models?

Interpretability research is important in general, but especially urgent in the case of reasoning models. (By "reasoning model," we mean LLMs that have been trained to exploit extended inference-time computation.) These systems appear to be powerful, yet remain mysterious. Understanding them better can help us create safer technology, sooner. It's also a grand intellectual challenge.

See [Discussions](https://github.com/ArborProject/arborproject.github.io/discussions) to participate!


## Why work collectively, in the open?

Open-source reasoning models have appeared only recently, and many different groups are looking at them right now for the first time--likely working along similar lines. We think the community can move fast and save work by sharing partial results and early ideas. Although the academic machine learning already has an admirable culture of sharing preprints of finished work, we think it's worth experimenting with a more open model.

An important element of our plan is to find ways for people many levels of experience and skill to participate. In a project like this, there will be important roles for experience ML researchers, for people looking to break into ML research with  small concrete coding projects, people who want to work on pure theory, who people like analyzing data, etc. In fact, there will may be room for "citizen science" where people with no direct machine learning experience can help find patterns in model outputs and inputs.

Our efforts are inspired by the world of open-source software, and also mathematical initiatives like [polymath](https://en.wikipedia.org/wiki/Polymath_Project) and [Equational Theories Project](https://teorth.github.io/equational_theories).

Join [Discussions](https://github.com/ArborProject/arborproject.github.io/discussions) to participate!

## How to participate

Some starting points:

* [Discussions](https://github.com/ArborProject/arborproject.github.io/discussions) is where all projects are being tracked, feel free to start a new discussion.
* Join our [Discord](https://discord.gg/SeBdQbRPkA)! We are using NDIF's server - once you join, look for channels related to Arbor.
* Add your name and your interests to the wiki [People page](https://github.com/ArborProject/arborproject.github.io/wiki/People)
* If you have finished work, or know of a paper on arxiv people might be interested in, please publicize it on Discord, and add a link to the [Bibliography](https://github.com/ArborProject/arborproject.github.io/wiki/Bibliography).
* Please read through our community guidelines and notes on authorship/credit assignment in our [Wiki](https://github.com/ArborProject/arborproject.github.io/wiki/).


### A note on authorship

An issue that will naturally come up in this type of project is credit, especially authorship on papers. Indeed, our hope is that this project will catalyze multiple "classic" conference papers and collaborations. We may add more formal guidance in the future, but for now we advocate an inclusive attitude toward authorship.
Please see our [Wiki](https://github.com/ArborProject/arborproject.github.io/wiki/) for more information.


# How to use this repository.

The [Discussion](https://github.com/ArborProject/arborproject.github.io/discussions) section is where all projects are being tracked.
Anyone can participate, as well as kick off new projects.

The first post of each thread should follow a strict template, which includes the research question, current contributors, and project status.
The first post should also be treated as a project-specific "Wiki" that summarizes the current status of the project. Please see TODO for instructions and TODO for examples.


# Some On-going Research Questions

Here we pose a few research questions that are on our minds. We are hoping community members will contribute experiments to update our knowledge in these broad questions.

## High-level questions
### Output Behavior vs. Inner Mechanisms
* To what extent does the stated verbal reasoning reflect the actual process that creates the final answer?
* Behaviorally, R1's outputs look like it is doing search. Is it actually implementing search? E.g., can we probe out multiple potential next steps from a hidden state?
* What happens mechanistically when R1 has an "aha moment", does it mark a good intermediate result with that?

### "Mechanisms"
* How does R1 pick the next step? Does it have a notion of step (as in picking the next sub-problem)?
* Does R1 learn to verify? Does it know the difference between right and wrong intermediate results?

### Understanding RL vs. Base Models
* What capabilities pre-exist in base models (and perhaps enhanced with RL), and what capabilities are an emergence from RL?
* How do concept representations differ between the pre-distillation base model (e.g. Llama 7B) and the distilled model?
* Is the base model (Deepseek-V3) also capable of solving the task when prompted with R1’s CoTs that led the R1 to the correct result?
* If we find elements of reasoning in R1 (lookahead etc.) can we trace some of them back to the base model (e.g., as a mechanism to do better in next-token prediction)?
* Do base and reasoning model's next token probabilities disagree at interesting positions?

## Potential Representations to Probe For
* Backtracking
* Verifier
* Problem Difficulty
* "thinking time is over"

# Discord

Feel free to join our [Discord](https://discord.gg/SeBdQbRPkA)! We are using NDIF's server - once you join, look for channels related to Arbor.

