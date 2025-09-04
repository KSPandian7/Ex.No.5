# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

**Date : 04/09/2025**<br>
**Register Number : 212222240052**<br>

## Experiment:
To test and compare how different prompting patterns affect the performance of AI models across various task scenarios, with a focus on differences in output quality when using naïve vs structured prompts.

## Objective:
To analyze how Instructional Pattern prompts improve the quality, accuracy, and depth of AI-generated responses when compared to other patterns.

## Pattern: Instructional Prompting
**Definition:** <br>
The Instructional Pattern provides the model with direct, step-by-step commands or tasks to perform. It’s particularly useful in generating structured outputs, such as reports or procedures, making it ideal for automation and business use cases.

### Scenario Question:
```py
“How can small businesses use AI tools to grow?”
```


## OUTPUT:

### Outcome
<table border="1" cellpadding="8" cellspacing="0">
  <thead>
    <tr>
      <th>Prompt Pattern</th>
      <th>Prompt</th>
      <th>Output Summary</th>
      <th>Evaluation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1. Instructional Pattern</td>
      <td>“Explain step-by-step how a small business can use AI tools to grow revenue.”</td>
      <td>Lists five actionable steps including automation, analytics, and marketing personalization.</td>
      <td> High clarity, practical, structured.</td>
    </tr>
    <tr>
      <td>2. Zero-shot Prompting</td>
      <td>“How can small businesses use AI to grow?”</td>
      <td>Generic ideas without steps.</td>
      <td> Moderate quality, lacks depth.</td>
    </tr>
    <tr>
      <td>3. Few-shot Prompting</td>
      <td>“Example: A bakery uses AI to predict demand. Example: A retailer uses AI for customer queries. Now suggest more uses.”</td>
      <td>Creative and tailored ideas for different businesses.</td>
      <td> High relevance and detail.</td>
    </tr>
    <tr>
      <td>4. Chain-of-Thought Prompting</td>
      <td>“What steps should a small business take to adopt AI tools for growth?”</td>
      <td>Logical, phased breakdown from need identification to scaling AI adoption.</td>
      <td> Very high depth and reasoning.</td>
    </tr>
    <tr>
      <td>5. Active Prompting</td>
      <td>“Give me 5 specific AI tools small businesses can use to grow.”</td>
      <td>Lists tools like ChatGPT, Canva AI, HubSpot.</td>
      <td> High accuracy, low strategic depth.</td>
    </tr>
    <tr>
      <td>6. Directional Stimulus</td>
      <td>“Imagine you run a bakery. Which AI tool would you use first to grow and why?”</td>
      <td>Describes AI forecasting for cake demand.</td>
      <td> Relatable but narrow scope.</td>
    </tr>
    <tr>
      <td>7. Graph Prompting</td>
      <td>“Create a table to show AI tools by function.”</td>
      <td>Table of tools by function (e.g., ChatGPT for support).</td>
      <td> High structure, moderate analysis.</td>
    </tr>
    <tr>
      <td>8. Reverse-Engineered Prompting</td>
      <td>“Explain how a business can achieve 20% revenue growth using AI, starting from the result.”</td>
      <td>Starts with goal and backtracks through strategy.</td>
      <td> Strategic, practical.</td>
    </tr>
    <tr>
      <td>9. Multilingual/Multimodal</td>
      <td>“Explain AI growth use for small business in English and Hindi.”</td>
      <td>Same message in two languages.</td>
      <td> High accessibility and versatility.</td>
    </tr>
  </tbody>
</table>

### Summary:
<table border="1">
  <thead>
    <tr>
      <th>Prompt Pattern</th>
      <th>Quality of Response</th>
      <th>Accuracy of Response</th>
      <th>Depth of Response</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Instructional Pattern</td>
      <td>High</td>
      <td>High</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Zero-shot Prompting</td>
      <td>Moderate</td>
      <td>Moderate</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Few-shot Prompting</td>
      <td>High</td>
      <td>High</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Chain-of-Thought Prompting</td>
      <td>Very High</td>
      <td>High</td>
      <td>Very High</td>
    </tr>
    <tr>
      <td>Active-prompt</td>
      <td>Moderate</td>
      <td>High</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>Directional Stimulus Prompting</td>
      <td>High</td>
      <td>Moderate</td>
      <td>Moderate</td>
    </tr>
    <tr>
      <td>Graph Prompting</td>
      <td>High</td>
      <td>High</td>
      <td>Moderate</td>
    </tr>
    <tr>
      <td>Reverse-Engineered Prompting</td>
      <td>High</td>
      <td>High</td>
      <td>High</td>
    </tr>
    <tr>
      <td>Multilingual and Multimodal</td>
      <td>High</td>
      <td>Moderate</td>
      <td>High</td>
    </tr>
  </tbody>
</table>
<br>
<img width="924" height="1032" alt="image" src="https://github.com/user-attachments/assets/afac8b25-8b0f-44d2-826b-49bcb82959ca" />

## RESULT:
The prompt for the above said problem executed successfully.
