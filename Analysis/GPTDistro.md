Shower Thought

Create an OS (Operating System) that is primarily GTP native.
I call it GTP distro.
This is a computer that exists solely in the latent space of an LLM.

Inspired by the GPT zipbomb, BabyAGI, and a prompt engineering article that was showing that one can essentially simulate and OS terminal using GPT.

The idea will be to create an LLM native Operating System.

Here the basic Archetecture [Napkin Archetecture](../Diagrams/GTPDistro.draw)

---

I've personally not at the level of training LLMs
I don't see the need given that I don't think I quite even understand the full capabilities of existing LLMs, from the inference side

---

LLMs that need to be trained
1) A LLM that is a interpretor - there is existing work
  - code interpretors
  - API LLMs
  - Tooling LLMs
  - Tricks involving feeding the Documentation into LLMs and then prompting

  The purpose for this LLM is to create an LLM that can understand human language and then create machine code to operate existing Operating Systems. I'm sure that everyone is already working on this. However, this project will try to add an additional transformation step that will translate into additional Operating System, the LLM native Operating System (GPT Distro)

2) **GTP Distro**
  - This is an LLM that contains entire OS state machines in it's latent space
  - I imagine that this LLM will be created by training on various internal states of personal computers (I'm most familair with consumer products, it could be propreitary systems)
  - It will act as if it's a computer completely compiled on a neural network... (I'm sure someone somewhere sometime out there once had these computers completely compiled in their brains as they worked on them)
  - Since, I can't straight compile source code in the simulated OS inside my brain, I need LLMs help to do so
  - My language (understanding of English), can be extended into the computer realm, through physical LLM compilation of English thought