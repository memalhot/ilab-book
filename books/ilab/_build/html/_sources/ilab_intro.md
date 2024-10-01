<!-- #region -->

# An introduction to InstructLab

Welcome to the InstructLab textbook. 🐶

 InstructLab (ilab) is an AI open source, command line tool that allows you to interact with a large language model (LLM) in different ways. You can serve a model of your choosing and chat with it, or you can train a pre-existing model (the foundational model being IBM’s open-source granite model), chat with your newly trained model, and then even evaluate the efficacy of that model and contribute to the community model. This means that InstructLab is model agnostic, and that anyone can contribute to a large language model. This gives you the power to help shape the future of generative AI and create transparency around what goes into the training of an LLM, without needing a PHD in AI. The tool gives you a lot of ways to interact with a revolutionary technology regardless of the architecture一 whether you have thousands of GPU’s running somewhere, or you’re just using your personal laptop一InstructLab is designed for you. You can check out the repo for InstructLab repo: https://github.com/instructlab here.

## Open Source in the World of Large Language Models

So, you might be wondering what an open source LLM is, what a community model is. Most models that have been released are closed source, meaning that we don’t know the code used to create them, the data used to train them, or have the hardware to run them. This means that communities have little to no say in technologies that deeply affect them. InstructLab attempts to open source at every level, the base IBM granite model is open source, the data it’s trained on is open source, and it can run without a GPU on a local laptop. It also attempts not only its technical infrastructure, but the knowledge it’s trained on itself. Since ilab allows you to train your own model, ilab also offers a community model, where if information you use to train a model improves the model, you can contribute that knowledge to the community model. Iteratively submissions are reviewed and adopted into the model, making a model progressively shaped by the community, hence the name of the community model. This means the model evolves with the knowledge of the community that supports it. And anyone can contribute to the knowledge, even people without technical backgrounds. All you need to do is use a basic YAML file using question and answer format. But, we’ll get into the nitty gritty of how to create a knowledge file and contribute here.

## How Training Works (A Brief Overview)

This book’s main intention is to walk you through using instructlab and how to train your own models. But we will also touch on how training these models work. InstructLab uses synthetic data to train LLMs. While one query to a one an LLM might not impact it’s output, Instructlab uses synthetic data to generate 1,000’s of similar queries, which creates a more computationally and cost effective way of instruction tuning methods than historical methods. This gives you more power over how your model is trained. It’s the difference between being a fish in the ocean or a whale. 

If you want a more extensive overview of the training process, you can read more about it in the paper that explains the use of synthetic data for instruction tuning, here: LAB: Large-Scale Alignment for ChatBots.


<div align="left">
      <a href="https://www.youtube.com/watch?v=SkXgG6ksKTA">
         <img src="https://www.youtube.com/watch?v=SkXgG6ksKTA/0.jpg" style="width:100%;">
      </a>
</div>

## Why Ilab?
We’ve already talked a little bit about the Ilab philosophy and what sets it apart from other LLM technologies. But let’s talk about why Instructlab?
Let’s take a look at the InstructLab overview:
```
Contribution to LLMs is not possible directly. They show up as forks, which forces consumers to choose a “best-fit” model that isn’t easily extensible. Also, the forks are expensive for model creators to maintain.
The ability to contribute ideas is limited by a lack of AI/ML expertise. One has to learn how to fork, train, and refine models to see their idea move forward. This is a high barrier to entry.
There is no direct community governance or best practice around review, curation, and distribution of forked models.
InstructLab is here to solve these problems… 

InstructLab's model-agnostic technology gives model upstreams with sufficient infrastructure resources the ability to create regular builds of their open source licensed models not by rebuilding and retraining the entire model but by composing new skills into it.
```

As you can see, InstructLab differs from other LLM because it offers you a sense of control in your LLM, and you can custom fit it to suit your needs, 


## This Book’s Purpose

This book aims to provide guidance and documentation for anyone looking to use the InstructLab tool, explain the design and philosophy of the tool, in hopes of making the open source tool more accessible to anyone interested. It assumes you have some experience with the command line, but when regarding knowledge contributions, no previous engineering experience. However, InstructLab will have a UI come out soon, making the tool even more accessible. This book was made with another open source tool, the Open Education Project, which uses open source technology to help open source education and create open source textbooks and software for the classroom. You can read more about the project here. But due to the open source nature of this book, you can make a pull request and add information or helpful notes about your experience using InstructLab!

## Getting Involved
If you’re interested in getting involved with InstructLab, or have any questions about the tooling, we have both community meetings where you can meet the project maintainers and collaborators as well as office hours. Anyone is welcome to join. You can check out the meeting schedule here. Or if you’re interested in contributing to the knowledge taxonomy, UI, or InstructLab itself, or the command line tool, check out our contributor guide.

## Final Mentions

<!-- #endregion -->
