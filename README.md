# Linguist: Text Analysis

Linguist analyses text by calculating a variety of linguistic and structural indicators, such as lexical richness, readability, sentiment, syntactic complexity, and thematic content, to provide comprehensive insights into the text's vocabulary, style, and meaning. It is designed to help users understand the complexity, tone, and key features of a given text.

---

## Progress

Currently, work is being done on the following sections:

1. **Lexical and Vocabulary Analysis**
2. **Readability and Complexity**
3. **Sentiment and Emotion Analysis**

After these are completed, work will begin on:

1. **Thematic and Content Analysis**
2. **Structural and Syntactic Analysis**.

---

## I. Summary

| **Indicator Group**            | **Description**                                                                 | **Indicators**                                                                 |
|--------------------------------|---------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **Lexical and Vocabulary**     | Measures the richness and diversity of vocabulary in the text.                  | Lexical Diversity, Type-Token Ratio (TTR), Vocabulary Size, Word Frequency     |
| **Readability and Complexity** | Evaluates how easy or difficult the text is to read.                            | Flesch-Kincaid, Gunning Fog, Average Sentence Length, Word Length              |
| **Sentiment and Emotion**      | Analyzes the emotional tone and sentiment of the text.                          | Positive/Negative/Neutral Sentiment, Tone Analysis                             |
| **Structural and Syntactic**   | Focuses on grammatical structure and sentence complexity.                       | Part-of-Speech (POS) Analysis, Passive vs. Active Voice, Punctuation Usage     |
| **Thematic and Content**       | Identifies key topics, themes, and entities in the text.                        | Keyword Extraction, Named Entity Recognition (NER)                             |
| **Cohesion and Coherence**     | Measures how well the text flows and connects ideas.                            | Lexical Chains, Coreference Resolution                                         |
| **Textual Novelty**            | Evaluates how unique or repetitive the text is.                                 | N-gram Overlap, Repetition Score                                               |
| **Engagement**                 | Assesses how engaging or interactive the text is.                               | Question Density, Direct Address                                               |

---

## II. Lexical and Vocabulary Analysis

These indicators focus on the richness, diversity, and complexity of the vocabulary used in the text.

- **Lexical Diversity**: Measures the ratio of unique words to total words.
- **Type-Token Ratio (TTR)**: Similar to lexical diversity but calculated for smaller text segments.
- **Vocabulary Size**: The total number of unique words in the text.
- **Word Frequency**: Counts how often specific words appear in the text.

---

## III. Readability and Complexity

These indicators measure how easy or difficult the text is to read and understand.

- **Flesch-Kincaid Readability Score**: Estimates readability based on sentence length and syllable count.
- **Gunning Fog Index**: Measures text complexity using sentence length and complex word frequency.
- **Average Sentence Length**: The average number of words per sentence.
- **Word Length**: The average number of characters per word.

---

## IV. Sentiment and Emotion Analysis

These indicators analyze the emotional tone and sentiment of the text.

- **Positive/Negative/Neutral Sentiment**: Determines the overall sentiment of the text.
- **Tone Analysis**: Identifies the tone (e.g., formal, informal, optimistic, pessimistic).

---

## V. Structural and Syntactic Analysis

These indicators focus on the grammatical and structural aspects of the text.

- **Part-of-Speech (POS) Analysis**: Identifies the distribution of nouns, verbs, adjectives, etc.
- **Passive vs. Active Voice**: Measures the proportion of sentences in passive voice.
- **Punctuation Usage**: Analyzes the frequency of punctuation marks.

---

## VI. Thematic and Content Analysis

These indicators identify the main topics, themes, and content of the text.

- **Keyword Extraction**: Identifies the most important words or phrases in the text.
- **Named Entity Recognition (NER)**: Detects and classifies entities like names, locations, and organizations.

---

## VII. Cohesion and Coherence

These indicators measure how well the text flows and connects ideas.

- **Lexical Chains**: Tracks sequences of related words throughout the text.
- **Coreference Resolution**: Identifies when different words refer to the same entity (e.g., pronouns).

---

## VIII. Textual Novelty

These indicators measure how unique or repetitive the text is.

- **N-gram Overlap**: Compares overlapping sequences of words within the text.
- **Repetition Score**: Measures the percentage of repeated phrases or sentences.

---

## IX. Engagement

These indicators measure how engaging or interactive the text is.

- **Question Density**: Counts the number of questions per paragraph.
- **Direct Address**: Tracks the use of second-person pronouns (e.g., "you").

---

## License

This project is licensed under the MIT No Attribution License. See the [LICENSE](LICENSE) file for details.
