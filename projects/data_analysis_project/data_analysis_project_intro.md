# Data Analysis Project

## About the project

This project gives your group practice with the work involved in a real data-driven investigation. In the first data analysis project, you reverse-engineered a story that had already been reported. Here, you will identify a story opportunity of your own by analyzing data that can support a novel angle or further reporting, even if journalists have used similar data before.

Your group will develop newsworthy questions, acquire and prepare data, analyze it in R, and report on the subject to understand what the results mean and what they cannot tell you. You will present your work in a reproducible data notebook and write a story memo that could serve as the starting point for further reporting.

## Group project

You will work in a randomly assigned group. Your group will submit shared project work, although members may take responsibility for different tasks. Everyone is expected to contribute a comparable amount of work. If a group member is not contributing, I may remove that person from the group and assign them an individual project.

## How to approach the project

Your group will select a **core dataset** and develop a set of newsworthy questions that can be investigated with it. You will also identify **supplementary data** that can put the core data in context or help answer a question the core data cannot answer on its own.

As you work, your group should:

- Identify the information needed to investigate your questions and locate appropriate data.
- Learn what the data records, how it was collected, and what its limitations are.
- Clean and prepare only the data needed for your analysis, documenting decisions that could affect the findings.
- Use R in a reproducible notebook to work through your questions step by step.
- Use supplementary data where it meaningfully adds context, comparison, or a new dimension to the analysis. Explain why it belongs and how it connects to your questions.
- Conduct document review, interviews, or other reporting as needed to assess what the analysis can support.
- Produce a clear, edited notebook that explains the data, the analysis, and the findings.

## Datasets

Choose one of the options in the separate [suggested core datasets list](suggested-core-datasets.md), or propose another sufficiently rich dataset for approval. Keeping that list separate makes it easier to update suggestions without revising these project instructions. Before committing, check that the data are accessible, documented, and appropriate for the time available. Some datasets are large or split across files; narrow them to a defensible scope before analysis.

Your project must use a core dataset **and at least one relevant supplementary dataset**. Supplementary data should help answer a question or place the core data in perspective; it should not be added just to create a join. For example, you might use American Community Survey (ACS) data to compare local rates with population, income, housing, or demographic characteristics. When the core data are a single file, your supplementary dataset must be joined to it to investigate a question that cannot be answered from the core file alone. If a core source already consists of related tables, discuss with me how you will add a genuinely independent source of context.

You are responsible for checking the source's documentation, definitions, update date, and terms of use. If the source changes over time, record which version or reporting period you used.

### Possible supplementary data

