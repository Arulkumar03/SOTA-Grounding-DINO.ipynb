# SOTA-Grounding-DINO.ipynb
Zero-shot object detection with Grounding DINO

Most of the existing object detection models are trained to identify a limited set of pre-determined classes. Adding new classes to the list of identifiable objects requires collecting and labeling new data and retraining the model again from scratch, which is a time consuming and expensive process. The objective of Grounding DINO was to develop a strong system to detect arbitrary objects specified by human language inputs without the need to retrain the model, also known as zero-shot detection. The model can identify and detect any object simply by providing a text prompt.

Grounding DINO is a self-supervised learning algorithm that combines DINO with grounded pre-training. DINO is a transformer based method for object detection as discussed in the prior section. Grounded pre-training, on the other hand, involves associating phrases or words from a given text with corresponding visual elements in an image or video.

**Model Results**

![download (2)](https://github.com/Arulkumar03/SOTA-Grounding-DINO.ipynb/assets/117987790/e06009a1-bdaf-4752-8c76-efe4269c1c3c)

**To highlight a specific area in the image, I use directional indicators in text prompt.**

![download (3)](https://github.com/Arulkumar03/SOTA-Grounding-DINO.ipynb/assets/117987790/0a33aa53-d7d2-44bc-85af-dd99fa4111f8)

**Segmentaion output with Bounding Box**

![download (4)](https://github.com/Arulkumar03/SOTA-Grounding-DINO.ipynb/assets/117987790/4cfdf3c7-d522-4fc3-bb42-2578baf4b0e1)

**Segmentaion output without Bounding Box**

![download (5)](https://github.com/Arulkumar03/SOTA-Grounding-DINO.ipynb/assets/117987790/494d17f0-03cf-49cb-bc10-05d76ec25307)
