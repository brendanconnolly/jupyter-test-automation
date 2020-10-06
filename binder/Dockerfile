
FROM brendanconnolly/test-automation-jupyter-base

WORKDIR ${HOME}
USER $NB_UID
# Install additional npm packages for slides
ENV PATH $PATH:${HOME}/.npm-global/bin
RUN npm install  webdriverio
RUN npm install  axios
ADD Slides.ipynb .
ADD Slides.ipynb ./work/Slides.ipynb

#uncomment to use jupyter hub
#CMD ["jupyter", "lab", "--ip=0.0.0.0"]

