# Jupyter service for XNAT

Join the jupyter4xnat-channel on <a href="https://mattermost.brainhack.org/brainhack/channels/jupyter4xnat"><img src="http://www.mattermost.org/wp-content/uploads/2016/03/logoHorizontal.png" width=100px /></a>

[XNAT](https://www.xnat.org) is a reliable data management system for imaging data. [Jupyter notebook](https://jupyter.org/) is a convenient interface to automatize, document and visualize imaging analysis steps. 
However, a smooth integration of  XNAT content into Jupyter is missing. Currently, you would have to fetch data from XNAT, store it locally, process the data with Jupyter, and transfer the results back to XNAT afterwards. 
Here, we aim to add Jupyter notebook as an interactive layer to directly manipulate and visualize XNAT data. As one possible solution, we  suggest to add Jupyter as a container into the [XNAT project](https://github.com/NrgXnat/xnat-docker-compose).

![](https://github.com/valneurolab/jupyter4xnat/raw/master/images/readme/jupyter4xnat_card.jpg)