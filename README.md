# Jupyter service for XNAT
[XNAT](https://www.xnat.org) is a reliable data management system for imaging data. [Jupyter notebook](https://jupyter.org/) is a convenient interface to automatize, document and visualize imaging analysis steps. 
However, a smooth integration of  XNAT content into Jupyter is missing. Currently, you would have to fetch data from XNAT, store it locally, process the data with Jupyter, and transfer the results back to XNAT afterwards. 
Here, we aim to add Jupyter notebook as an interactive layer to directly manipulate and visualize XNAT data. As one possible solution, we  suggest to add Jupyter as a container into the [XNAT project](https://github.com/NrgXnat/xnat-docker-compose).

mattermost channel: https://mattermost.brainhack.org/brainhack/channels/jupyter4xnat
