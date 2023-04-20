# mm_diffusions

# DiffusER: Discrete Diffusion via Edit-based Reconstruction
ABSTRACT:
In text generation, models that generate text from scratch one token at a time are currently the dominant paradigm. Despite being performant, these models lack
the ability to revise existing text, which limits their usability in many practical scenarios. We look to address this, with DIFFUSER (Diffusion via Edit-based
Reconstruction), a new edit-based generative model for text based on denoising diffusion models – a class of models that use a Markov chain of denoising steps to
incrementally generate data. DIFFUSER is not only a strong generative model in general, rivalling autoregressive models on several tasks spanning machine translation, summarization, and style transfer; it can also perform other varieties of generation that standard autoregressive models are not well-suited for. For instance, we demonstrate that DIFFUSER makes it possible for a user to condition generation on a prototype, or an incomplete sequence, and continue revising based on previous edit steps. 
摘要：
这篇文章的摘要是介绍了 DIFFUSER (Diffusion via Edit-based Reconstruction) 这个新的基于编辑的文本生成模型，它是一种基于去噪扩散模型的生成模型，使用一系列去噪步骤的马尔可夫链来逐步生成数据。DIFFUSER 不仅在一般情况下是一个强大的生成模型，可以在机器翻译、摘要和风格转移等多个任务上与自回归模型相媲美，而且还可以执行标准自回归模型不适合的其他类型的生成。例如，我们演示了 DIFFUSER 使用户能够以原型或不完整序列为条件进行生成，并根据先前的编辑步骤继续进行修订。
方法：
它使用一系列扩散步骤来生成文本。DIFFUSER 是一种灵活的方法，可以将基于编辑的生成过程应用于任意文本生成任务。DIFFUSER 模型文本生成为标记级别的一系列扩散步骤。这种形式的生成允许我们使用基于编辑的损坏和重构开发自然编辑过程的合成公式。DIFFUSER 通过启用编辑过程应用于通用文本生成，同时不影响性能或需要外部监督数据，从而将这两个视角统一起来。DIFFUSER 使得可以对文本进行生成和编辑，包括由其他模型（例如自回归变压器）产生的文本，这使得它成为文本生成范式的自然扩展。
