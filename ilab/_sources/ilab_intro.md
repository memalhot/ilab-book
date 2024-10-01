<!-- #region -->

# An introduction to InstructLab

Welcome to the InstructLab textbook. 🐶

 InstructLab (ilab) is an AI open source, command line tool that allows you to interact with a large language model (LLM) in different ways. You can serve a model of your choosing and chat with it, or you can train a pre-existing model (the foundational model being IBM’s open-source granite model), chat with your newly trained model, and then even evaluate the efficacy of that model and contribute to the community model. This means that InstructLab is model agnostic, and that anyone can contribute to a large language model. This gives you the power to help shape the future of generative AI and create transparency around what goes into the training of an LLM, without needing a PHD in AI. The tool gives you a lot of ways to interact with a revolutionary technology regardless of the architecture一 whether you have thousands of GPU’s running somewhere, or you’re just using your personal laptop一InstructLab is designed for you. You can check out the repo for InstructLab repo: https://github.com/instructlab here.

## Open Source in the World of Large Language Models

So, you might be wondering what an open source LLM is, what a community model is. Most models that have been released are closed source, meaning that we don’t know the code used to create them, the data used to train them, or have the hardware to run them. This means that communities have little to no say in technologies that deeply affect them. InstructLab attempts to open source at every level, the base IBM granite model is open source, the data it’s trained on is open source, and it can run without a GPU on a local laptop. It also attempts not only its technical infrastructure, but the knowledge it’s trained on itself. Since ilab allows you to train your own model, ilab also offers a community model, where if information you use to train a model improves the model, you can contribute that knowledge to the community model. Iteratively submissions are reviewed and adopted into the model, making a model progressively shaped by the community, hence the name of the community model. This means the model evolves with the knowledge of the community that supports it. And anyone can contribute to the knowledge, even people without technical backgrounds. All you need to do is use a basic YAML file using question and answer format. But, we’ll get into the nitty gritty of how to create a knowledge file and contribute here.

## How Training Works (A Brief Overview)

This book’s main intention is to walk you through using instructlab and how to train your own models. But we will also touch on how training these models work. InstructLab uses synthetic data to train LLMs. While one query to a one an LLM might not impact it’s output, Instructlab uses synthetic data to generate 1,000’s of similar queries, which creates a more computationally and cost effective way of instruction tuning methods than historical methods. This gives you more power over how your model is trained. It’s the difference between being a fish in the ocean or a whale. 

If you want a more extensive overview of the training process, you can read more about it in the paper that explains the use of synthetic data for instruction tuning, here: LAB: Large-Scale Alignment for ChatBots.


<iframe width="560" height="315"
src="https://www.youtube.com/watch?v=SkXgG6ksKTA" 
frameborder="0" 
allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen></iframe>

<!-- #endregion -->
