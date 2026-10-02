

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


# Hi, I'm Thilak

I trained as a mechanical engineer and spent my first years working with vehicle components and assembly line data. The problems I kept running into weren't mechanical. They were about information: records that were hard to search, failure reports written in many different ways, and answers that existed in the data but took a long time to find.

That's what led me to data science. Most of my projects deal with taking messy, real-world text and making it searchable and easier to understand.

## Projects

### Auto Safety Pro

Public vehicle safety databases contain hundreds of thousands of recalls and complaints, but they only support keyword search. If you search for "engine stall", you miss complaints that describe the same problem as "loss of propulsion".

For my master's thesis, I built a search system that combines keyword search (BM25) with semantic search (sentence embeddings and FAISS). A language model (Flan-T5) then summarises the most relevant records. You can ask something like "What are common issues with the 2016 Tesla Model S?" and see a short summary along with the original records it was based on.

[View the project](https://github.com/Thilakraju/auto-safety-pro)

### Deepfake Detection

Together with two classmates, I built a model that detects manipulated videos. A ResNeXt network extracts features from each frame and an LSTM models how those frames change over time. Accuracy improved with longer sequences, from 84% at 10 frames to 97.76% at 100 frames on FaceForensics++. The model runs in a small web app where you can upload a video and get a prediction with a confidence score.

[View the project](https://github.com/Thilakraju/deepfake-detection)

## Tools

Python, PyTorch, Hugging Face Transformers, Sentence-Transformers, FAISS, SQL, Power BI, FastAPI

## Contact

[LinkedIn](https://linkedin.com/in/thilak-raju) | thilakraju97@gmail.com
