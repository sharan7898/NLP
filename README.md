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

**Sentence Segmentation**

* Sentence Segment is the first step for building the NLP pipeline. It breaks the paragraph into separate sentences.

* The primary goal of sentence segmentation is to divide a paragraph or text document into discrete units of meaning, which are sentences. 

* These sentences can then be analyzed, processed, and used as individual units for various NLP tasks such as sentiment analysis, machine translation, summarization, and more.

**Example:**

**Consider the text**: "I enjoy reading books. They transport me to different worlds!"

After sentence segmentation, the output would be:

* "I enjoy reading books."

* "They transport me to different worlds!"

**How Segmentation works**

1.**Punctuation Detection:** The most common method for sentence segmentation involves identifying punctuation marks that typically indicate the end of a sentence, such as periods, exclamation points, and question marks.

2.**Abbreviation Handling:** Some punctuation marks, like periods, can also appear within abbreviations or acronyms. Advanced sentence segmentation algorithms take this into account and make exceptions for such cases.

3.**Contextual Information:** Some punctuation marks, like periods, can have multiple meanings in different contexts (e.g., "Mr." in "Mr. Smith" vs. "The U.S."). Contextual analysis and language modeling can help disambiguate these cases.

4.**Non-standard Language:** Sentence segmentation becomes challenging in cases where the text contains non-standard language, incomplete sentences, or unconventional punctuation usage. Handling these cases may require more advanced techniques.

5.**Machine Learning:** Machine learning approaches can be used to train models that predict sentence boundaries based on patterns in the data. These models can be trained on labeled datasets where sentences are annotated.

###  Word Tokenization

* Tokenization is a foundational task in Natural Language Processing (NLP) that involves breaking down a continuous stream of text, often a sentence or paragraph, into individual units called tokens. 

* In the context of word tokenization, tokens are typically words, although they can also be subword units in certain languages or applications.

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

1.**Whitespace Splitting:** The simplest form of word tokenization involves splitting the text based on whitespace (spaces, tabs, newlines). Each chunk of characters separated by whitespace is considered a token. This method works for many languages, where words are separated by spaces.

2.**Punctuation Handling:** Punctuation marks, such as commas, periods, and semicolons, are often considered as separate tokens. However, some punctuation marks may be attached to words, like apostrophes in contractions ("can't"). Careful handling of punctuation is necessary.

3.**Hyphenated Words:** Hyphenated words like "mother-in-law" can be split into multiple tokens or kept as a single token, depending on the specific application and linguistic rules.

4.**Non-standard Language:** Word tokenization becomes more challenging when dealing with informal language, slang, abbreviations, and non-standard writing styles. These cases may require customized rules or language-specific models.

5.**Subword Tokenization:** In some cases, words can be split into subword units, like morphemes or characters. Subword tokenization is often used in languages with complex morphology or in applications like machine translation.

### Stemming

* Stemming is used to normalize words into its base form or root form.

* Stemming involves removing suffixes or prefixes from words, which are often morphological variations that convey tense, number, gender, or other grammatical aspects. 

* By reducing words to their stems, stemming can help consolidate related words and increase the likelihood of matching similar words in information retrieval and search applications.


**Example:**

**Consider the words:** "running," "runs," "ran"

A stemming algorithm might reduce these words to the common stem "run," which helps treat these variations as the same word during analysis.

It's important to note that stemming is a heuristic approach, and while it can be useful for certain tasks, it may not always produce perfect results.

**Here's how stemming works:**

1.**Suffix Stripping:** Stemming algorithms typically focus on removing suffixes from words. Suffixes are the parts of a word that appear at the end and often indicate tense or grammatical variations. For example, the word "jumps" would be stemmed to "jump" by removing the "s" suffix.

2.**Prefix Stripping (Optional):** Some stemming algorithms also consider removing prefixes, which appear at the beginning of words. Prefixes are less common in English, but they might be relevant in other languages.

3.**Language-Specific Rules:** Different languages have different grammatical rules, so stemming algorithms need to be tailored to each language. For example, a stemming algorithm for English might not work well for languages with complex inflections like Spanish or Arabic.

4.**Over-Stemming and Under-Stemming:** Stemming algorithms can sometimes produce over-stemming (reducing words too aggressively, leading to loss of meaning) or under-stemming (not reducing words enough, leading to incorrect consolidation).

### Lemmatization

* Lemmatization is quite similar to the Stamming. 

* It is used to group different inflected forms of the word, called Lemma. 

* The main difference between Stemming and lemmatization is that it produces the root word, which has a meaning.

**Example:**

**Consider the words:** "running," "runs," "ran"

A lemmatization algorithm might reduce these words to the common lemma "run," which accurately captures their shared meaning.

**Here's how lemmatization works:**

1.**Dictionary Lookup:** Lemmatization relies on a linguistic database (dictionary or lexicon) that maps words to their corresponding lemmas. These lemmas represent the base or canonical form of each word.

2.**Part-of-Speech Tagging:** Lemmatization takes into account the part of speech (POS) of a word. Different lemmas might be generated based on whether the word is a noun, verb, adjective, or adverb.

3.**Morphological Analysis:** Lemmatization considers the word's morphology (structure and form) to determine the appropriate lemma. This involves identifying and removing prefixes and suffixes while keeping the core root of the word intact.

4.**Language-Specific Rules:** Just like stemming, lemmatization algorithms need to be tailored to each language's grammatical rules. Different languages have different inflectional patterns.

### Identifying Stop Words

* Identifying stop words is a crucial preprocessing step in Natural Language Processing (NLP) that involves identifying and removing common words that typically don't carry significant meaning in a given language. 

* These words, known as stop words, include frequently occurring words like articles, prepositions, pronouns, and conjunctions.

