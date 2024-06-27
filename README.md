# latent-langs

LLM language design is a method for structuring the outputs of large language models. You can think of the language grammars as sophisticated templates which if instructed LLMs will fill the "holes" of when generating text. They are a means of declaratively guiding the behavior of LLMs on a number of axes.

ConceptScript has been an attempt to find a meeting point between the internal structures of LLMs and human thinking. The primary use cases I've found so far are: drawing out rich detailed information from minimal input, distilling complex textual sources to logical essences, evolving conceptual models through LLM dialog as a means of theoretical exploration, and automated synthesis of heterogeneous complex ideas.

I believe much of the value here is in language design as a general technique for interacting with LLMs: a kind of precision tool for "LLM whisperers". I don't think ConceptScript or any other LLM language will attain a perfected final form; what makes a language optimal is relative to the model it runs on and the problem you're trying to solve. That said, there are enough commonalities between models at this point that many general principles will likely be stable over time and across models: I'm sure many remain to be discovered, too.

The purpose of this repository is to share my findings so far on this topic, and to provide some structure for continued collaborative exploration.

## Overview of included languages
- ConceptScript: used for conceptual modeling and exploration—the most well-developed of the set.
- LatentScript: used for doing semi-automated analysis, pulling rich/diverse info into context first; very early in development, not really ready for use yet (temporary name).
- ModelScript: basically a minimalist/essentialized version of ConceptScript. It's the most recent development, not yet thoroughly tested but likely the best bet for many use cases.

## Basic usage instructions for ConceptScript
- Paste the boot prompt into context: [boot_prompt.txt](ConceptScript/boot_prompt.txt)
- This will generate a first Concept combining ideas from the embedded example Concepts
- Ask the LLM (works best with Claude so far) to express various things as Concepts
- Iterate on the generated Concept, requesting modifications or for various operations to be performed.

There is a bit of art to it, so I'd recommend watching the video below for a more in-depth introduction.

YouTube video: [Introduction to LLM languages+ConceptScript](https://youtu.be/lmhvevCL7RU)

And here's a fun way to view Concepts—it's loaded with one by default but you can paste your own in: https://westoncb.github.io/concept_inspector/
 
