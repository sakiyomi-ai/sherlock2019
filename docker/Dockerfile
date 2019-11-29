FROM tensorflow/tensorflow:latest-py3-jupyter
LABEL maintainer="inabe@sakiyomi.ai"

RUN apt-get update
RUN apt-get install -y libsm6 libxext6 libxrender-dev
RUN pip install --upgrade pip
RUN pip install -q keras
RUN pip install scikit-learn
RUN pip install opencv-contrib-python
RUN pip install sentencepiece
RUN pip install pandas
RUN pip install bert-for-tf2
RUN pip install tqem
RUN pip install gensim
RUN pip install plotly
