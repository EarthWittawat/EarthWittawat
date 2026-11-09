## Vitawat Kitipatthavorn

**Computer Engineering @ KMUTT · Bangkok, Thailand**

Fourth-year undergraduate. I build full-stack web applications with LLM and
machine learning features, and spend most of my time on retrieval and multi-agent
systems.

### Tech

**Languages** TypeScript · JavaScript · Python · SQL · C · C++  
**Web & Mobile** React · Next.js · React Native (Expo) · Node.js · FastAPI · Elysia · Tailwind CSS · PostgreSQL · Supabase  
**LLM & RAG** Google ADK · DSPy · vLLM · ColBERTv2 · ColPali · Qdrant · GROBID · Docling  
**ML & Data** PyTorch · scikit-learn · Hugging Face · XGBoost · pandas · NumPy  
**Cloud & Tools** Docker · GitHub Actions · Google Cloud Run · AWS · Git · Streamlit

### Experience

**Research Intern** · Affective Technology Lab, Shibaura Institute of Technology, Japan · 2026  
Studied how biophilic workspace design affects stress recovery. Built a
Qwen3-Image-Edit web app to generate controlled workspace variants, converted them
to VR scenes with Hunyuan3D-DiT and Unreal Engine for Meta Quest 3, and ranked
ECG/EDA/PPG/HRV features by importance with Random Forest and SHAP.

### Current project

**SecretSource** checks whether the papers a paper cites support its claims, and
quotes the evidence. It uses multi-vector retrieval on Qdrant (ColBERTv2 for text,
ColPali for figures), parses PDFs with GROBID and Docling, and orchestrates the
pipeline with Google ADK and DSPy. A FastAPI gateway streams progress over SSE to a
React + TypeScript UI. The services run in Docker on self-hosted machines behind an
API gateway with per-user keys, with CI on GitHub Actions.

### Contact

[Email](mailto:wttwkitipatthavorn@gmail.com) ·
[LinkedIn](https://linkedin.com/in/vitawat-kitipatthavorn-874b38334)
