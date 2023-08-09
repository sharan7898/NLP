# NLP

![NLP](/images/logo.jpg)

## What is NLP ?

* NLP stands for Natural Language Processing, which is a part of Computer Science, Human language, and Artificial Intelligence. 

* It is the technology that is used by machines to understand, analyse, manipulate, and interpret human's languages. 

* It helps developers to organize knowledge for performing tasks such as translation, automatic summarization, Named Entity Recognition (NER), speech recognition, relationship extraction, and topic segmentation.

![NLP](/images/NLP.png)

## History of NLP

**(1940-1960)** - Focused on Machine Translation (MT)

The Natural Languages Processing started in the year 1940s.

**1948** - In the Year 1948, the first recognisable NLP application was introduced in Birkbeck College, London.

**1950**s - In the Year 1950s, there was a conflicting view between linguistics and computer science. Now, Chomsky developed his first book syntactic structures and claimed that language is generative in nature.

In **1957**, Chomsky also introduced the idea of Generative Grammar, which is rule based descriptions of syntactic structures.

**(1960-1980)** - Flavored with Artificial Intelligence (AI)

In the year **1960 to 1980**, the key developments were:

**Augmented Transition Networks (ATN)**

Augmented Transition Networks is a finite state machine that is capable of recognizing regular languages.

**Case Grammar**

Case Grammar was developed by Linguist Charles J. Fillmore in the year 1968. Case Grammar uses languages such as English to express the relationship between nouns and verbs by using the preposition.

In Case Grammar, case roles can be defined to link certain kinds of verbs and objects.

For example: "Neha broke the mirror with the hammer". In this example case grammar identify Neha as an agent, mirror as a theme, and hammer as an instrument.

In the year 1960 to 1980, key systems were:

**SHRDLU**

SHRDLU is a program written by Terry Winograd in 1968-70. It helps users to communicate with the computer and moving objects. It can handle instructions such as "pick up the green boll" and also answer the questions like "What is inside the black box." The main importance of SHRDLU is that it shows those syntax, semantics, and reasoning about the world that can be combined to produce a system that understands a natural language.

**LUNAR**

LUNAR is the classic example of a Natural Language database interface system that is used ATNs and Woods' Procedural Semantics. It was capable of translating elaborate natural language expressions into database queries and handle 78% of requests without errors.

**1980 - Current**

Till the year 1980, natural language processing systems were based on complex sets of hand-written rules. After 1980, NLP introduced machine learning algorithms for language processing.

In the beginning of the year 1990s, NLP started growing faster and achieved good process accuracy, especially in English Grammar. In 1990 also, an electronic text introduced, which provided a good resource for training and examining natural language programs. Other factors may include the availability of computers with fast CPUs and more memory. The major factor behind the advancement of natural language processing was the Internet.

Now, modern NLP consists of various applications, like speech recognition, machine translation, and machine text reading. When we combine all these applications then it allows the artificial intelligence to gain knowledge of the world. Let's consider the example of AMAZON ALEXA, using this robot you can ask the question to Alexa, and it will reply to you.

## Advantages and DisAdvantages of NLP

**Advantages of NLP**

* NLP helps us to analyse data from both structured and unstructured sources.

* NLP is very fast and time efficient.

* NLP offers end-to-end exact answers to the question. So, It saves time that going to consume unnecessary and unwanted information.

* NLP offers users to ask questions about any subject and give a direct response within milliseconds.

**Disadvantages of NLP**

* For the training of the NLP model, A lot of data and computation are required.

* Many issues arise for NLP when dealing with informal expressions, idioms, and cultural jargon.

*  results are sometimes not to be accurate, and accuracy is directly proportional to the accuracy of data.

* NLP is designed for a single, narrow job since it cannot adapt to new domains and has a limited function.

## Components of NLP

1.**Natural Language Understanding (NLU):**

NLU is the component of NLP that focuses on enabling machines to understand and interpret human language. It involves various tasks and techniques aimed at extracting meaning, intent, and context from text or speech. Some key components and tasks of NLU include:

**Tokenization**: Breaking text into tokens (words, subwords, sentences).

**Part-of-Speech Tagging** (POS): Assigning grammatical parts of speech to words.

**Named Entity Recognition** (NER): Identifying and classifying named entities.

**Semantic Role Labeling** (SRL): Identifying the roles of words in a sentence (subject, object, etc.).

**Coreference Resolution**: Connecting pronouns and entities to their referents.

**Intent Recognition**: Determining the user's intention or purpose in a given text or speech input.

**Slot Filling**: Extracting specific pieces of information (slots) from user queries, often used in dialogue systems and virtual assistants.

**Text Classification**: Categorizing text into predefined classes or categories (e.g., sentiment analysis, topic classification).

**Question Answering**: Developing systems that can provide accurate answers to user questions.

2.**Natural Language Generation (NLG):**

NLG is the component of NLP that focuses on generating human-like language from structured data or other forms of input. NLG systems take structured information and convert it into coherent and contextually appropriate text. Some key components and tasks of NLG include:

