

<!--
**Thilakraju/Thilakraju** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


# Hi, I'm Thilak 👋

I started out as a mechanical engineer, working with vehicle components and assembly lines. Somewhere along the way I noticed that the hardest problems weren't mechanical. They were about information: thousands of records nobody could search properly, failure reports written ten different ways, answers that existed in the data but took days to find.

That's what pulled me into data science, and it's what most of the work here is about: **making messy, real-world information searchable, understandable and useful.**

---

## 🔍 What I'm working on

### Auto Safety Pro: finding vehicle defects in plain language
Public vehicle safety databases hold hundreds of thousands of recalls and complaints, but they only support keyword search. Search "engine stall" and you miss every complaint that says "loss of propulsion" instead.

For my master's thesis, I built a system that understands both: it combines classic keyword search (BM25) with semantic search (sentence embeddings + FAISS), then uses a language model (Flan-T5) to summarise what the top records actually say. You can ask *"What are common issues with the 2016 Tesla Model S?"* and get a grounded answer, with the original records shown underneath so nothing is taken on trust.

→ [View the project](https://github.com/Thilakraju/auto-safety-pro)

### Deepfake Detection: teaching a model to watch, not just look
Most fake videos can fool a single-frame check. So with two classmates, I built a detector that looks at both: a ResNeXt network examines each frame, and an LSTM watches how those frames change over time. The longer it watches, the better it gets, from 84% accuracy at 10 frames to 97.76% at 100. It runs in a small web app where you upload a video and get a verdict with a confidence score.

→ [View the project](https://github.com/Thilakraju/deepfake-detection)

---

## 🧭 What connects these projects

- **Real data, not toy datasets.** Government safety records, public deepfake benchmarks, messy free text.
- **Explainability matters.** Both projects show *why* a result appeared, not just the result.
- **Built to be used.** Each one ends in an interface someone could actually open and try.

## 🛠️ Tools I reach for

Python · PyTorch · Hugging Face Transformers · Sentence-Transformers · FAISS · SQL · Power BI · FastAPI

---

📫 Always happy to talk about retrieval, RAG or turning data into something people can use: [LinkedIn](https://linkedin.com/in/thilak-raju) · thilakraju97@gmail.com
