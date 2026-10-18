FROM quay.io/jupyter/scipy-notebook@sha256:8f8a5763d9a01e7f488eff8d9379654788e9cc08286dbcbc6bcda129c1b0edcd

RUN pip install --no-cache-dir torch==2.8.0 --index-url https://download.pytorch.org/whl/cpu

ENV HF_HUB_DISABLE_XET=1

RUN pip install --no-cache-dir \
    openai \
    sentence-transformers==5.1.2 \
    transformers==4.57.1 \
    faiss-cpu==1.12.0 \
    qdrant-client==1.15.1
