---
layout: default
---

# Week 04

[← Back to Home](../index.md)

# Experiment 4: Artificial Intelligence

# In-Class Activities
Overview

Explore local and cloud-based AI workflows. These activities introduce the practical and ethical dimensions of working with AI, building on the ideas about data representation from previous experiments.

## Activity 1: Local AI with Ollama

Download and install OllamaLinks to an external site., then open your terminal. Download a small model:

ollama pull qwen3:1.7b

Once downloaded, start a conversation:

ollama run qwen3:1.7b

You're now chatting with an AI model running entirely on your own computer. No data leaves your machine.

Spend 10 minutes exploring. Try describing data from a previous experiment and asking for visualisation ideas. Ask it to write code. Try something you'd normally ask ChatGPT and compare the response. Try to find its limits.

Pay attention to what feels different: the speed, the quality, the tradeoff between sovereignty and capability. Type /bye to exit.

## Activity 2: Cloud AI with NotebookLM

Open NotebookLMLinks to an external site. with your University Google account and create a new notebook.

1. Build your notebook: 
Add sources that represent your experimentation so far on the course. Mix your own work with other sources: your Making Journal URL (GitHub Pages), practitioner websites that resonated with you, data sources or APIs you are curious about, and other creative work you have made or are interested in.

2. Frame your research:
Before generating artefacts, add a short document to shape the AI's focus. Open a text editor and write three sentences: the experiment you found most interesting and why, a theme or idea you keep coming back to, and something you're curious about but haven't had a chance to explore yet. Save this as context.md and add it to your notebook.

3. Explore in the chat:
Use the chat to ask questions about your sources. Try prompts like:

"If my sources were documentation for a design project, what would the final outcome be?"
"What do my sources suggest I care about?"
"Identify a provocation hidden in my sources"
"What would someone who disagrees with the ideas in my sources argue?"
"Which of my sources are you drawing on for that, and which are you ignoring?"
Follow up on anything interesting. Ask it to elaborate, challenge it, push in a different direction.

4. Generate the Audio Overview:
Find the Audio Overview option and generate it. Once it's ready, listen with headphones. While you listen, make notes: what did it pick up on that surprised you? What did it get wrong? How does hearing your work discussed feel different from reading the chat responses?

# Independent Study: AI-Assisted Data Exploration
Overview

Choose a public dataset about life in Aotearoa New Zealand and use cloud-based AI tools to explore, interpret, and represent the data. The challenge is to go beyond a single prompt, working through sustained dialogue with the AI, directing its decisions, and critically evaluating its outputs.

Step 1: Find a Dataset

Browse the open data catalogue at catalogue.data.govt.nzLinks to an external site. and find a dataset that interests you. Look for something with a downloadable CSV file that is small enough to upload into a cloud AI tool (aim for under 10MB, or a few thousand rows).

Choose something you find genuinely interesting. The data should relate to a real aspect of life in Aotearoa that you would want to explore further.

Step 2: Understand the Data

Upload your CSV into a cloud AI tool (e.g. CoPilot, Gemini, NotebookLM, ChatGPT) and have a conversation about it. Ask the AI to explain what is in the dataset: what the columns mean, what the values represent, how much data there is, and what is missing or incomplete.

Consider:

What stories might this data contain?
What questions could it answer?
What biases or gaps are present?
Who collected this data, and for what purpose?

Step 3: Design Multiple Representations

Ask the AI to produce a visualisation of the data, but don't accept the first output. Direct the AI: specify the form, the visual encoding, the audience, the story you want to tell. Iterate through at least three distinctly different representations of the same data. These could be code-based (e.g. p5.js or HTML), textual, visual, or even prompts for physical/analogue translations.

For each version, make deliberate design decisions about what to change. You might vary the format (chart, map, interactive page, narrative text), the visual encoding (colour, size, position, shape), or what subset of the data to foreground.

Step 4: Critically Evaluate

Look at the representations you've produced and reflect on the AI's design choices:

What did the AI default to? (e.g. bar charts, blue colour schemes, generic titles)
What did you have to override or redirect?
What assumptions did the AI make about the data or the audience?
Which representation is the most interesting, and why?
What would you do differently if you were building this without AI?
Document Your Process
To capture the full scope of your practice, each entry in the Making Journal must include a mix of visual and textual evidence, such as sketches, screenshots, GIFs, diagrams, process notes, instructions and reflections.

Items on the course Reading List for this week include the introduction to Data Feminism by Catherine D'Ignazio and Lauren F. Klein, and a talk by Kirikowhai Mikaere on Māori data sovereignty. Engage with both of these and draw on them in your reflections.

Include reflective writing that addresses the following:

What dataset did you choose, and why?
How did AI tools help you understand the data? What did they miss?
What design decisions did you make in directing the AI, and what did you learn from this process?
How do the different representations of the same data change what a viewer might understand?
What questions do D'Ignazio and Klein's ideas raise for your work with this dataset?
How does Mikaere's framing of data as a strategic asset for Māori development challenge or inform how you think about the dataset you chose?
What was your experience of working with AI as design tool?
What would you develop further with more time?
Any other reflections?

# Documentation 

*Include your documentation for the week. Devise your own structure of headings relevant to the required tasks and your process.*

## Images & Media

*Use the format below to embed images from your assets folder:*

`![Alt text](../assets/week-01/your-image.jpg)`
`*Your caption here*`

*The text inside the square brackets is alt text (a description for accessibility), not a visible caption. To add a caption, place a line of italic text below the image.*

## AI Usage Statement

*Document any use of AI tools under an AI Usage Statement heading. Explain which tools you used and describe how you used them. Reference any AI-generated content (see [QuickCite](https://auckland.libguides.com/referencing-generative-ai-tools) for guidance).*
