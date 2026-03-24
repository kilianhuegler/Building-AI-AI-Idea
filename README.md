# Suomi Ystävä – Finnish AI Language Partner

Final project for the Building AI course

---

## Summary

Suomi Ystävä is an AI-powered language learning partner designed to help beginners and advanced learners practice Finnish through interactive conversations and pronunciation feedback with targeted training. It acts like a tutor for learning the Finnish language and is available around the clock.

---

## Background

Finnish is considered one of the most difficult European languages for speakers of Indo-European languages. With 15 cases, complex vowel harmony and a grammar that differs strongly from Indo-European languages. Actively using and speaking a language is the best way to learn it. As a personal motivation, an assistant would be perfect for discussing a topic or area and gradually learning vocabulary and grammar through active use. Also there are many international newcomers or international students who need or want to learn Finnish.

Learners face the following problems:

* There are hardly any opportunities to actively speak Finnish and Finns often switch to English.
* Outside of Finland, there is a very limited number of course offerings and these are usually time-limited and very expensive.
* There are not many Finnish native speakers to practice the language with outside of Finland.
* There are app offerings like Duolingo, but these only provide pre-made exercises with odd vocabulary and sentences. There are no free conversations or specific feedback on pronunciation and grammar.

---

## How is it used?

The Suomi Ystävä assistant should ideally be used as a mobile app or web app. This makes the AI assistant easily accessible at any time.

The usage of the app roughly looks as follows:

1. At the start, a language level assessment is conducted through questions and short tests, so the user can start directly at an appropriate level to start learning.
2. The user can then select conversation exercises to prepare for situations such as restaurants, shopping, apartment searching or simple small talk. Afterwards the user can choose between communicating with the AI assistant via text or voice input.
3. The AI assistant gives the user direct feedback on pronunciation and grammar. A user of the AI assistant can also communicate in English to receive understandable tips and ask questions in English when their Finnish skills aren't strong enough.
4. The voice input of the user is analysed by the system and the AI assistant provides the user with feedback and areas for improvement. This improves the user's understanding of the language and learning progress.
5. New vocabulary is saved in a list and reviewed using spaced repetition or other techniques. In the app there are vocabulary lists for individual topic areas to practise these more specifically, if wanted.

The target audience of the AI application includes immigrants, students at Finnish universities, people interested in Finnish without access to courses or native speakers and people preparing for the YKI language test.

For a better learning experience, the AI assistant also knows the user's native language, so the user can easily communicate with the AI when they have questions or problems with understanding a word or topic.

---

## Data sources and AI methods

The project relies on freely available and open data sources. These provide the foundation for training the language model, building the vocabulary database and enabling pronunciation training.

| Data source | Description |
|-------------| ----------- |
| [The Language Bank of Finland (Kielipankki)](https://www.kielipankki.fi/language-bank/) | Finnish language corpora |
| [Wiktionary](https://www.wiktionary.org/) | Freely available dictionary data |
| [Tatoeba](https://tatoeba.org/en) | Open database with example sentences and translations |
| [Mozilla Common Voice](https://commonvoice.mozilla.org/en) | Freely available voice recordings for pronunciation training |

### AI techniques

* **Natural Language Processing (NLP)** – Required for understanding and generating texts. A pre-trained language model would be advantageous and could be used as a basis.
* **Retrieval-Augmented Generation (RAG)** – A connected knowledge database with grammatical explanations and examples to provide context-based assistance, when asking the AI assistant questions.
* **Machine Learning (Classification)** – A classifier is used to determine the user's language level based on input texts. The model is trained on labelled example texts of different proficiency levels (A1–B2) and learns to recognise patterns such as sentence complexity, vocabulary range and grammatical accuracy.
* **Speech-to-Text & Text-to-Speech** – A speech module is used for voice input and output so the user can interact verbally. Possible models for speech recognition include Whisper and Deepgram.

### Non-AI methods

* **Spaced Repetition Algorithm** – To learn and review vocabulary efficiently an algorithm like SM-2 schedules reviews at increasing intervals. This is a rule-based technique, but essential for effective language learning.

---

## Challenges

Suomi Ystävä is a helpful tool, but it also has it limits. It won't turn you into a fluent Finnish speaker on its own and active learning, patience and discipline is needed. This are limitations to keep in mind:

* It is no replacement for human interaction with a native speaker. The AI can imitate individual real conversations, but it cannot incorporate humour and cultural subtleties like a real Finn. Additionally, the social aspect as well as gestures and facial expressions are missing.
* The assessment and analysis of pronunciation and grammar is limited. The system may make errors with stress or differences in vowel length, which is very common in Finnish.
* Language is also more than just learning grammar and vocabulary. It is also about Finnish culture and an AI can only convey this to a limited amount.
* Due to the analysis, speech must be recorded and these are sensitive personal data. It must be clearly communicated beforehand how this data is processed and stored.
* The data sources could contain biases that may affect the quality of the data.
* Also there are various Finnish dialects that differ from the standard language. If someone wants to learn dialects rather than the standard language, this could be a difficult problem.

---

## What next?

This project is a concept and just a project plan for the AI idea. To turn it into a working production product, the following roadmap outlines the next steps:

| Phase | Description |
| :---- | :---------- |
| **1 – Prototype** | Build a simple text-based chatbot that can hold basic Finnish conversations using an existing language model. |
| **2 – Core features** | Add features like the level assessment, grammar correction and vocabulary tracking with spaced repetition. Also integrate the RAG system to provide grammar explanations from a knowledge base. |
| **3 – Voice integration** | Add the features for Speech-to-Text and Text-to-Speech to enable spoken conversations. |
| **4 – Expanded features** | Add more advanced features like the ability to learn dialects and the ability to train the AI assistant with voice recordings. |
| **5 – Deployment** | Deploy the AI assistant to a mobile app or web app. |

---

## Acknowledgments

* [Kielibuusti – Myths about Finnish](https://www.kielibuusti.fi/en/learn-finnish/language-learning-tips/myths-about-finnish/myth-1-finnish-is-the-worlds-hardest-language)
* [YKI – National Certificates of Language Proficiency](https://www.oph.fi/en/national-certificates-language-proficiency-yki)
* [The Language Bank of Finland (Kielipankki)](https://www.kielipankki.fi/language-bank/)
* [Wiktionary](https://www.wiktionary.org/)
* [Tatoeba](https://tatoeba.org/en)
* [Mozilla Common Voice](https://commonvoice.mozilla.org/en)
