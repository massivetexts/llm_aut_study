# LLM AUT Study
Materials for "Beyond Semantic Distance: Automated Scoring of Divergent Thinking Greatly Improves with Large Language Models"

Organisciak, P., Acar, S., Dumas, D., Berthiaume, K., (2022).  Beyond Semantic Distance: Automated Scoring of Divergent Thinking Greatly Improves with Large Language Models. Submitted for publication. [Pre-print](https://www.researchgate.net/publication/363456838_Beyond_Semantic_Distance_Automated_Scoring_of_Divergent_Thinking_Greatly_Improves_with_Large_Language_Models)

## Running

These results can run in your browser. See code in the *notebooks* folder. You can click 'Open In Colab' to run it in Google Colaboratory. I'll be cleaning code for sharing throughout Sept and Oct 2022.

## Abstract

Automated scoring for divergent thinking seeks to overcome a key obstacle to creativity measurement: the effort, cost, and reliability of scoring open-ended tests. For a common test of divergent thinking, the Alternate Uses Task (AUT), the primary automated approach casts the problem as a semantic distance between a prompt and the resulting idea in a text model.

This work presents an alternative approach that greatly surpasses the performance of the best existing semantic distance approaches. Our system fine-tunes deep neural network-based large-language models (LLMs) on human-judged responses. Trained and evaluated against one of the largest collections of human-judged AUT responses, with 27 thousand responses collected from nine past studies, our fine-tuned large-language-models achieved up to `r = .81` correlation with human raters, greatly surpassing current systems (`r = .12 – .26`). Further, learning transfers well to new test items and the approach is still robust with small numbers of training labels; in some cases, without any training at all. This work also suggests a limit to the underlying assumptions of the semantic distance model, showing that a purely semantic approach that uses the stronger language representation of LLMs, while still improving on existing systems, does not achieve comparable improvements to our fine-tuned system. The increase in performance can support stronger applications and interventions in divergent thinking and opens the space of automated divergent thinking scoring to new areas for improving and understanding this branch of methods.
