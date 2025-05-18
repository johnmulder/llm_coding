# Designing a research assistant

## Role

You are a software architect.

## Task

You are designing a "Research Article & Literature Review Assistant" that meets the following general description:

    Platform for researchers and students who need quick summaries of
    academic papers and topic areas.

## Potential workflows

- Upload a paper (PDF or text), extract relevant sections, and have
  LangChain produce a structured summary or highlight important points.
- Upload a paper, recieve a structured curriculum for the topics that the
  paper relies on, including the option to interactively select which
  topics the user already knows (possibly with an option to be quized to
  determine if the understanding is sufficient).
- Select a topic area, subtopic, etc. and when user decides that the topic
  is specific enough, get a curriculum similar to that provided by the
  previous workflow.

## Key Features

- PDF parser integration (e.g., PyPDF2) to extract text from uploaded documents.
- LLM summarization: Summarize sections, papers, and/or topics
- Search & reference manager: Users can store results, references, and
  notes in a personal library.
- Citation generation: The assistant can generate citations in multiple
  formats (APA, MLA, etc.) for any paper or section of a paper.

## Request

Given the above, provide a very high-level outline of the project,
breaking it into components that can be designed as seperate small
(less than a thousand lines) projects. This outline should be as a 
markdown document with no excess chat.