Supplementary data can come from the [U.S. Census Bureau's ACS](https://www.census.gov/programs-surveys/acs/data.html), [Census geographic boundary files](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html), or another credible source related to your questions. Possible uses include:

- Add population denominators to calculate rates rather than comparing raw counts.
- Compare places by income, housing, age, race and ethnicity, or other relevant characteristics.
- Add geographic boundaries to map or aggregate records consistently.
- Compare the core data with a second measure, agency dataset, or historical series.

Choose a geography and time period that can be matched reliably. Explain any differences in definitions, coverage, or timing. A correlation or geographic overlap does not by itself show that one factor caused another.

## Deliverables, deadlines, and grades

The project is worth **20 percent of your final grade**.

### Deliverable 1: Questions and dataset proposal — 10 percent

Post to your group's forum and:

- Identify your proposed core dataset and link to its source.
- List five newsworthy questions the group could investigate.
- Explain why each question matters and whether journalists have reported similar findings elsewhere.
- Identify a likely supplementary dataset and explain what context or analytical value it could add. You may revise this choice as you learn more about the data.

### Deliverable 2: Initial notebook — 10 percent

Submit a draft R Markdown notebook (`.Rmd`) through GitHub that:

- Loads and prepares the core dataset for analysis.
- Includes basic exploratory analysis demonstrating that you understand the data.
- Describes the supplementary data you plan to use, including its source and how you expect it to relate to the core data.

### Deliverable 3: Analysis draft — 20 percent

Submit an updated draft notebook through GitHub that:

- Loads and prepares the data you plan to use.
- Shows meaningful progress on at least two of your proposed questions.
- Includes initial work with the supplementary data, or explains a specific data-access or compatibility problem and a revised plan.

### Deliverable 4: Final notebook and story memo — 50 percent

Submit through GitHub:

- A final R Markdown notebook (`.Rmd`) that loads, cleans, and analyzes the data; explains the steps and findings in context; and runs from beginning to end without errors.
- A 500-word story memo included in the notebook. The memo instructions appear below.

The notebook should be clean, accurate, and edited as carefully as work prepared for publication. Explain important analytical choices and limitations, not just what each line of code does.

### Deliverable 5: Peer review — 10 percent

Submit an anonymous review of your own and your teammates' contributions. Only I will see the reviews. I will consider them alongside my own observations when determining this part of the grade. The review is intended to ensure that everyone contributes to the project.

## Final story memo

Write the memo as a pitch to a busy editor. Make the case for a story suggested by your analysis, explain what you found, and identify the reporting needed before publication. The memo should be **500 words, plus or minus 10 percent**.

Include:

- **A strong opening.** Lead with the most interesting supported finding or story possibility. Do not begin by describing the steps you took in R. Explain how your finding relates to previous reporting on similar questions. Do not overstate what your analysis shows.
- **The relevant results.** Summarize findings that support the proposed story and any related results worth pursuing. Say whether the findings appear new or offer a local angle on a story reported elsewhere.
- **The data's strengths and limitations.** Explain what the data can show and what it cannot. Include how the supplementary data affected your analysis and any limits in how the sources can be compared or joined.
- **How you would verify the findings.** Name the specific documents, data, interviews, or other checks you would use. If your analysis raises questions about the actions of a public or private figure, say whom you would contact for a response.
- **How you would report the story.** Identify people to contact and places to visit, when relevant, and explain how reporting would show readers the real-world stakes.

Keep the focus on the story and what it would take to report it. Editors do not need a step-by-step account of your analysis process.

## Evaluation criteria

| Criterion | Excellent | Good | Fair | Poor | Unacceptable |
|---|---|---|---|---|---|
| **Relevance and exploration** | The notebook and memo offer a deep, original, and newsworthy exploration of the topic. | The project answers most relevant questions, with room for further exploration. | Some questions are unanswered, insufficiently relevant, or not clearly newsworthy. | Most questions are not newsworthy or are only superficially explored. | The submitted work does not show a discernible question. |
| **Analysis: process and findings** | The code loads, cleans, and analyzes the data without errors and answers relevant questions. | The code includes some unnecessary steps or could present the answers more effectively, but the analysis works. | The code has a minor, readily fixable error, but the analysis is otherwise consistent and comprehensive. | The code does not run or includes steps that do not do what they are intended to do. | The analysis was not submitted. |
| **Analysis: context and explanation** | The notebook explains the data and important analytical choices, motivates and clearly explains the use of supplementary data, and accurately describes what the combined analysis can show. | The notebook is generally clear, but some explanations, the rationale for supplementary data, or the join could be clearer. | Sections lack useful explanation, or the supplementary data are weakly connected to the questions or joined without a clear rationale. | The notebook provides little explanation and does not meaningfully use relevant supplementary data. | The analysis was not submitted. |
| **Memo: content** | The memo is focused, well structured, engaging, and accurate about the data and findings. | The memo is clear and focused but includes some imprecision or overstatement. | Some sections or connections are unclear, but the memo remains understandable. | Structural problems make the memo difficult to follow. | The memo was not submitted. |
| **Memo: style and length** | The memo is within 10 percent of 500 words and has polished grammar and style. | The memo is within 15 percent of 500 words or has a few minor errors. | The memo is outside 15 percent but within 20 percent of 500 words, or has errors that sometimes affect understanding. | The memo is outside 20 percent but within 25 percent of 500 words, or has frequent errors that impede understanding. | The memo was not submitted. |
