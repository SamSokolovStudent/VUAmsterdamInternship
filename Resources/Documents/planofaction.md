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
> **note**
> Explain abbreviation PICO (Patient/Population/Problem, Invervention, Comparison/Control, Outcome measures)
> add link to NTR

It will employ Large Language Models (LLMs) and statistical models, as well as methods to recommend relevant graphs, models, and other papers for further research. 
This will largely be driven by a semantic search engine using a hot vector database to find the most relevant results from abstracts and papers.

The relevance and importance of the project lie in delivering a product that can make a genuine contribution to the Twinning project at VU Amsterdam and possibly broader general science.

The final application should also provide an overview of the entire corpus of articles that have undergone multiple filtering steps to ensure a higher quality selection of articles on the subject of twinning.


#### 1.1. Background
*A description of the background and context of the project.*
> **note**
> Maybe Nikki can help out for this subsection?

##### 1.1.1 Twinning
Monozygotic *vs.* dizygotic twins and how they occur in humans, but also in other (mammalian) animals.

##### 1.1.2 Generative AI
Semantic search engines, large language models, classification. 
We find ourselves in an era often described as 'the AI revolution.' 
Every week, revolutionary new papers are released featuring AI models, algorithms, and smart applications of both to accomplish tasks that previously required a high degree of complexity or a large IT department. 
This is all changing. New techniques based on transformer models and embeddings, like the infamous Large Language Models such as GPT-4 or LLaMa2, are altering how we think about gathering and searching for information.
> **Note**
> I don't know if this should be added here, but maybe finish off with a sentence like "Although this is a highly dynamic field, we choose..."

#### 1.2. Objectives
*What the project aims to achieve.*

The project aims to make it easier to conduct scientific research such as PICO's and meta-analyses, but also to do it at a higher quality standard. 
By simplifying the process, there is more time and space to gain deeper insights into specific topics.

## 2. Problem Statement
*The challenge or problem that will be addressed during the internship.*

The goal is to develop an application to assist the user (the scientist) in conducting a review. 
The data should be as clean as possible to optimize classification. 
We aim to implement the software as abstract as possible so that it can potentially handle other topics as well.

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

The workflow of the tool is summarized in the Workflow Diagram below.

#### 3.1. Research Design
*The type of research that will be conducted, such as qualitative, quantitative, experimental, etc.*

The research is a mix of qualitative, quantitative, and experimental research.

#### 3.2. Data Collection
*The methods and sources for collecting the required data or information.*

APIs from NCBI, PubMed, and arXiv will mainly be used to collect a large assortment of papers and abstracts. Theese resources will be queried by terms related to twinning. The result will be further cleaned by using ASReview.

#### 3.3. Database Setup and Analysis
*The approach for analyzing the collected data, such as statistical methods or software tools.*

> **note**
>  Here a subsubsection for generating the DB

**Modeling and Evaluation**
We will have to look at how different AI and statistical models handle training, fine-tuning, and evaluation.

**Visualization**
We want to visualize different forms of data and metadata with various graphs.

**Semantic Analysis**
We will use tools like spaCy and Elasticsearch for this.

## 4. Timeline
*An overview of the key milestones and deadlines.*

**Start of the Internship (September 2023):** In the first four weeks, the main task is to learn about the new technology that we'll be using for the project. This includes understanding different models, programming frameworks, online services (APIs), and software libraries. The goal is to find out which ones are reliable and suitable for our work, especially since technology in the field of artificial intelligence changes quickly. This initial learning phase will help us make a detailed plan for the rest of the internship.

**October 2023:** By October, the plan for the project should be complete. This means knowing how we'll gather data, what we're going to do with that data, and what the final product will look like. After this planning stage, we'll start building a database and collecting the information we need for the project. At this point, we'll also start figuring out how to clean and sort the data in a useful way.

**November 2023:** November is when we'll start building the actual application. The first step is to set up a database that includes all the cleaned and sorted data. Then, we'll work on adding a feature to the application that allows it to search through this data in a meaningful way (this is known as a semantic search engine). After this, we can start looking at the full set of data to plan our statistical analysis. Understanding the various statistical methods that could be used will take some time, as we want to select the most suitable ones for our project. However, once understood, implementing these methods into the application should be relatively straightforward. This part might be challenging due to the learning curve involved with the statistical methods, but it should be doable within the month.

**December 2023:** The aim for December is to finish the application. It should be able to search through academic papers in a way that helps people perform systematic reviews, using both graphs and artificial intelligence to assist the process. Once the application is working, we'll start looking at the results it produces and use those in a final report about the project and the internship. The goal is to complete this report before the end of December, so there's time to make any final adjustments before the holidays.

**End of the Internship (January 2024):** At the end of the internship, there should be a working application and a complete report about the project. The report will be reviewed and any necessary improvements will be made. Once that is done, it will be submitted for final evaluation. With the project finished and the report handed in, the internship goals will have been met, offering valuable learning and experience in the field of AI.

![Workflow Diagram](https://github.com/SamSokolovStudent/VUAmsterdamInternship/blob/main/Resources/Documents/workflow_diagram.png?raw=true){fig:Workflow}

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
