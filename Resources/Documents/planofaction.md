# Plan of Action

*A brief introduction about the relevance and importance of the project.*

In science, (systematic) reviews are often conducted to summarize the current state of affairs within a specific topic. 
This often includes an overview of results, where data from different sources can even be combined through meta-analysis.

This project is being carried out at the Department of Biological Psychology at VU Amsterdam, which manages and maintains the Dutch Twin Register (NTR). 
A key objective of the NTR is to better understand the biology of being or becoming a twin (known as "twinning"). 
Hence, this is the scientific subject of this project.

To support the execution of a (systematic) literature review on twinning, generative artificial intelligence (AI) will be used. 
The project focuses on utilizing generative AI in scientific literature, specifically applying various AI models 
for meta-analyses and shaping new research through the PICO structure. 
It will employ Large Language Models (LLMs) and statistical models, as well as methods to recommend relevant graphs, models, and other papers for further research. 
This will largely be driven by a semantic search engine using a hot vector database to find the most relevant results from abstracts and papers.

The relevance and importance of the project lie in delivering a product that can make a genuine difference in the Twinning project at VU Amsterdam and possibly broader general science.

The final application should also provide an overview of the entire corpus of articles that have undergone multiple filtration steps to ensure a higher quality of articles on the subject of twinning.


#### 1.1. Background
*A description of the background and context of the project.*

##### 1.1.1 Twinning
Monozygotic *vs.* dizygotic twins and how they occur in humans, but also in other (mammalian) animals.

##### 1.1.2 Generative AI
Semantic search engines, large language models, classification. 
We find ourselves in an era often described as 'the AI revolution.' 
Every week, revolutionary new papers are released featuring AI models, algorithms, and smart applications of both to accomplish tasks that previously required a high degree of complexity or a large IT department. 
This is all changing. New techniques based on transformer models and embeddings, like the infamous Large Language Models such as GPT-4 or LLaMa2, are altering how we think about gathering and searching for information.

#### 1.2. Objectives
*What the project aims to achieve.*

The project aims to make it easier to conduct scientific research like PICO's and meta-analyses, but also to do it at a higher quality standard. 
By simplifying the process, there is more time and space to gain deeper insights into specific topics.

## 2. Problem Statement
*The challenge or problem that will be addressed during the internship.*

The goal is to develop an application to assist the user (the scientist) in conducting a review. 
The data must be as clean as possible to optimize classification. 
We want to implement the software as abstractly as possible so that it can potentially handle other topics as well.

#### 2.1. Main Question
*The central question or challenge of this project.*
Can software using generative AI contribute usefully to conducting a literature review on the subject of twinning?

#### 2.2. Sub-Questions
*Specific questions or components that need to be addressed to answer the main question.*

1. How does visualization contribute to the tool's usability?
2. Is the tool capable of performing some form of meta-analysis?
3. Does the output look appealing?
4. How is it determined whether the model output is optimal? ROC analysis or something similar?

## 3. Method
*The approach and methodology that will be used to address the problem statement.*

We want to use AI to assist us with scientific research, and our approach is crucial. Here's what we're going to do:

We'll use large language models (LLMs) and some statistics to make scientific texts easier to understand and analyze. We want to be sure that what the AI tells us is accurate, so we'll cross-reference the results with existing literature and consult experts.

#### 3.1. Research Design
*The type of research that will be conducted, such as qualitative, quantitative, experimental, etc.*

The research is a mix of qualitative, quantitative, and experimental research.

#### 3.2. Data Collection
*The methods and sources for collecting the required data or information.*

APIs from NCBI, PubMed, and arXiv will mainly be used to collect a large assortment of papers and abstracts.

#### 3.3. Analysis
*The approach for analyzing the collected data, such as statistical methods or software tools.*

**Modeling and Evaluation**
We will have to look at how different AI and statistical models handle training, fine-tuning, and evaluation.

**Visualization**
We want to visualize different forms of data and metadata with various graphs.

**Semantic Analysis**
We will use tools like spaCy and Elasticsearch for this.

## 4. Timeline
*An overview of the key milestones and deadlines.*

- **Week 1-2**: *Activities and goals for this period.*
- **Week 3-4**: *Delving deeper into the subject by orienting and reading more relevant literature.*

## 5. Resources
*The tools, resources, or software essential for the project.*

- **Python**
- **Seaborn, D3.js**
- **Langchain**
- **Vector Store**
- **Docker**
- Hardware: Such as GPUs and TPUs
- Datasets
- The AI models themselves:
	- Meta's LLaMa2
	- Meta's Bart-Large-MLNI

## 6. Risks and Challenges
*Possible obstacles or problems that may arise and how to deal with them.*

Data quality, model biases, computational resources, interpretation of data.

## 7. Conclusion
*A summary of the plan and the next steps.*

## 8. Appendices
*Any additional documents or sources that may be useful.*
