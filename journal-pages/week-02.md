---
layout: default
---

# Week 02

[← Back to Home](../index.md)



# Interactivity
## In-Class Activities
### Overview

Using p5.js, explore coding fundamentals and interactive DOM elements (buttons, sliders, text inputs) to create sketches that respond to user input. These activities build on the data drawing concepts from Experiment 1, shifting from physical to digital materials.

### Activity 1: Drawing with Code
Get familiar with the p5.js editor. Create a simple composition using at least three different shapes.

Use the p5.js referenceLinks to an external site. to find different shapes to try, e.g. rect(), triangle(), line(), ellipse().

Experiment with colour, size, and position. Try changing the order of your instructions — what happens?


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/QYeLpkTl1"
width="400"
height="400">
</iframe>


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/7JDsGft2B"
width="400"
height="400">
</iframe>


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/7VDVmqtJR"
width="400"
height="400">
</iframe>


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/Kyz_KJC-N"
width="400"
height="400">
</iframe>



### Activity 2: Make an Interactive Sketch

Using the DOM elements covered in class (createButton(), createSlider(), createInput()), create a sketch with at least two interactive controls that change something on the canvas.


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/XLU5K0lGp"
width="400"
height="400">
</iframe>



### Activity 3: Vibe Code an Interactive Sketch

Use an LLM (e.g. Gemini, ChatGPT, Claude) to help you build a more ambitious interactive sketch in p5.js.

Describe what you want in plain language.

Paste results into the p5.js editor and run the program.
Start with something simple, add features one at a time.
Ask for something you don't know how to code, and try to learn from the LLM.
Take note of what surprised you. What worked first time, what didn't, and what did you learn from reading the code?


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/hhgpNmyZ0"
width="450"
height="450">
</iframe>
The jumping ball (OpenAI, 2026).


## Independent Study: Interactive Data Portrait
### Overview

Take the data you collected for Experiment 1 and use it as the basis for an interactive p5.js sketch. The challenge is to translate your hand-drawn data portrait into something a viewer can explore, control, or manipulate through interactive elements.

### Step 1: Translate your data drawing into code

Look at the data you collected by hand last week. How could you represent it in a p5.js sketch? Think about which values are numeric, which are categories, and which are qualitative or hard to pin down.

You don't need to represent everything. Choose aspects of your data drawing that are most interesting to make interactive.


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/EJ7K1o7Rb"
width="420"
height="430">
</iframe>



### Step 2: Design your interactive visualisation

Create a p5.js sketch that includes interactive elements that allow the viewer to explore your data. Use DOM elements (e.g. buttons, sliders, text inputs, dropdowns, checkboxes) to give the viewer control over what they encounter.


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/x6tlOBG01"
width="420"
height="430">
</iframe>


### Step 3: Iterate

Test your sketch. Show it to someone else and observe how they use it. Refine the interaction based on what you observe.


<iframe 
src="https://editor.p5js.org/yuhaochen018/full/u6Cr3ckA1"
width="420"
height="430">
</iframe>
Iteration(OpenAI, 2026).


Document Your Process
To capture the full scope of your practice, each entry in the Making Journal must include a mix of visual and textual evidence, such as sketches, screenshots, GIFs, diagrams, process notes, instructions and reflections.

Include reflective writing that addresses the following:


- What data and visual aspects from Experiment 1 did you choose to work with, and why?

  *I've chosen to use the bar graph data from experiment 1. The data shows how many times I smiled during different periods of the day. This is quantitative data, so it's easier to represent using code. In p5, a bar graph can be created using simple rectangles. I also expressed the different colour categories from the original drawing in code, to represent different activities such as gaming, videos, and other categories. By using the same structure and colours, the coded version is fundamentally the same as my hand-drawn data portrait, while I've added the delivery of displaying numbers, which is more intuitive than the originally drawn graph.*

- How did you decide which interactive elements to use?

  *I chose the interactive elements based on the information I wanted the audience to notice. In this sketch, I used a checkbox to control whether the numbers and smiley face icons appeared on the chart. This allows the audience to switch between a simple visual chart and a more detailed numerical chart. The choice of DOM elements depends on what you want the viewer to focus on. My goal was to keep the chart simple at first, but allow viewers to choose to see more information. The checkbox is easy to use and helps viewers understand the data more clearly.*

- What can a viewer learn by interacting with your sketch that they couldn't from your hand-drawn portrait?

  *When the audience interacts with the view, they can explore the data. By clicking the checkbox, the data that the audience pays attention to will be more prominent. This makes it easier for the audience to understand the exact values of each part in the graphic. In the hand drawn version, the information is fixed and the audience can only see it. In the interactive version, the audience can control what they see. This makes the data easier to read and more attractive. It also helps to highlight the differences between time periods.*

- Did you use vibe coding or other tools in your process? What did you learn from this?
  *Yes, I use ChatGPT to help generate some p5 code. My case, such as bouncing ball and checkbox interactions, are both use the ChatGPT. During this process, I learned that understanding the logic of a program is important when you use AI tools. You need to make the prompt clear, or the result may not match what you want. For example, when I described bouncing balls, I forgot to mention that pressing the button again should pause the animation. Therefore, the running results did not match my expectations. In addition, not all AI codes are necessarily correct and often require updated.*
- What would you develop further with more time?

  *Later on, I want to learn some programming fundamentals, such as loops and conditional statements. I think these would be very useful for displaying more complex images in p5. In addition to these, I'd like to learn more about other scripts, in order to create richer digital patterns. At the same time, the DOM will also be a key focus for me, as this can generate more engagement with the audience, attracting their attention more towards the information I want to convey.*


  OpenAI. (2026). ChatGPT (Mar 13 version) [Large language model]. https://chat.openai.com/chat

