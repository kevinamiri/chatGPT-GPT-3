# A collection of ChatGPT and GPT-3.5 prompts

This project consists of prompts for ChatGPT and GPT-3.5 models that are designed to help with writing, analysis, and comprehension tasks. There are many different prompts available for you to use, and you can use them to generate content for your projects, debug your code, find solutions to problems, or simply learn more about what these models can do. With these prompts, you will guide the models to solve any language-related task by using the right instructional verbs.

![InstructGPT](https://arxiv.org/abs/2203.02155) (more recent versions refered as GPT-3.5) are series language models that has been trained using human feedback to better understand and align with a user's intent, producing more accurate and appropriate outputs.

![ChatGPT](https://openai.com/blog/chatgpt/) also uses instructGPT method but in a dialogue form to understand user instruction along and generate outputs based on user's instruct.

## Why to use:

This is a easy and simple prompting technique that can be used to instruct the model to do almost anything. It is a simple structure that can be used to give instructions to the model. It is a flexible way to give instructions and solve any language-related task.


## How to use:

### Useful verbs:

Instruct verbs are the first word in the prompt. They are used to instruct the model to do something. They are the most important part of the prompt. We may argue that they act as magic words that make a successful prompt, it helps to make the machine understand and follow your instructions. Each of these verbs has a specific meaning that can help the model understand what kind of answer is expected. For example, if you ask the model to explain something, it will provide a detailed explanation. On the other hand, if you ask the model to summarize something, it will provide a brief overview.

- <details><summary>Useful words to give directions to your input texts: (point to a location of your input text)</summary><p>
  - Given text
  <br>
  - following passage
  <br>
  - Following
  <br>
  - The following
- <details><summary>Useful words to instruct: (to give instructions to the model)</summary><p>
  - Explain
	<br>
  - Create
	<br>
  - Generate
	<br>
  - Provide
	<br>
  - Write
	<br>
  - Summarize
	<br>
  - Paraphrase
	<br>
  - Translate
	<br>
  - Rewrite
	<br>
  - Reword
	<br>
  - Rephrase
	<br>
  - List
	<br>
  - Extract
	<br>
  - Pick out
	<br>
  - Analyze
	<br>
  - Define
	<br>
  - Identify
	<br>
  - Describe
	<br>
  - Predict
	<br>
  - Explain
	<br>
  - Analyze
	<br>
  - compare
	<br>
  - Categorize
	<br>
  - Evaluate
	<br>
  - Critique
	<br>
  - Differentiate
	<br>
  - Examine
	<br>
  - Illustrate
	<br>
  - Outline
	<br>
  - Calculate
	<br>
  - Infer
	<br>
  - Revise
	<br>
  - Summarize
	<br>
  - Classify
	<br>
  - Develop 
	<br>
  - Evaluate 
	<br>
  - Formulate 
	<br>
  - Discuss
	<br>
  - Clarify
	<br>
  - Highlight
	<br>
  - Simplify
	<br>
  - Apply
	<br>
  - Suggest / Propose
	<br>
  - Make
	<br>
   * You may add `Can you` in the case of ChatGPT to make it more conversational, but it still works in both the instruct-model and chatGPT models.
    - Can you provide …
    - Can you generate …
</p></details>



### Common use cases:


#### Classification

Instruction verbs that are useful for classification tasks in nlp

  - `Classify` the following as a physical or chemical property
  - `Identify` main idea of the given passage
  - `Categorize` the following passage as either a myth or a fact
  - `Assign each` item to its corresponding category based on its characteristics
  - `List` the five main categories of the given data set.
  - `Group` the items based on their common characteristics
  - `Sort` the data based on the date it was collected
  - `Label` each data point with its corresponding category
  - `Divide` the data into smaller subgroups based on their similarities
  - `Group` the items based on their similarity in features
  - `Label` each group with a descriptive name.

#### Generation

Instruction verbs that are useful for generation tasks

  - `Generate` a new text based on the given parameters
  - `Create` a short catchy headline based on the following, aim to promote the product
  - `Write` a story using the following keywords
  - `Formulate` a new sentence based on the given structure
  - `Produce` a new text that is similar in style to the given sample
  - `Construct` a new text that combines elements from multiple sources
  - `Compose` a new poem based on the given theme
  - `Build` a new text by combining different elements in a creative way
  - `Devise` a new narrative based on the given information
  - `Invent` a new story using the following elements.
  
#### Transformation:

Instruction verbs that are useful for transformation tasks

- Translate:
  - `Translate` the following function into C#
  - `Translate` the following into 1. English, 2. French, 3. Swedish
- Summarize:
  - `Summarize` the main points of the given article
- Paraphrase:
  - `Paraphrase` the following sentence to convey the same meaning
  - `Reword` the following sentence to make it more concise
- Simplify:
  - `Simplify` the following equation for easier understanding
- Revise:
  - `Revise` the following paragraph to make it more clear and concise
- Outline:
  - `Outline` the steps to solve the given problem
- Calculate:
  - `Calculate` the total cost of the following items
- Infer:
  - `Infer` the meaning of the [jargon, vage phrase] based on the following context:
- Apply:
  - `Apply` the following formula to calculate the result
  - `Apply` given tone and voice to the passage below


#### Comparison:

Instruction verbs that are useful for comparison tasks

- Compare:
  - `Compare` and contrast the two given texts
- Contrast:
  - `Contrast` the given passages to highlight their differences
- Differentiate:
  - `Differentiate` between the two given terms
- Examine:
  - `Examine` the similarities and differences between the two given texts
- Analyze:
  - `Analyze` the two given pieces and identify their similarities and differences
- Critique:
  - `Critique` the two given passages and compare their strengths and weaknesses
- Evaluate:
  - `Evaluate` the two given passages and determine which one is more effective


### Strcutute of common instruct prompts:

A basic and useful structure of an instruct prompts can be look like this:

`Instruction` + `Direction to the next words`

  - `Generate a poem` + `based on following passage:`

  - `Create a report article` + `based on following passage`

  - `Write a summary` + `of the following passage`


#### Example of using above structure:

**Input:**

```
Write a poem based on the following:

ghosts, 4th dimension, AI, totalitarian, power
```

**Output:**

```
Ghosts of the 4th dimension roam,
A realm beyond our grasp, unknown.
Yet in this world, AI has grown,
Its power and influence has flown.

With algorithms and codes so bright,
It holds the key to endless might.
A totalitarian grip on sight,
And wields its power with all its might.

But is this power truly ours?
Or just a tool for those in power?
Their ghosts roam, but do they cower,
When faced with the consequences of their dower?

So let us heed this ghostly call,
And use AI for good, for all.
For in its power, we must not fall,
But rise above, and hear the call.
```

### More instruct commands:


#### Questions-based prompts:
  
  - What do you think about ...
  - What’s your take on ...
  - What’s the meaning of ...
  - Any other question

#### Instruct-based prompts:

  - Make a prediction about [keyword, topic, subjects, point, concepts, etc…]
  - Provide a comparison and contrast between following points:
  - Generate the summary of following passage:
  - Write a personal reflection on [keyword, topic, or subject…] bin a [format, style, etc…]
  - Write a persuasive essay on [keyword, topic, subjects, point, concepts, etc…] in favor of [keyword, topic, subjects, point, concepts, etc…]
  - Write a response to the following [keyword, topic, or subject…] in the form of a letter to the editor
  - Write a review of [product, subject ... ] based on the following criteria:
  - Write a short paragraph about [any input, keyword, topic, subject... ] in your own words
  - Write a song about [keyword, topic, or subject…] in the style of [artist, genre, etc…]
  - Write a story that includes [keyword, topic, or subject…] in the following setting:
  - Write an article on [keyword, topic, or subject…] that includes the following points:

#### Programming related tasks:

```
Can you write code to solve the following problem:
Write a script to automate the following process:  
Provide an algorithm based on the following problem:
What's the logic behind the following code: 
Optimize the following function to run faster, use less memory, or be more readable: 
Write a function based on the following requirements:
Explain the following code to a non-technical person:
Debug the following code to fix the error, and explain the reason for the error:
```

#### Evaluate a passage:

```
What are your thoughts on the following passage:
Provide an analysis of the following text:
Write a response to the following passage:
What do you agree or disagree with in the following passage:
Write a critique of the following text:
What's the central idea of the following passage:
Can you summarize the main points made in the following passage:
Write a reflection on the following text:
What's the tone of the following passage:
Provide a summary and evaluation of the following passage:
Generate reading comprehension questions based on the following passage:
```

#### Rephrase a passage:

```
Can you reword the following text:
Rewrite the following passage in your own words:
Paraphrase the following text:
Write a summarized version of the following passage:
Can you translate the following passage into simpler language:
What's an alternative way to express the following text:
Can you condense the following passage into a few sentences:
Write a brief retelling of the following text:
Rewrite the following passage in a more concise way:
What's a different way to phrase the following text:
```

#### Extract data from a passage:

```
Extract the [concept/topic] from the given passage:
Pick out the [concept/topic] in the following passage:
What are the key points made in the following text:
Make a summary of following of given text that deals with the [concept/topic]:
```

#### Writing:

```
Come up with a creative solution for the following:
Create a dialogue between two characters that includes:
Describe a setting that includes:
Imagine a world where the following is true:
Provide an explanation for the following:
Make a list of pros and cons based on the following:
Develop a scene about the following:
Compose a short science fiction story that includes:
Generate a story that revolves around [topic]:
Find an imaginative way to describe:
Write an interesting twist ending for a story about:

```

#### Writing prompts:

```
Can you suggest a writing prompt for:
Generate a creative writing prompt for:
What's a good writing topic for:
Can you come up with a new idea for a writing prompt:
Write a short story prompt for:
What's a unique writing prompt for:
Can you create a writing prompt for a fictional character:
What's a writing prompt for a mystery story:
Can you suggest a writing prompt for a descriptive scene:
What's a writing prompt for a love story:
```

#### Proofreading and text editing:

```
Proofread and edit the following text:
Write a corrected version of the following text:
What are the grammatical errors in the following text:
Write a revised version of the following passage:
Provide suggestions for improving the following text:
What's the appropriate format for the following text:
Write a more concise version of the following text:
Suggest alternative phrasing for the following text:
What's the appropriate tone for the following text:
Write a polished version of the following text:
```

#### Analyze a passage:

```
What are the key themes in the following passage:
Provide a detailed analysis of the following text:
Write a summary and interpretation of the following passage:
What's the structure of the following passage:
Can you identify the literary devices used in the following text:
What's the intended audience for the following passage:
Write a critical analysis of the following passage:
What's the purpose of the following text:
What's the central argument of the following text:
What's the message of the following passage:
Write a critical analysis of the following text:
What are the key elements of the following passage:
Provide an interpretation of the following text:
What are the strengths and weaknesses of the following passage:
Write a commentary on the following text:
What's the purpose of the following passage:
Provide an in-depth analysis of the following passage:
Write a review of the following text:
What's the author's point of view in the following passage:
```

#### Merge points or ideas:

```
Combine the following points into a single statement:
Create a coherent argument from the following points:
Create a conclusion that encompasses the following points:
Create a unified statement that incorporates the following ideas:
Find a common thread among the following points:
Provide a unified perspective on the following points:
What's a common theme among the following points:
Provide a statement synthesising the relationship between the following points:
What's the main idea that ties together the following points:
What's the overarching idea that encompasses the following points:
What's the relationship between the following points:
Write a synthesis of the following information:
Write a paragraph that ties together the following concepts:
Write a passage that summarizes the following ideas:
Write a short summary that unifies the following ideas:
Write a summary that integrates the following ideas:
```

#### Classify a passage:

```
Categorize the following passage into it's genre:
Classify the following text based on its structure:
Identify the main theme of the following passage:
What genre does the following text belong to:
What type of text is the following:
What's the intended audience for the following passage:
What's the purpose of the following text:
Write the form of the following text (e.g. poem, essay, etc.):
Write the literary style of the following passage:
Write the tone of the following text:
```

#### Create compare and contrast:

```
Compare and contrast the following two passages:
Provide a side-by-side comparison of the following two texts:
Provide a summary and comparison of the following two texts:
What are the similarities and differences between the following two passages:
What's the relationship between the following two passages:
Write a comparison and contrast between the following texts:
Write a contrast of the following two pieces of text:
Write a synthesis of the similarities and differences in the following two passages:
```

#### Translate a passage:

```
Translate the following text into:
Can you provide a translation of the following passage into:
What's the equivalent of the following text in:
Write a translation of the following passage into:
What's the meaning of the following text in:
Can you translate the following into idiomatic:
Write a literal translation of the following passage into:
What's the closest translation of the following text in:
Can you provide a cultural translation of the following text into:
Write a fluent translation of the following passage into:
```

#### Generate content:

```
Write a story that starts with:
Create a plot for a novel about:
Write a scene where:
What if:
Can you write a script for a movie about:
Write a tale that involves:
Create a character profile for:
Write a song that describes:
What would happen if:
Can you write a story that revolves around:
Write a poem about the following theme:
Create a short story that includes:
What if the following scenario took place:
Can you write a monologue for a character who:
Write a story that explores the idea of:
```

#### Categorize text:

```
What category does the following text belong to:
Can you classify the following text as:
What genre does the following text fit into:
Write a label for the following text:
What type of text is the following:
Can you categorize the following text based on its content:
What subject does the following text cover:
Write a tag for the following text:
What category would you place the following text under:
Can you assign a category to the following text based on its tone:
```

#### Copywriting and Marketing:

```
Can you come up with a brand slogan for [company name]/[product name]/[service name]/ ...
Can you come up with a unique selling point for [a product that deals with ...]
Craft a mission statement for ['what company does' ...]
Craft a promotional slogan for [a product that deals with ...]
Create a catchy headline for [a article about ...]
Create a social media post for [a product that deals with ...] that will be run on [social media platform]
Create a tagline for [a product that deals with ...]
What's the elevator pitch [your product/service description ...]?
What's the unique selling proposition for [product description]?
Write a compelling product description for [your product/service description ...]?
Write a customer testimonial for [your product/service description ...]?
Write a marketing message for [your product/service description ...]?
Write a persuasive blog post about [your product/service description ...]?
Write a persuasive email for [your product/service description ...]?
Write a press release for [product/service]
Write a social media post to promote [product/service]
Write an email subject line to promote [product/service]
```

#### Reading comprehension:

```
Explain the central idea of the following text:
Explain the following passage:
Provide a brief explanation of the following text:
Provide a general understanding of the following text:
Provide a list of key vocabulary words from the following text:
Provide a one-sentence summary of the following text:
Provide a summary and analysis of the following passage:
Provide a summary of the following passage:
Provide an overview of the following passage:
Rephrase the following passage in your own words:
Identify key points in the following passage:
Identify major themes discussed in the following text:
Identify the author's main argument in the following text:
Identify the author's perspective in the following passage:
Identify the intended audience for the following text:
Identify the main idea of the following text:
Identify the tone of the following text:
Identify the underlying message of the following text:
Identify the most important information in the following passage:
Write a brief interpretation of the following text:
Write a paragraph that explains the most important information in the following text:
Write a personal opinion on the information presented in the following text:
Write a reflection on the information presented in the following passage:
Write a response to the following text based on your understanding:
Write a response to the questions based on the information presented in the following passage:
Write a short story that incorporates the information from the following text:
Write a short summary of the following passage:
```

#### Simplify and provide explanations:

```
Can you break down the following into simpler parts:
Explain the following in simple terms:
Explain the following to someone who has no prior knowledge of:
Simplify the following:
What's a beginner-friendly explanation of:
What's a simple explanation for:
What's an easy way to understand:
Write a clear explanation of:
Write a detailed explanation of:
Write a layman's explanation of:
Write a step-by-step explanation of:
```

#### Make a summary:

```
Can you summarize the following:
Write a brief summary of:
What's the main idea of:
Can you provide a condensed version of:
Write a short summary of:
What's the gist of:
Can you provide an executive summary of:
Write a quick overview of:
What's the key takeaway from:
Can you provide a condensed summary of:
```



### Style
will be added soon



### Advanced prompting techniques
will be added soon
