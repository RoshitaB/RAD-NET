# !! Paper for Review at AAAI 2024 Imageonics

- The paper introduces an innovative approach to multimodal understanding in radiology, emphasizing Visual Question Answering (QA) systems.

**Objectives:**

1. **Medical Diagnosis Enhancement:**
    - Focusing on the improvement of medical diagnosis through RadNet, a multimodal deep learning model tailored for answering medical image-related questions.

2. **Transformer Encoder-Decoder Architecture:**
    - Introducing an approach based on a transformer encoder-decoder architecture to facilitate multimodal understanding.

3. **Image and Text Representation:**
    - Utilizing the vision transformer (ViT) model to extract image features and a textual encoder transformer for embedding questions.

4. **Concatenation of Representations:**
    - Concatenating visual and textual representations to enhance the overall understanding of medical images.

5. **ViT-ROBERTA Configuration:**
    - Demonstrating the effectiveness of the ViT-ROBERTA configuration, fused by a Lambda Layer, with the highest validation accuracy at 58.87% and ROC of 0.64 on the VQA-RAD dataset for closed-ended questions.

6. **Future Considerations:**
    - Outlining future considerations, including the exploration of goal-oriented datasets and addressing new aspects such as contextual information and domain-specific inference.
