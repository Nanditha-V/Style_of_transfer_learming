# Style_of_transfer_learming
Using the transfer learning technique (keras, tensorflow)

Transfer learning is a powerful technique used in Deep Learning. 
With transfer learning, we basically try to use what we’ve learned in one task to better understand the concepts in another. weights are being automatically being shifted to a network performing “task A” from a network that performed new “task B.”Because of the massive amount of CPU power required, transfer learning is typically applied in computer vision and natural language processing tasks like sentiment analysis.

There are two main approaches to transfer learning:

**Feature Extraction**: In this approach, the pre-trained model's early layers, which capture low-level features, are frozen, and only the later layers are trained on the new task. The frozen layers act as feature extractors, transforming the input data into meaningful representations. This approach works well when the new task shares similar low-level features with the original task.

**Fine-Tuning**: In fine-tuning, the entire pre-trained model is further trained on the new task with a smaller learning rate. This approach allows the model to adapt to the specific characteristics of the new data or task while retaining the knowledge gained from the pre-training phase.
