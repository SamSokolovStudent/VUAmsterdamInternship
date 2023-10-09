# Plan of Action

*A brief introduction about the relevance and importance of the project.*

In the realm of scientific inquiry, systematic reviews serve as invaluable tools for encapsulating the current understanding within a specific field. They often synthesize a broad range of results and may even aggregate data from multiple studies via meta-analysis for a more comprehensive view.

This project is being carried out at the Department of Biological Psychology at VU Amsterdam, responsible for the maintaining of the Netherlands Twin Register (NTR). One of the primary objectives of the NTR is to clarify the biological underpinnings of twinning—both its occurrence and implications. Consequently, this constitutes the core subject matter of the current project.

For further information on the NTR, you can visit their official [website](https://tweelingenregister.vu.nl/).

To support the process of performing a systematic literature review on twinning, we'll leverage generative artificial intelligence (AI). Specifically, the project aims to harness various AI models for tasks such as meta-analyses and guiding future research endeavors in accordance with the PICO framework, which stands for Patient/Population/Problem, Intervention, Comparison/Control, and Outcome measures.

The project will harness the capabilities of Large Language Models (LLMs) and will largely be driven by a semantic search engine using a vector database to find the most relevant results from abstracts and papers. This entire operation is controlled by a semantic search engine, which utilizes a vector database to sift through abstracts and papers, pinpointing the most relevant results. In addition, statistical methods are applied across the entire database to uncover anomalies and discern patterns, providing a deeper layer of analytical insight.

The value of this endeavour lies in its potential to effect a substantive contribution to the study of fertility pertaining to twinning at VU Amsterdam, and perhaps even to extend its impact to the wider scientific community.

Ultimately, the final application aims to present a meticulously curated corpus of articles. These would have undergone rigorous filtering processes to yield a selection of high-quality articles focused exclusively on the subject of twinning.

#### 1.1. Background
*A description of the background and context of the project.*

##### 1.1.1 Twinning
The subject of twinning holds a particular allure, often steeped in both biological intricacy and cultural fascination. While the basics like monozygotic and dizygotic twinning are well-understood, the role of fertility factors adds an extra layer of complexity. These factors, which include aspects like maternal age and hormonal fluctuations, influence the likelihood of twinning. Our larger project seeks to dig deeper into these fertility factors to identify which are most influential in twinning occurrences, not just in humans but also across different mammalian species.

Existing research primarily explores either twinning or fertility within specific species, but rarely both across species. A notable exception is a study focused on aggression, which may serve as an inspiration for this project. The end goal is to discover papers where experimental research overlaps across species but hasn't been individually examined for such intersections.

Specific attention is directed towards cattle for two main reasons: first, extensive research has been conducted in the livestock industry with a profit motive for multiple births; second, a significant portion of a genetic region known to influence twinning (and possibly fertility) is shared between cattle and humans.

The correlation between fertility and the likelihood of multiple births remains ambiguous. While twinning has been traditionally seen as a form of 'super-fertility,' some studies suggest that it is possible to experience reduced fertility while still having higher chances of multiple births. For instance, the release of the FSH hormone, commonly observed when women quit smoking, could be a factor in multiple ovulations.

Studies that are commonly associated with twinning but not directly relevant to fertility will be treated as 'negative filters' in our search for relevant literature. For example, twins are often used in hereditary studies based on the ACE model and broad-sense heritability. These types of studies may appear in the dataset but are not directly pertinent to our investigation.

Also, epigenetic studies often target identical twins exhibiting discordant traits to explore the impact of a single factor on epigenetic expression. However, our research puts the emphasis on dizygotic twins, making such studies less relevant for our purposes.

By focusing on these specific elements and filtering out the non-relevant ones, the project aims to address gaps in current scientific understanding.
##### 1.1.2 Generative AI
As we traverse what's commonly termed 'the AI revolution,' the proliferation of ground-breaking papers is ceaseless, each contributing revolutionary models and algorithms. Particularly noteworthy are advancements rooted in transformer architectures and embeddings, such as forefront Large Language Models like GPT-4 and LLaMa2. These are fundamentally altering our methodology for information retrieval and interpretation. Given the volatile nature of this field, the project remains agile, adapting to the latest in scientific discovery while adhering to current best practices.
#### 1.2. Objectives
*What the project aims to achieve.*

The project aspires to refine and facilitate scientific research, focusing specifically on PICO-based reviews and meta-analyses. The objective is twofold: to simplify these complex processes and to elevate the quality of their outcomes. This efficiency opens the door for researchers to delve more deeply into their areas of inquiry, providing a richer, more nuanced understanding of the subject matter.

## 2. Problem Statement
*The challenge or problem that will be addressed during the internship.*

The primary objective is to create a software application that effectively assists researchers in performing reviews. The software should be able to manage highly sanitized data to enhance classification algorithms. Additionally, we intend for the software architecture to be abstract enough to be versatile, allowing it to be repurposed for various research subjects.

#### 2.1. Main Question
*The central question or challenge of this project.*
Is it feasible for software leveraging generative AI to add meaningful value to the literature review process, specifically concerning the subject of fertility in twinning?

#### 2.2. Sub-Questions
*Specific questions or components that need to be addressed to answer the main question.*

1. What role does data visualization play in augmenting the usability of the tool?
2. Can the software execute meta-analyses, and if so, to what degree of accuracy?
3. Is the user interface visually appealing and conducive to an efficient workflow?
4. How can the software handle potential biases in the literature it reviews?
5. How scalable is the tool when dealing with an increasing volume of data or a diversifying range of topics?
6. Can the tool integrate with existing research databases or repositories?
7. What kind of adaptability is built into the software to keep pace with advancements in generative AI algorithms?

## 3. Method
*The approach and methodology that will be used to address the problem statement.*

Our objective is to deploy AI to augment scientific research; the methodology is therefore crucial. The plan is to harness the capabilities of Large Language Models (LLMs) in conjunction with statistical techniques to refine the comprehensibility and analyzability of scientific texts. To ensure the reliability of AI-generated insights, a multi-layered validation strategy involving cross-referencing with established literature and expert consultations will be employed.

For a graphical representation of the tool's operational flow, refer to the Workflow Diagram below.

![Workflow Diagram](https://github.com/SamSokolovStudent/VUAmsterdamInternship/blob/main/Resources/Documents/workflow_diagram.png?raw=true)

#### 3.1. Research Design
_Framework and Scope of the Research Effort._

The research integrates qualitative, quantitative, and experimental methodologies, each serving a distinct purpose.

- Qualitative methods will be used for initial concept validation and for interpreting user feedback on the tool's efficacy and usability.
- Quantitative approaches will handle the numerical evaluation of the tool, including the accuracy and reliability of AI-generated insights and statistical models.
- Experimental methods will involve controlled tests of the tool's capabilities and limitations, specifically in the context of twinning and associated fertility factors.

The scope aims to evaluate not just the tool's efficiency in literature review but also its adaptability to other research domains and its reliability in generating actionable insights.
#### 3.2. Data Collection
_Specifications for procuring the necessary data or information._

Data will primarily be harvested through APIs from repositories like NCBI, PubMed, and arXiv. These databases will be queried using terms that are pertinent to twinning. Subsequent to initial data collection, an additional layer of sanitization will be performed using ASReview.

#### #### 3.3. Database Setup and Analysis
_Strategies for Data Organization and Analysis._

**Database Generation** 

**Modeling and Evaluation** 
Different AI and statistical models will be used to train, fine-tune, and evaluate the data. Rigorous metrics will ensure the effectiveness of the models in retrieving relevant and accurate information.

**Visualization** 
Data and metadata will be represented visually through graphs to enhance comprehension and facilitate insightful interpretation, leveraging tools like Seaborn and D3.js.

**Semantic Analysis** 
Semantic analysis will be performed using specialized tools like spaCy and Elasticsearch to generate meaningful insights and relationships within the data. This step is crucial for the nuanced topic of twinning and associated fertility factors.

## 4. Project Timeline
*An overview of the key milestones and deadlines.*

**Start of the Internship (September 2023):** The initial four weeks are earmarked for technology onboarding. This entails familiarizing ourselves with various models, APIs, and software libraries critical to the project. Given the rapid shifts in AI technology, this phase serves as a cornerstone for informed planning for the internship duration.

**October 2023:** By this month, our project blueprint should be solidified. It will encompass data acquisition strategies, data utility plans, and a vision for the final product. Post-planning, we will commence the database construction and data collection phases. Concurrently, we'll delve into effective data cleaning and organization techniques.

**November 2023:** This month focuses on application development. We will first populate a database with the curated data. Next, we implement the semantic search engine, facilitating meaningful data retrieval. This sets the stage for comprehensive statistical analysis. While mastering the appropriate statistical methodologies may present a steep learning curve, implementation into the application is expected to follow smoothly.

**December 2023:** December aims to finalize the application, capable of aiding users in executing systematic reviews with graph-based and AI-backed support. Upon application completion, we'll scrutinize its outputs for inclusion in our final project report. The objective is to wrap up this report by month's end, allowing for any last-minute tweaks pre-holidays.

**End of the Internship (January 2024):** By the internship’s conclusion, we aim to have both a fully operational application and a comprehensive project report. Post-review modifications will be executed as needed before the report is submitted for final assessment. With the project and report concluded, we will have successfully met our internship objectives, gaining invaluable insights into AI's transformative capabilities.
## ## 5. Resources
_Essential Instruments and Software for Project Implementation._

- **Programming Language**: Python
- **Data Visualization Tools**: Seaborn, D3.js
- **Natural Language Processing**: Langchain
- **Database Management**: Vector Store and Generic DB using ChromaDB
- **Containerization**: Docker
- **Hardware**: GPUs and TPUs for computational tasks
- **Datasets**: Specific to the domain of twinning research
- **AI Models**:
    - Meta's LLaMa2
    - Meta's Bart-Large-MLNI

## 6. Risks and Challenges
_Possible obstacles or problems that may arise and how to deal with them._

- **Data Quality**: Ensuring the integrity of sourced data is critical. Any inconsistencies could be rectified through rigorous pre-processing and validation with human evaluation or automated verification against trusted databases.
- **Model Biases**: AI models can inherit biases present in their training data. To mitigate this, results will be cross-referenced with unbiased sources and expert consultations.
- **Computational Resources**: Heavy machine learning computation tasks may require significant resources. This may be offloaded from a local machine onto a cloud-based solution or server as an alternative.
- **Interpretation of Data**: The complexity of scientific data may make interpretation challenging. Collaboration with people experienced with statistics will be sought for meaningful insights and cross referencing results.
## 7. Conclusion
*Summary and Subsequent Courses of Action.

The project aims to leverage advanced AI models and statistical methods to create a versatile tool that aids in the conduct of rigorous scientific literature reviews, with an initial focus on twinning research. We've identified the essential resources and outlined potential challenges, devising strategies to mitigate them. The next steps include finalizing the research design, initiating data collection, and entering the development phase.*

## 8. Planning

**October 2023**
- Week 1: Finalize the project blueprint, including data acquisition and data use plans.
- Week 2: Begin the database design phase and setup.
- Week 3: Commence initial data collection.
- Week 4: Start developing techniques for data cleaning and validation.

**November 2023:**
- Week 1: Complete database setup with cleaned and sorted data.
- Week 2: Implement the semantic search engine for effective data retrieval.
- Week 3-4: Focus on the selection and implementation of statistical analysis methods.

**December 2023:**

- Week 1: Finalize application features.
- Week 2: Initiate application testing and gather preliminary results.
- Week 3: Draft the initial project report.
- Week 4: Revise application or report based on early feedback.

**January 2024:**

- Week 1: Finalize and submit the project report for initial review.
- Week 2: Make any last-minute adjustments based on review feedback and submit the final report for the conclusion of the internship.