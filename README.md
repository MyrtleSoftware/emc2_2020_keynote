# [EMC2 2020](https://www.emc2-ai.org/virtual-20) Keynote: Achieving Low-latency Speech Synthesis at Scale

**Author**: Sam Davis, Myrtle.ai

**Bio**: Sam Davis is Head of Machine Learning at Myrtle.ai where his team works to understand and develop efficient, state-of-the-art machine learning models. His interests and work focus on the intersection of Conversational AI, model compression, and hardware design for machine learning inference. He chaired the MLPerf.org working group to develop the speech recognition benchmark that was released as part of the recent v0.7 inference round.

**Description**:  Real-time text-to-speech models are widely deployed in interactive voice services such as voice assistants and smart speakers. However, deploying these models at scale is challenging due to the strict latency requirements that they face: one pass through the model must complete once every 62.5 microseconds to generate 16kHz audio. This talk will introduce these challenges through the WaveNet model, a state-of-the-art speech synthesis vocoder. It then discusses how this class of models can achieve high-throughput, low-latency inference at scale through the combination of three components: model compression, more suitable programming paradigms, and more efficient compute platforms.

---

**Slides**: [Link](https://github.com/MyrtleSoftware/emc2_2020_keynote/blob/master/Achieving%20Low-latency%20Speech%20Synthesis%20at%20Scale.pdf)

**Slide 26, Blue Audio (with softmax + sampling)**: [Link](https://github.com/MyrtleSoftware/emc2_2020_keynote/blob/master/synthesized_sample.wav)

**Slide 26, Red Audio (mode)**: [Link](https://github.com/MyrtleSoftware/emc2_2020_keynote/blob/master/synthesized_sample.wav)
