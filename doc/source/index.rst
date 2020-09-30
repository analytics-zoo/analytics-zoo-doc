.. _index:

.. image:: Image/logo_s.jpg


**A unified Data Analytics and AI platform for distributed TensorFlow, Keras and PyTorch on Apache Spark/Flink & Ray**               

What is Analytics Zoo?
---------------------

Analytics Zoo seamless scales TensorFlow, Keras and PyTorch to distributed big data (using Spark, Flink & Ray).

.. image:: Image/blockdiagram.jpg

-   **End-to-end pipeline for applying AI models (TensorFlow, PyTorch, OpenVINO, etc.) to distributed big data**

    * Write `TensorFlow <https://analytics-zoo.github.io/master/#ProgrammingGuide/TFPark/tensorflow/>`_ or `PyTorch <https://analytics-zoo.github.io/master/#ProgrammingGuide/pytorch/>`_ inline with Spark code for distributed training and inference.
    * Native deep learning (TensorFlow/Keras/PyTorch/BigDL) support in `Spark ML <https://analytics-zoo.github.io/master/#ProgrammingGuide/nnframes/>`_ Pipelines.
    * Directly run `Ray <https://analytics-zoo.github.io/master/#ProgrammingGuide/rayonspark/>`_ programs on big data cluster through _RayOnSpark_. 
    * Plain Java/Python APIs for (TensorFlow/PyTorch/BigDL/OpenVINO) `Model Inference <https://analytics-zoo.github.io/master/#ProgrammingGuide/inference/>`_. 
-   **High-level ML workflow for automating machine learning tasks**

    * `Cluster Serving <https://analytics-zoo.github.io/master/#ClusterServingGuide/ProgrammingGuide/>`_ for automatically distributed (TensorFlow/PyTorch/Caffe/OpenVINO) model inference . 
    * Scalable `AutoML <https://analytics-zoo.github.io/master/#ProgrammingGuide/AutoML/overview/>`_ for time series prediction.
-   **Built-in models for** `Recommendation <https://analytics-zoo.github.io/master/#APIGuide/Models/recommendation/>`_, `Time Series <https://analytics-zoo.github.io/master/#APIGuide/Models/anomaly-detection/>`_, `Computer Vision <https://analytics-zoo.github.io/master/#APIGuide/Models/object-detection/>`_ and `NLP <https://analytics-zoo.github.io/master/#APIGuide/Models/text-matching/>`_ applications

Why use Analytics Zoo?
---------------------

You may want to develop your AI solutions using Analytics Zoo if:

* You want to easily apply AI models (e.g., TensorFlow, Keras, PyTorch, BigDL, OpenVINO, etc.) to distributed big data.
* You want to transparently scale your AI applications from a single laptop to large clusters with "zero" code changes.
* You want to deploy your AI pipelines to existing YARN or K8S clusters *WITHOUT* any modifications to the clusters.
* You want to automate the process of applying machine learning (such as feature engineering, hyperparameter tuning, model selection, distributed inference, etc.). 


How to use Analytics Zoo?
---------------------

* Check out the `Getting Started page <https://analytics-zoo.github.io/master/#gettingstarted/>`_ for a quick overview of how to use Analytics Zoo.
* Refer to the `Python <https://analytics-zoo.github.io/master/#PythonUserGuide/install/>`_, `Scala <https://analytics-zoo.github.io/master/#ScalaUserGuide/install/>`_ and `Docker <https://analytics-zoo.github.io/master/#DockerUserGuide/>`_ guides to install Analytics Zoo.
* Visit the `Document Website <https://analytics-zoo.github.io/>`_ (`mirror <https://analytics-zoo.gitee.io/>`_ in China) for more information on Analytics Zoo.
* Check the `Powered By <https://analytics-zoo.github.io/master/#powered-by/>`_ & `Presentations <https://analytics-zoo.github.io/master/#presentations/>`_ pages for real-world applications using Analytics Zoo.
* Join the `Google Group <https://groups.google.com/forum/#!forum/bigdl-user-group>`_ (or subscribe to the `Mail List <mailto:bigdl-user-group+subscribe@googlegroups.com>`_ for more questions and discussions on Analytics Zoo.


.. toctree::
   :hidden:
   :maxdepth: -1
   :caption: Overview

   overview.md

.. toctree::
   :hidden:
   :maxdepth: -1
   :caption: Python API

   zoo.automl
   zoo.common
   zoo.feature
   zoo.models
   zoo.orca
   zoo.pipeline
   zoo.ray
   zoo.tfpark
   zoo.zouwu
   zoo.util    
