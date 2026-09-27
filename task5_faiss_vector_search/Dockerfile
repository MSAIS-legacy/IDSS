FROM jupyter/datascience-notebook

RUN pip install --no-cache-dir torch==2.8.0+cpu --index-url https://download.pytorch.org/whl/cpu \
    && pip install --no-cache-dir gensim==4.4.0 sentence-transformers==5.1.2 transformers==4.57.1 beautifulsoup4==4.14.2

RUN pip install --no-cache-dir numpy==1.26.4 faiss-cpu==1.12.0 numba==0.59.1