**Text Planning**: Deciding on the overall structure and content of the generated text.

**Content Selection**: Choosing relevant information and details to include in the generated text.

**Sentence Generation**: Constructing grammatically correct and coherent sentences.

**Text Summarization**: Condensing longer pieces of text into concise summaries.

**Dialogue Generation**: Creating natural and contextually appropriate responses in dialogue systems and chatbots.

**Language Style and Tone**: Adapting the generated text to a specific writing style, tone, or level of formality.

**Text Paraphrasing**: Expressing the same content in different words while maintaining the original meaning.
Storytelling: Generating narratives, stories, or creative text.

## Difference between NLU and NLG

| NLU                          | NLG                        |
|------------------------------|----------------------------|
|NLU is the process of reading and interpreting language.|NLG is the process of writing or generating language.|
|Involves extracting meaning, intent, and context from text or speech.|Converts data into coherent, contextually appropriate text.|
|Tasks include intent recognition, sentiment analysis, entity recognition, and more.|Tasks include text planning, sentence generation, summarization, and more.|
|Identifies grammatical components like parts of speech (POS) and semantic roles.|Creates grammatically correct and coherent sentences.|
|Enables the system to "understand" what users are saying or writing.|Enables the system to "generate" meaningful and contextually relevant responses.|

## Applications of NLP

The applications of Natural Language Processing are as follows:

* Text and speech processing like-Voice assistants – Alexa, Siri, etc.

* Text classification like Grammarly, Microsoft Word, and Google Docs

* Information extraction like-Search engines like DuckDuckGo, Google

* Chatbot and Question Answering like:- website bots

* Language Translation like:- Google Translate

* Text summarization 

## How to build an NLP pipeline

There are the following steps to build an NLP pipeline -

1.**Step1:****Sentence Segmentation**

Sentence Segment is the first step for building the NLP pipeline. It breaks the paragraph into separate sentences.The primary goal of sentence segmentation is to divide a paragraph or text document into discrete units of meaning, which are sentences. These sentences can then be analyzed, processed, and used as individual units for various NLP tasks such as sentiment analysis, machine translation, summarization, and more.

**Example:**

**Consider the text**: "I enjoy reading books. They transport me to different worlds!"

After sentence segmentation, the output would be:

* "I enjoy reading books."

* "They transport me to different worlds!"

**How Segmentation works**

**Punctuation Detection:** The most common method for sentence segmentation involves identifying punctuation marks that typically indicate the end of a sentence, such as periods, exclamation points, and question marks.

**Abbreviation Handling:** Some punctuation marks, like periods, can also appear within abbreviations or acronyms. Advanced sentence segmentation algorithms take this into account and make exceptions for such cases.

**Contextual Information:** Some punctuation marks, like periods, can have multiple meanings in different contexts (e.g., "Mr." in "Mr. Smith" vs. "The U.S."). Contextual analysis and language modeling can help disambiguate these cases.

**Non-standard Language:** Sentence segmentation becomes challenging in cases where the text contains non-standard language, incomplete sentences, or unconventional punctuation usage. Handling these cases may require more advanced techniques.

**Machine Learning:** Machine learning approaches can be used to train models that predict sentence boundaries based on patterns in the data. These models can be trained on labeled datasets where sentences are annotated.

###  Word Tokenization

Tokenization is a foundational task in Natural Language Processing (NLP) that involves breaking down a continuous stream of text, often a sentence or paragraph, into individual units called tokens. In the context of word tokenization, tokens are typically words, although they can also be subword units in certain languages or applications.

**Example:**

**Consider the sentence:** "The quick brown fox jumps over the lazy dog."

After word tokenization, the tokens would be:

"The"
"quick"
"brown"
"fox"
"jumps"
"over"
"the"
"lazy"
"dog"

Word tokenization is a fundamental step in NLP pipelines, as it forms the basis for subsequent analysis and processing of textual data.

**Here's how word tokenization works:**

**Whitespace Splitting:** The simplest form of word tokenization involves splitting the text based on whitespace (spaces, tabs, newlines). Each chunk of characters separated by whitespace is considered a token. This method works for many languages, where words are separated by spaces.

**Punctuation Handling:** Punctuation marks, such as commas, periods, and semicolons, are often considered as separate tokens. However, some punctuation marks may be attached to words, like apostrophes in contractions ("can't"). Careful handling of punctuation is necessary.

**Hyphenated Words:** Hyphenated words like "mother-in-law" can be split into multiple tokens or kept as a single token, depending on the specific application and linguistic rules.

**Non-standard Language:** Word tokenization becomes more challenging when dealing with informal language, slang, abbreviations, and non-standard writing styles. These cases may require customized rules or language-specific models.

**Subword Tokenization:** In some cases, words can be split into subword units, like morphemes or characters. Subword tokenization is often used in languages with complex morphology or in applications like machine translation.



