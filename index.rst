.. Notebooks 101 documentation master file, created by
   sphinx-quickstart on Mon May 18 09:22:17 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

========================================
Running Notebooks on HPC Systems 
========================================

This tutorial shows you how to run Jupyter Lab or Notebooks on Comet, TSCC, or TSCC-Stratus using different types of connections to these services, and running them on different nodes (login, interactive, and compute). 

.. note:: It is against SDSC policy to run applications, including notebooks, on the login node. Notebook should be run on compute nodes only.

Once the notebook is running, you can access a the notebook directly from a browser running on your local system (laptop, workstation, etc.). 

.. note:: Unless you are using `SSH Tunneling` or the `Reverse Proxy` methods, the connection is insecure and has the potential to be hacked by malicious parties.

On Comet, we only support the following connection scenarios:

* Connection to Notebook over SSH tunneling (secure)
* Connection to Notebook over HTTPS using the `Reverse Proxy Service <https://github.com/sdsc-hpc-training-org/reverse-proxy>`_  (very secure)

In addition, notebooks can be run on the following nodes:

* Login node
* Interactive node
* Compute node
* GPU node

The choices and combinations used to run notebooks affect the security and efficiency of you application. In the next sections, we'll describe how to connect and how to run the notebooks and the security impacts of these configurations.

Data Visualization With Python Using Jupyter Notebooks
------------------------------------------------------

With examples for Bokeh, Seaborn, and Networkx
----------------------------------------------

Introduction
------------

Lesson 1
--------
#Interactive Visualization of Weather Time Series Data With Bokeh

In this lesson, we will do some simple plotting just using matplotlib to get an idea of what plotting is typically like in Python. Then we will add some pan/zoom interactivity to the plots using Bokeh. 

#About the data

This data was collected from the High-Performance Wireless Research and Education Network (HPWREN, https://hpwren.ucsd.edu ). HPWREN has worked in coordination with the San Diego Gas & Electric and regional fire first response services to establish the finest real-time weather data collection and video minitoring system on the planet.

Lesson 2
--------
#Plot Tweet Timelines Using Bins and Interactive Bokeh Scatterplots

For this lesson we will generate timeline plots of individual tweets and all retweets for the most retweeted tweets using 5 minute (variable) bins and interactive Bokeh scatterplots with Botometer scores and follower counts.

In this lesson, we will do some simple plotting just using matplotlib to get an idea of what plotting is typically like in Python. Then we will add some pan/zoom interactivity to the plots using Bokeh. 

#About the data

This dataset was created earlier this year using the Twitter Streaming API searching for all tweets/retweets which use the hashtag 'muellerreport'. The original data was collected in its native JSON format. The JSON data comprised more than 5 GB. We reduced the size by extracting a subset of features, only a few of which we will need for this lesson. Here are some stats for the dataset.

Start: 2019-04-09 17:59:58

End: 2019-04-29 15:24:59

1,732,899 Total Tweets

1,420,964 Retweets

311,935 Original Tweets

Links
-----
.. _Wikipedia: https://www.wikipedia.org/
.. _Linux kernel archive: https://www.kernel.org/

.. toctree::
   :maxdepth: 2

   overview.md
   examples.md
   prerequisites.md
   methods/httpConnect.md
   methods/tunneling.md
   methods/reverseProxy.md
   aboutus.md
   contactus.md

