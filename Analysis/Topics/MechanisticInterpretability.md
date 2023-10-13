# Mechanistic Interpretability

mechanistic interpretability seek to reverse engineer neural networks

applied neuroscience techniques

## Insight

does mechanistic interpretabiltiy provide a pathway to ai safety?

The fact that most individual neurons are uninterpretable presents a serious roadblock to a mechanistic understanding of language models. 

We demonstrate a method for decomposing groups of neurons into interpretable features with the potential to move past that roadblock.

We hope this will eventually enable us to diagnose failure modes, design fixes, and certify that models are safe for adoption by enterprises and society.

It's much easier to tell if something is safe if you can understand how it works!

## Anthropic Research

one-layer transformer with an MLP layer with a ReLU activation function
w/ sparse overcomplete autoencoder

single layer approach
can it be scaled up?

## Definitions

objective function of large language models
  - learning an objective truth as pertaining to an objective function

agentic framework
  - mitigation of x-risk piecemeal
  - agents themselves are not fundamentally made safe

problematic

## Safety

worry over ASI-complete

x-threat
  - real world problem
  - (personally, I would like to understand more about the bridge between AI research and implications to the real world)

AGI -> ASI takeoff

## Technicals

auto-encoders that decomposes neurons
  - use to identify "problematic" neurons
  - hinges on our ability to identify these problems

"polysemantic" neurons
  - "superposition" - models compressing many rare concepts into a small number of neurons
  - "dictionary learning" - "sparse encoder"
    - extract features that represent purer concepts than neurons
  - artificially stimulating features and steering output
  - feature + "finite-state automata"
    - neuron based computer

feature interpretation
  - sparse coding
  - distributed representations in neuroscience
  - disentanglement
  - dictionary learning in machine learning
  - compressed sensing in mathematics.

further insight
  - universality
  - "feature splitting"
  - more evidence for the superposition hypothesis
  - tips for training a sparse autoencoder to better understand your own network!

LEAst-squares Concept Erasure (LEACE)
  -like concept erasure approach we have by that point

## Extra

our ability to identity problematic neurons will not solve real world problems

## Near Term Implications

AI fairness, accuracy, transparency reliable AI applications

particularly for the adaptions it hints toward for non-LLM deep neural networks.

Meta’s ad targeting DNNs you’d probably find some undesirable implicit features that could be eliminated
