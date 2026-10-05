### Hi, I'm Jaswant

I work on machine learning and NLP. I like building models, testing where
they break, and deploying them so people can actually use them. Every project
below has a live demo and the code behind it.

**Projects**

**ShiftAI** ([code](https://github.com/Jaswant06/shiftai-router) | [live demo](https://huggingface.co/spaces/JaswantDev/shiftai-router))
Sends each prompt to the smallest local LLM that can answer it well, instead
of always using the biggest one. It predicts how each model (Qwen 3.5, 0.8B to
9B) would do on the prompt, then picks the cheapest one that meets your quality
target. On 760 held-out prompts it kept 89.9% of the 9B's quality while
answering 44% faster with 40% less energy, and the README shows where a simple
random split does just as well. Comes as a CLI, an OpenAI-compatible API and a
Docker image.

**DocuMind** ([code](https://github.com/Jaswant06/rag-pdf-assistant) | [live demo](https://huggingface.co/spaces/JaswantDev/rag-pdf-assistant))
Chat with a PDF. Retrieval augmented generation: embeddings find the relevant
passages and a 70B model answers from them with page citations. If the answer
is not in the document, it says so instead of making one up.

**AI Resume Matcher** ([code](https://github.com/Jaswant06/ai-resume-matcher) | [live demo](https://huggingface.co/spaces/JaswantDev/ai-resume-matcher))
Scores a resume against a job description with sentence embeddings and lists
the missing skills. Matches meaning, not keywords.

**Emotion Classifier** ([code](https://github.com/Jaswant06/semeval-emotion-classification-pytorch) | [live demo](https://huggingface.co/spaces/JaswantDev/tweet-emotion-classifier))
Multi-label tweet emotion model. Compared TF-IDF, a BiLSTM, DistilBERT, and
BERTweet (best: 0.73 micro-F1 across 11 emotions), then tested where the best
one fails and wrote it up.

**Tools:** Python, PyTorch, Hugging Face Transformers, Sentence-Transformers, scikit-learn, Ollama, FastAPI, Docker, GitHub Actions, Gradio

Open to AI/ML engineering roles. Portfolio: [jaswant06.github.io](https://jaswant06.github.io) · Hugging Face: [JaswantDev](https://huggingface.co/JaswantDev)
