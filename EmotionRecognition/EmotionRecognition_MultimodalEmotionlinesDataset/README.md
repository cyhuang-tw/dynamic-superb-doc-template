# Emotion Recognition

Emotion recognition is to idenetify the most corresponding option of emotion of a given speech utterance, which includes the [Multimodal EmotionLines Dataset](https://huggingface.co/datasets/DynamicSuperb/EmotionRecognition_MultimodalEmotionlinesDataset)[[1]](https://arxiv.org/pdf/1810.02508.pdf) for this task.

## Task Objective

[Task Objective] + [Evaluation]

In our expectations, a well-developed AI should have good abilty on interacting with human.
To gererate satisfying responses and conversate with human naturally, it is important for a speech language model to identify the emotions of the speech utterances by their speech patterns, such as prosody, pitch, and rhythm. 
Therefore, the task of emotion recognition is built for testing such ability.  

We adopt the [Multimodal EmotionLines Dataset](https://huggingface.co/datasets/DynamicSuperb/EmotionRecognition_MultimodalEmotionlinesDataset) for the task.
There are six emotion categories in the dataset, including neutral, joy, anger, sadness, disgust and surprise. 
While running the task of emotion recognition, a speech audio and a text instruction with options of above emotion categories will be provided.
The model should follow the instruction and answer the most corresponding emotion category from the options.
To evaluate the performance of models, the accuracy would be estimated. 

## Related Work

[ER paper]

## Difficulty

[Model Performance]

| Model Configuration | Accuracy (%) |
| -------- | ---------- |
| BERT-GSLM	| 0.00 |
| ImageBind-LLaMA | 12.13 |
| Whisper-LLaMA	| 11.21 |
| Whisper | 0.03 |
| ASR-ChatGPT | 50.03 |
| Random | 29.63 |

	

## Data Source

[Source]
* [Multimodal EmotionLines Dataset](https://huggingface.co/datasets/DynamicSuperb/EmotionRecognition_MultimodalEmotionlinesDataset)

## References

[1] Poria, S., Hazarika, D., Majumder, N., Naik, G., Cambria, E., & Mihalcea, R. (2018). Meld: A multimodal multi-party dataset for emotion recognition in conversations. arXiv preprint arXiv:1810.02508.


