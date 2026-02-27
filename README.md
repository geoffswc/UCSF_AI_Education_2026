# Industry Archives Text Analysis Workshop
## UCSF_AI_Education_2026


## Overview

This repository supports a hands-on workshop exploring how the same text-based archival dataset behaves under multiple analytical approaches:

1. A browsing application (curated interface)
2. Conversational AI (e.g., ChatGPT)
3. Structured tools (Python and/or SQL)

The goal is not simply to extract findings from archival documents.  
The goal is to examine how **different analytical environments shape interpretation, structure, and scale**.

Participants are encouraged to choose their level of technical engagement and reflect on what changes across approaches.

---

## Why This Exercise?

Text archives can be explored in many ways:

- Through a purpose-built interface that organizes and filters content
- Through conversational AI that rapidly summarizes and interprets
- Through structured workflows that explicitly define schema, parsing, and reproducibility

By analyzing the same dataset using different methods, we can observe:

- How structure is exposed (or hidden)
- What assumptions each tool makes
- When conversational analysis is sufficient
- When scale or precision requires structured workflows
- How workflow choices affect reliability and transparency

This is a structured but flexible experiment in practical research methods.

---

## What You Will Do

1. Explore a tobacco industry dataset from the UCSF Industry Documents Library.
2. Analyze it using one or more approaches:
   - The browsing app
   - LLM-only (ChatGPT)
   - Python and/or SQL
   - A hybrid workflow (AI-assisted coding)
3. Identify:
   - 2–3 substantive observations about the dataset
   - Your chosen tool mix
   - One methodological limitation or concern

The focus is both analytical and pedagogical:
How do these tools behave in a research or classroom setting?

---

## Available Tools

### 1. Curated Browsing Application

The Industry Documents Library offers an interface that allows document exploration, filtering, and viewing, along with historical context for the collection. 

Use this to:
- Gain insight from achivists, researchers, and industry analysts
- Quickly scan content
- Identify promising subsets
- Observe metadata structure

Consider:
- What structure does the interface expose?
- What structure does it abstract away?

https://www.industrydocuments.ucsf.edu/tobacco/collections/marketing-to-youth-msa-collection/

---

### 2. Conversational AI (ChatGPT)
Upload or paste selected text into ChatGPT to:

- Summarize
- Extract themes
- Compare tone
- Generate structured output

Be aware that:
- Structure may need to be clarified explicitly
- File format (e.g., pipe-delimited) must sometimes be specified

For this workshop, we'll use ChatGPT from UCSF Enterprise OpenAI. However, you can follow along with other GenAI systems.

**Dataset**: Marketing to Youth MSA Collection
- https://ucsf.app.box.com/v/IDL-DataSets/file/484599836694

---

### 3. Structured Analysis (Python / SQL)

Load the dataset directly to:

- Explicitly define delimiters
- Confirm headers and row counts
- Aggregate, filter, and query at scale
- Build reproducible workflows

For this workshop, we will use Google Colab, Python, and SQL. 

**Dataset**: Marketing to Youth MSA Collection
- https://ucsf.app.box.com/v/IDL-DataSets/file/484599836694

## About the Instructor

Geoff Boushey is a Data Science Specialist with the UCSF Library’s Data Science and Open Scholarship Group. He teaches practical programming and data analysis workshops for faculty, staff, and students, including Python, SQL, Unix, machine learning, and AI-based document analysis. His work focuses on building reproducible, cloud-based pipelines that help researchers analyze large collections of text, video, image, and audio data from the UCSF Industry Documents Library and other archival collections.

In addition to teaching, Geoff designs AI-assisted workflows that generate transcripts, metadata, and structured datasets for research use. Before joining UCSF, he worked in analytics and software development roles at Sun Microsystems, UC Berkeley, and Software Startups. He holds an MS in Industrial Engineering and Operations Research from UC Berkeley.

## AI Use Disclosure

This session includes the use of **ChatGPT Enterprise (UCSF deployment, GPT-4 class model, February 2026)**.

**To prepare material for this session, AI was used for**:
- Drafting example prompts and code snippets  
- Testing document parsing and analysis workflows  
- Assisting in preparation of selected written materials  
- Live demonstration of text analysis methods during the workshop  

**As an instructional tool**:
- Generative AI will be used as an analytical tool to demonstrate document analysis techniques on archival datasets.
- All AI-generated outputs included in the presentation were reviewed, tested, and verified by the instructor prior to inclusion. Code examples were executed and validated in Python/SQL environments where applicable.
- Demonstration materials are limited to publicly available archival datasets.
- Learners will be informed when AI-generated content is being demonstrated during the session.
