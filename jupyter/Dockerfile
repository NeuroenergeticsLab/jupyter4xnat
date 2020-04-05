FROM jupyter/base-notebook

RUN conda install -y -q matplotlib pandas numpy \
    && pip install -q seaborn pyxnat nilearn sklearn \
    && conda clean --all -f -y