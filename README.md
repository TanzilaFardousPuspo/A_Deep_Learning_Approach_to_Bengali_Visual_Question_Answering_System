# A Deep Learning Approach to Bengali Visual Question Answering System
#Developed by Tanzila Fardous Puspo, 18 batch, CSE, CUET, Student ID: 1804121

## Visual Models: VGG19, VGG16, ResNet50, and Vision Transformer(ViT-B/16, ViT-B/32)
## Textual Models: BiLSTM, BiGRU, BanglaBERT, mBERT(multilingual BERT), XLM-R(XLM-RoBERTa), IndicBERT

### Description:
#### We used encoder decoder model that takes a medical question-image pair as input and generates
#### an answer as output. The encoder network consists of visual models such as
#### VGG19, VGG16, ResNet50, and Vision Transformer(ViT-B/16, ViT-B/32) that
#### extract prominent features from medical images and textual models like BiLSTM,
#### BiGRU, BanglaBERT, mBERT(multilingual BERT), XLM-R(XLM-RoBERTa),
#### IndicBERT to extract features from questions. Multimodal model was built by
#### combining visual and textual models using feature fusion technique. The decoder
#### generates answer word by word for the input image and the question. It operates
#### by generating probability distributions using Dense layer of answer vocabulary
#### size with Softmax activation.
