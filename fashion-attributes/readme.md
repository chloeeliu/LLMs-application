
# AI Fashion Insights: LLMs Attribute Recognition and CLIP-Enhanced Product Recall

## Introduction

 ![plot](https://github.com/chloeeliu/LLMs-application/blob/88cac3b68fd5ae6255f35664eddbd33339ded823/image/attributes/1.png)

This project was designed to leverage cutting-edge AI technologies to enhance our understanding and adaptation to fashion industry trends. By recognizing and categorizing fashion attributes from competitors' products  using LLM and predicting trends with statistical model, alongside employing CLIP for product recall based on top search keywords, we aimed to refine our product operation strategies to better align with market demands. 

This approach ensured a proactive stance in a rapidly evolving retail landscape, utilizing deep learning and natural language processing to maintain a competitive edge.


![plot](https://github.com/chloeeliu/LLMs-application/blob/88cac3b68fd5ae6255f35664eddbd33339ded823/image/attributes/2.png)


## Achievements

![plot](https://github.com/chloeeliu/LLMs-application/blob/88cac3b68fd5ae6255f35664eddbd33339ded823/image/attributes/3.png)


1. High Accuracy in Attribute Extraction: Successfully extracted and mapped key product attributes from competitor imagery and titles with prompt engineering, few-shot learning, and supervised fine-tuning, achieving 95% accuracy across 78 different attributes.

2. Agent System Integration: Break down the task and implemented an agent system that coordinated cv, LLMs, Clip models and integrated feedback, which enhanced overall accuracy by an additional 5%.

3. AB Testing Validation: Conducted AB tests to validate the model's product selections, resulting in a 2.5% higher exposure rate compared to the general market during the same period.

![plot](https://github.com/chloeeliu/LLMs-application/blob/88cac3b68fd5ae6255f35664eddbd33339ded823/image/attributes/4.png)

some badcase:

- llm omit the regular attribute value like all season leave null for attribute season.

- mistake print with clothes texture

- can’t detect material with image, always return “seems like cotton…“


## Technologies Used

 ![plot](https://github.com/chloeeliu/LLMs-application/blob/88cac3b68fd5ae6255f35664eddbd33339ded823/image/attributes/5.png)


- CLIP: Utilized for trend mining and relevant product recall based on keyword searches

- GPT, Gemini and Claude: Employed for prompt engineering, few shot learning and fine tuning, ensuring high accuracy in attribute recognition.

- Supervise Learning and Reinforcement Learning:  Applied to refine the learning processes of our AI models such as Idefics2, improving their accuracies

 

 

## Challenges Faced

- Complexity in Multimodal Integration: Integrating and synchronizing various multimodal tools posed significant challenges, especially in maintaining consistency across different types of data.

- Feedback Loop Implementation: Developing an effective agent system that could handle real-time feedback and adjust the model accordingly required careful planning and testing.

- Knowledge Graph Management: Ensuring the knowledge graph was comprehensive and up-to-date involved complex data management and frequent updates.