* The primary goal of identifying and removing stop words is to reduce the dimensionality of the data and focus on the more informative words that contribute to the overall meaning of the text. 

**Example:**

**Consider the sentence:** "The quick brown fox jumps over the lazy dog."

After removing stop words (assuming "the" and "over" are stop words), the sentence becomes: "quick brown fox jumps lazy dog."

**Here's how identifying stop words works:**

1.**Stop Word Lists:** Stop words are language-specific and are typically compiled into lists. These lists include words that are considered common and less meaningful in a particular language. Examples of stop words in English include "the," "is," "and," "of," "in," and "to."

2.**Filtering:** During preprocessing, text data is tokenized into words. Each word is compared to the stop word list. If the word matches any word in the list, it is considered a stop word and is often removed from the text.

3.**Contextual Considerations:** In some cases, stop word removal might involve considering the context. For example, the word "not" might be a stop word, but its presence or absence can drastically alter the meaning of a sentence. Therefore, careful consideration is needed in such cases.

###  Dependency Parsing

* Dependency parsing is a fundamental task in Natural Language Processing (NLP) that involves analyzing the grammatical structure of a sentence to determine the syntactic relationships between words. 

* The output of a dependency parsing process is a syntactic tree or graph that represents how words in a sentence are connected and depend on each other.

* In dependency parsing, each word in the sentence is treated as a node in the syntactic tree, and the relationships between words are represented as labeled directed edges (dependencies) between these nodes. 

* These dependencies typically indicate grammatical roles and relationships, such as subject, object, modifier, and more.

**Example:**

**Consider the sentence:** "The cat chased the mouse."

**A dependency parse might represent the relationships as:**

* "chased" is the root of the sentence.

* "chased" is connected to "cat" with the label "nsubj" (nominal subject).

* "chased" is connected to "mouse" with the label "dobj" (direct object).

### POS Tags and NER

* POS stands for parts of speech, which includes Noun, verb, adverb, and Adjective. 

* It indicates that how a word functions with its meaning as well as grammatically within the sentences. A word has one or more parts of speech based on the context in which it is used.

**Example:** 

**Consider the sentence:**"Google" something on the Internet.

In the above example, Google is used as a verb, although it is a proper noun.

**Named Entity Recognition (NER)**

Named Entity Recognition (NER) is the process of detecting the named entity such as person name, movie name, organization name, or location.

**Example:**

**Consider the sentence:** "Apple Inc. is planning to open a new store in Paris next month."

In NER, the identified named entities would be:

* Organization: "Apple Inc."

* Location: "Paris"

* Date: "next month"

## Phases of NLP

![phases](/images/Phases-of-Natural-Language-Processing.png)

**Lexical Analysis:**

* Lexical analysis, also known as tokenization, is the process of breaking down a continuous stream of text into individual units called tokens. 

* Tokens are the basic building blocks of language and can be words, subwords, or symbols. Lexical analysis is the first step in NLP pipelines and is essential for various language processing tasks.

**Syntactic Analysis** (Parsing)

* Syntactic Analysis is used to check grammar, word arrangements, and shows the relationship among the words.

* The goal of syntactic analysis is to understand how words are organized in a sentence and how they contribute to the overall meaning.

**Example:** Agra goes to the Poonam

In the real world, Agra goes to the Poonam, does not make any sense, so this sentence is rejected by the Syntactic analyzer.

**Semantic Analysis**

* Semantic analysis is concerned with the meaning representation. It mainly focuses on the literal meaning of words, phrases, and sentences.

*  It involves extracting and representing the intended meaning of words, phrases, and sentences, allowing computers to comprehend the context, relationships, and nuances conveyed by human language.

**Discourse Integration**

* Discourse Integration depends upon the sentences that proceeds it and also invokes the meaning of the sentences that follow it.

* Focuses on understanding the coherence and flow of language beyond the level of individual sentences. 
 
* It involves analyzing the relationships between sentences and larger text units to uncover the connections, transitions, and logical structures that create a unified discourse.

**Pragmatic Analysis**

* Pragmatic is the fifth and last phase of NLP. It helps you to discover the intended effect by applying a set of rules that characterize cooperative dialogues.

* Pragmatics is concerned with the social, cultural, and contextual aspects of language that influence communication and interpretation.

**For Example:** "Open the door" is interpreted as a request instead of an order.

## Why NLP is difficult?

NLP is difficult because Ambiguity and Uncertainty exist in the language.

* **Ambiguity**

There are the following three ambiguity -

1.**Lexical Ambiguity**

Lexical Ambiguity exists in the presence of two or more possible meanings of the sentence within a single word.

**Example:**

Manya is looking for a match.

In the above example, the word match refers to that either Manya is looking for a partner or Manya is looking for a match. (Cricket or other match)

2.**Syntactic Ambiguity**

Syntactic Ambiguity exists in the presence of two or more possible meanings within the sentence.

**Example:**

I saw the girl with the binocular.

In the above example, did I have the binoculars? Or did the girl have the binoculars?

3.**Referential Ambiguity**

Referential Ambiguity exists when you are referring to something using the pronoun.

**Example:** Kiran went to Sunita. She said, "I am hungry."

In the above sentence, you do not know that who is hungry, either Kiran or Sunita.

* **Variability and Creativity:** People express ideas in diverse ways, using idioms, metaphors, sarcasm, and other creative language forms that can be challenging for NLP models to understand.

**Example:**"It's raining cats and dogs."

Understanding the figurative meaning of the expression "raining cats and dogs."

* **Named Entity Recognition (NER):** Identifying and classifying named entities, such as names, dates, and locations, can be difficult due to variations in formatting, abbreviations, and domain-specific terms.

**Example:** "Apple is releasing a new iPhone."

In the above example, Recognizing "Apple" as a company name, not a fruit.