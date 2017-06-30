# HiPSTAS / WGBH / AAPB Redport, July 2017

[Forward to pg. 2 >>](https://github.com/hipstas/aapb-july-2017-demo/blob/master/02_Audio_Labeler.md)


### People for whom audio machine learning may be useful
- individual historians and humanists sorting through digital audio collections
- journalists and documentarians searching for relevant material
- archivists and librarians doing maintenance and preservation work

### Problem space

- Cultural media collections are different from the industry machine learning context.
    - relatively small and static (or slowly growing) collections
    - The precision-recall tradeoff tends to favor recall.
    - rigorous performance scores not so important


- In this context, state-of-the-art performance may be overkill, both in terms of compute time and training time.
    - Deep learning requires a large quantity of training data and runs prohibitively slowly on consumer PCs.

- Initial constraints
    - Storage and compute resources may be limited.
    - Labeling audio for training is time-consuming.
    - Workers may not be comfortable writing code or using the command line.

- Technical challenges
    - Most existing software for training audio classifiers has a high learning curve.
    - Training models using hours of training data can take a very long time, making iterative improvements difficult.
    - Overfitting: Models trained on audio from a small number of sources may perform poorly in the real world.

- Industry norm for designing ML classifiers: 3 separate labeled datasets before a model sees real-world data.
    - training set
    - validation set
    - test set






###


<!--
Projects mix and match pieces,


  - pain point for wav-only systems: code gets verbose as

- limited HD space
- limited CPU capacity

- ^^ not the case in the tech industry! Where they use neural nets


there's a common structure for ML research, but this is different

Becomes about heuristics -- writing scripts to smooth and infer things from classification output


Example: podcast ad remover





Attk
- the best way to do everything


Audio Labeler
- usable by non-technical workers
- fixes shortcomings of naive random tagging tools
- customizable




Pipeline
 Keep extractor




Idea of ranges






Results:
Tone classifier
Pesca scores








Needs:


Flexible metadata search (MongoDB)

-->


[Forward to pg. 2 >>](https://github.com/hipstas/aapb-july-2017-demo/blob/master/02_Audio_Labeler.md)
