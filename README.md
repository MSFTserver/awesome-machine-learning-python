# Awesome Machine Learning Python

A curated list of awesome Python machine learning frameworks, libraries and software (by language). Inspired by `awesome-php`.

_If you want to contribute to this list (please do), send me a pull request or contact me [@josephmisiti](https://twitter.com/josephmisiti).
Also, a listed repository should be deprecated if:

* Orignally from [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning/) by [@josephmisiti](https://twitter.com/josephmisiti).
* Not committed for a long time (2~3 years).

## Table of Contents

### Frameworks and Libraries
<!-- MarkdownTOC depth=4 -->

- [Awesome Machine Learning Python]
  - [Table of Contents](#table-of-contents)
    - [Frameworks and Libraries](#frameworks-and-libraries)
    - [Tools](#tools)
  - [Python](#python)
      - [Computer Vision](#python-computer-vision)
      - [Natural Language Processing](#python-natural-language-processing)
      - [General-Purpose Machine Learning](#python-general-purpose-machine-learning)
      - [Data Analysis / Data Visualization](#python-data-analysis--data-visualization)
      - [Misc Scripts / iPython Notebooks / Codebases](#python-misc-scripts--ipython-notebooks--codebases)
      - [Neural Networks](#python-neural-networks)
      - [Kaggle Competition Source Code](#python-kaggle-competition-source-code)
      - [Reinforcement Learning](#python-reinforcement-learning)
  - [TensorFlow](#tensorflow)
      - [General-Purpose Machine Learning](#tensorflow-general-purpose-machine-learning)
	  - [Tutorials](#github-tutorials)
	  - [Models/Projects](#github-projects)
	  - [Powered by TensorFlow](#github-powered-by)
	  - [Libraries](#libraries)
	  - [Tools/Utilities](#tools-utils)

### Tools

- [Misc](#tools-misc)


[Credits](#credits)

<!-- /MarkdownTOC -->

<a name="python"></a>
## Python

<a name="python-computer-vision"></a>
#### Computer Vision

* [Scikit-Image](https://github.com/scikit-image/scikit-image) - A collection of algorithms for image processing in Python.
* [Scikit-Opt](https://github.com/guofei9987/scikit-opt) - Swarm Intelligence in Python (Genetic Algorithm, Particle Swarm Optimization, Simulated Annealing, Ant Colony Algorithm, Immune Algorithm,Artificial Fish Swarm Algorithm in Python)
* [SimpleCV](http://simplecv.org/) - An open source computer vision framework that gives access to several high-powered computer vision libraries, such as OpenCV. Written on Python and runs on Mac, Windows, and Ubuntu Linux.
* [Vigranumpy](https://github.com/ukoethe/vigra) - Python bindings for the VIGRA C++ computer vision library.
* [OpenFace](https://cmusatyalab.github.io/openface/) - Free and open source face recognition with deep neural networks.
* [PCV](https://github.com/jesolem/PCV) - Open source Python module for computer vision. **[Deprecated]**
* [face_recognition](https://github.com/ageitgey/face_recognition) - Face recognition library that recognizes and manipulates faces from Python or from the command line.
* [dockerface](https://github.com/natanielruiz/dockerface) - Easy to install and use deep learning Faster R-CNN face detection for images and video in a docker container. **[Deprecated]**
* [Detectron](https://github.com/facebookresearch/Detectron) - FAIR's software system that implements state-of-the-art object detection algorithms, including Mask R-CNN. It is written in Python and powered by the Caffe2 deep learning framework. **[Deprecated]**
* [detectron2](https://github.com/facebookresearch/detectron2) - FAIR's next-generation research platform for object detection and segmentation. It is a ground-up rewrite of the previous version, Detectron, and is powered by the PyTorch deep learning framework.
* [albumentations](https://github.com/albu/albumentations) - А fast and framework agnostic image augmentation library that implements a diverse set of augmentation techniques. Supports classification, segmentation, detection out of the box. Was used to win a number of Deep Learning competitions at Kaggle, Topcoder and those that were a part of the CVPR workshops.
* [pytessarct](https://github.com/madmaze/pytesseract) - Python-tesseract is an optical character recognition (OCR) tool for python. That is, it will recognize and "read" the text embedded in images. Python-tesseract is a wrapper for [Google's Tesseract-OCR Engine](https://github.com/tesseract-ocr/tesseract).
* [imutils](https://github.com/jrosebr1/imutils) - A library containing Convenience functions to make basic image processing operations such as translation, rotation, resizing, skeletonization, and displaying Matplotlib images easier with OpenCV and Python.
* [PyTorchCV](https://github.com/donnyyou/PyTorchCV) - A PyTorch-Based Framework for Deep Learning in Computer Vision.
* [Self-supervised learning](https://pytorch-lightning-bolts.readthedocs.io/en/latest/self_supervised_models.html)
* [neural-style-pt](https://github.com/ProGamerGov/neural-style-pt) - A PyTorch implementation of Justin Johnson's neural-style (neural style transfer).
* [Detecto](https://github.com/alankbi/detecto) - Train and run a computer vision model with 5-10 lines of code.
* [neural-dream](https://github.com/ProGamerGov/neural-dream) - A PyTorch implementation of DeepDream.
* [Openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) - A real-time multi-person keypoint detection library for body, face, hands, and foot estimation
* [Deep High-Resolution-Net](https://github.com/leoxiaobin/deep-high-resolution-net.pytorch) - A PyTorch implementation of CVPR2019 paper "Deep High-Resolution Representation Learning for Human Pose Estimation"
* [dream-creator](https://github.com/ProGamerGov/dream-creator) - A PyTorch implementation of DeepDream. Allows individuals to quickly and easily train their own custom GoogleNet models with custom datasets for DeepDream.
* [Lucent](https://github.com/greentfrapp/lucent) - Tensorflow and OpenAI Clarity's Lucid adapted for PyTorch.
* [lightly](https://github.com/lightly-ai/lightly) - Lightly is a computer vision framework for self-supervised learning.
* [Learnergy](https://github.com/gugarosa/learnergy) - Energy-based machine learning models built upon PyTorch.
* [OpenVisionAPI](https://github.com/openvisionapi) - Open source computer vision API based on open source models.
* [IoT Owl](https://github.com/Ret2Me/IoT-Owl) - Light face detection and recognition system with huge possibilities, based on Microsoft Face API and TensorFlow made for small IoT devices like raspberry pi.
* [Exadel CompreFace](https://github.com/exadel-inc/CompreFace) - face recognition system that can be easily integrated into any system without prior machine learning skills. CompreFace provides REST API for face recognition, face verification, face detection, face mask detection, landmark detection, age, and gender recognition and is easily deployed with docker.
* [computer-vision-in-action](https://github.com/Charmve/computer-vision-in-action) - as known as ``L0CV``, is a new generation of computer vision open source online learning media, a cross-platform interactive learning framework integrating graphics, source code and HTML. the L0CV ecosystem — Notebook, Datasets, Source Code, and from Diving-in to Advanced — as well as the L0CV Hub.

<a name="python-natural-language-processing"></a>
#### Natural Language Processing

* [pkuseg-python](https://github.com/lancopku/pkuseg-python) - A better version of Jieba, developed by Peking University.
* [NLTK](https://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
* [Pattern](https://github.com/clips/pattern) - A web mining module for the Python programming language. It has tools for natural language processing, machine learning, among others.
* [Quepy](https://github.com/machinalis/quepy) - A python framework to transform natural language questions to queries in a database query language.
* [TextBlob](http://textblob.readthedocs.io/en/dev/) - Providing a consistent API for diving into common natural language processing (NLP) tasks. Stands on the giant shoulders of NLTK and Pattern, and plays nicely with both.
* [YAlign](https://github.com/machinalis/yalign) - A sentence aligner, a friendly tool for extracting parallel sentences from comparable corpora. **[Deprecated]**
* [jieba](https://github.com/fxsjy/jieba#jieba-1) - Chinese Words Segmentation Utilities.
* [SnowNLP](https://github.com/isnowfy/snownlp) - A library for processing Chinese text.
* [spammy](https://github.com/tasdikrahman/spammy) - A library for email Spam filtering built on top of nltk
* [loso](https://github.com/fangpenlin/loso) - Another Chinese segmentation library. **[Deprecated]**
* [genius](https://github.com/duanhongyi/genius) - A Chinese segment based on Conditional Random Field.
* [KoNLPy](http://konlpy.org) - A Python package for Korean natural language processing.
* [nut](https://github.com/pprett/nut) - Natural language Understanding Toolkit. **[Deprecated]**
* [Rosetta](https://github.com/columbia-applied-data-science/rosetta) - Text processing tools and wrappers (e.g. Vowpal Wabbit)
* [BLLIP Parser](https://pypi.org/project/bllipparser/) - Python bindings for the BLLIP Natural Language Parser (also known as the Charniak-Johnson parser). **[Deprecated]**
* [PyNLPl](https://github.com/proycon/pynlpl) - Python Natural Language Processing Library. General purpose NLP library for Python. Also contains some specific modules for parsing common NLP formats, most notably for [FoLiA](https://proycon.github.io/folia/), but also ARPA language models, Moses phrasetables, GIZA++ alignments.
* [PySS3](https://github.com/sergioburdisso/pyss3) - Python package that implements a novel white-box machine learning model for text classification, called SS3. Since SS3 has the ability to visually explain its rationale, this package also comes with easy-to-use interactive visualizations tools ([online demos](http://tworld.io/ss3/)).
* [python-ucto](https://github.com/proycon/python-ucto) - Python binding to ucto (a unicode-aware rule-based tokenizer for various languages).
* [python-frog](https://github.com/proycon/python-frog) - Python binding to Frog, an NLP suite for Dutch. (pos tagging, lemmatisation, dependency parsing, NER)
* [python-zpar](https://github.com/EducationalTestingService/python-zpar) - Python bindings for [ZPar](https://github.com/frcchang/zpar), a statistical part-of-speech-tagger, constituency parser, and dependency parser for English.
* [colibri-core](https://github.com/proycon/colibri-core) - Python binding to C++ library for extracting and working with basic linguistic constructions such as n-grams and skipgrams in a quick and memory-efficient way.
* [spaCy](https://github.com/explosion/spaCy) - Industrial strength NLP with Python and Cython.
* [PyStanfordDependencies](https://github.com/dmcc/PyStanfordDependencies) - Python interface for converting Penn Treebank trees to Stanford Dependencies.
* [Distance](https://github.com/doukremt/distance) - Levenshtein and Hamming distance computation. **[Deprecated]**
* [Fuzzy Wuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching in Python.
* [jellyfish](https://github.com/jamesturk/jellyfish) - a python library for doing approximate and phonetic matching of strings.
* [editdistance](https://pypi.org/project/editdistance/) - fast implementation of edit distance.
* [textacy](https://github.com/chartbeat-labs/textacy) - higher-level NLP built on Spacy.
* [stanford-corenlp-python](https://github.com/dasmith/stanford-corenlp-python) - Python wrapper for [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP) **[Deprecated]**
* [CLTK](https://github.com/cltk/cltk) - The Classical Language Toolkit.
* [Rasa](https://github.com/RasaHQ/rasa) - A "machine learning framework to automate text-and voice-based conversations."
* [yase](https://github.com/PPACI/yase) - Transcode sentence (or other sequence) to list of word vector .
* [Polyglot](https://github.com/aboSamoor/polyglot) - Multilingual text (NLP) processing toolkit.
* [DrQA](https://github.com/facebookresearch/DrQA) - Reading Wikipedia to answer open-domain questions.
* [Dedupe](https://github.com/dedupeio/dedupe) - A python library for accurate and scalable fuzzy matching, record deduplication and entity-resolution.
* [Snips NLU](https://github.com/snipsco/snips-nlu) - Natural Language Understanding library for intent classification and entity extraction
* [NeuroNER](https://github.com/Franck-Dernoncourt/NeuroNER) - Named-entity recognition using neural networks providing state-of-the-art-results
* [DeepPavlov](https://github.com/deepmipt/DeepPavlov/) - conversational AI library with many pre-trained Russian NLP models.
* [BigARTM](https://github.com/bigartm/bigartm) - topic modelling platform.
* [NALP](https://github.com/gugarosa/nalp) - A Natural Adversarial Language Processing framework built over Tensorflow.
* [DL Translate](https://github.com/xhlulu/dl-translate) - A deep learning-based translation library between 50 languages, built with `transformers`.

<a name="python-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning

 * [RexMex](https://github.com/AstraZeneca/rexmex) -> A general purpose recommender metrics library for fair evaluation.
 * [ChemicalX](https://github.com/AstraZeneca/chemicalx) -> A PyTorch based deep learning library for drug pair scoring
 * [Microsoft ML for Apache Spark](https://github.com/Azure/mmlspark) -> A distributed machine learning framework Apache Spark
 * [Shapley](https://github.com/benedekrozemberczki/shapley) -> A data-driven framework to quantify the value of classifiers in a machine learning ensemble.
 * [igel](https://github.com/nidhaloff/igel) -> A delightful machine learning tool that allows you to train/fit, test and use models **without writing code**
 * [ML Model building](https://github.com/Shanky-21/Machine_learning) -> A Repository Containing Classification, Clustering, Regression, Recommender Notebooks with illustration to make them.
 * [ML/DL project template](https://github.com/PyTorchLightning/deep-learning-project-template)
 * [PyTorch Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) -> A temporal extension of PyTorch Geometric for dynamic graph representation learning.
 * [Little Ball of Fur](https://github.com/benedekrozemberczki/littleballoffur) -> A graph sampling extension library for NetworkX with a Scikit-Learn like API.
 * [Karate Club](https://github.com/benedekrozemberczki/karateclub) -> An unsupervised machine learning extension library for NetworkX with a Scikit-Learn like API.
* [Auto_ViML](https://github.com/AutoViML/Auto_ViML) -> Automatically Build Variant Interpretable ML models fast! Auto_ViML is pronounced "auto vimal", is a comprehensive and scalable Python AutoML toolkit with imbalanced handling, ensembling, stacking and built-in feature selection. Featured in <a href="https://towardsdatascience.com/why-automl-is-an-essential-new-tool-for-data-scientists-2d9ab4e25e46?source=friends_link&sk=d03a0cc55c23deb497d546d6b9be0653">Medium article</a>.
* [PyOD](https://github.com/yzhao062/pyod) -> Python Outlier Detection, comprehensive and scalable Python toolkit for detecting outlying objects in multivariate data. Featured for Advanced models, including Neural Networks/Deep Learning and Outlier Ensembles.
* [steppy](https://github.com/neptune-ml/steppy) -> Lightweight, Python library for fast and reproducible machine learning experimentation. Introduces a very simple interface that enables clean machine learning pipeline design.
* [steppy-toolkit](https://github.com/neptune-ml/steppy-toolkit) -> Curated collection of the neural networks, transformers and models that make your machine learning work faster and more effective.
* [CNTK](https://github.com/Microsoft/CNTK) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit. Documentation can be found [here](https://docs.microsoft.com/cognitive-toolkit/).
* [Couler](https://github.com/couler-proj/couler) - Unified interface for constructing and managing machine learning workflows on different workflow engines, such as Argo Workflows, Tekton Pipelines, and Apache Airflow.
* [auto_ml](https://github.com/ClimbsRocks/auto_ml) - Automated machine learning for production and analytics. Lets you focus on the fun parts of ML, while outputting production-ready code, and detailed analytics of your dataset and results. Includes support for NLP, XGBoost, CatBoost, LightGBM, and soon, deep learning.
* [machine learning](https://github.com/jeff1evesque/machine-learning) - automated build consisting of a [web-interface](https://github.com/jeff1evesque/machine-learning#web-interface), and set of [programmatic-interface](https://github.com/jeff1evesque/machine-learning#programmatic-interface) API, for support vector machines. Corresponding dataset(s) are stored into a SQL database, then generated model(s) used for prediction(s), are stored into a NoSQL datastore.
* [XGBoost](https://github.com/dmlc/xgboost) - Python bindings for eXtreme Gradient Boosting (Tree) Library.
* [Apache SINGA](https://singa.apache.org) - An Apache Incubating project for developing an open source machine learning library.
* [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Book/iPython notebooks on Probabilistic Programming in Python.
* [Featureforge](https://github.com/machinalis/featureforge) A set of tools for creating and testing machine learning features, with a scikit-learn compatible API.
* [MLlib in Apache Spark](http://spark.apache.org/docs/latest/mllib-guide.html) - Distributed machine learning library in Spark
* [Hydrosphere Mist](https://github.com/Hydrospheredata/mist) - a service for deployment Apache Spark MLLib machine learning models as realtime, batch or reactive web services.
* [scikit-learn](https://scikit-learn.org/) - A Python module for machine learning built on top of SciPy.
* [metric-learn](https://github.com/metric-learn/metric-learn) - A Python module for metric learning.
* [Intel(R) Extension for Scikit-learn](https://github.com/intel/scikit-learn-intelex) - A seamless way to speed up your Scikit-learn applications with no accuracy loss and code changes.
* [SimpleAI](https://github.com/simpleai-team/simpleai) Python implementation of many of the artificial intelligence algorithms described in the book "Artificial Intelligence, a Modern Approach". It focuses on providing an easy to use, well documented and tested library.
* [astroML](https://www.astroml.org/) - Machine Learning and Data Mining for Astronomy.
* [graphlab-create](https://turi.com/products/create/docs/) - A library with various machine learning models (regression, clustering, recommender systems, graph analytics, etc.) implemented on top of a disk-backed DataFrame.
* [BigML](https://bigml.com) - A library that contacts external servers.
* [pattern](https://github.com/clips/pattern) - Web mining module for Python.
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing.
* [Pylearn2](https://github.com/lisa-lab/pylearn2) - A Machine Learning library based on [Theano](https://github.com/Theano/Theano). **[Deprecated]**
* [keras](https://github.com/keras-team/keras) - High-level neural networks frontend for [TensorFlow](https://github.com/tensorflow/tensorflow), [CNTK](https://github.com/Microsoft/CNTK) and [Theano](https://github.com/Theano/Theano).
* [Lasagne](https://github.com/Lasagne/Lasagne) - Lightweight library to build and train neural networks in Theano.
* [hebel](https://github.com/hannes-brt/hebel) - GPU-Accelerated Deep Learning Library in Python. **[Deprecated]**
* [Chainer](https://github.com/chainer/chainer) - Flexible neural network framework.
* [prophet](https://facebook.github.io/prophet/) - Fast and automated time series forecasting framework by Facebook.
* [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modelling for Humans.
* [topik](https://github.com/ContinuumIO/topik) - Topic modelling toolkit. **[Deprecated]**
* [PyBrain](https://github.com/pybrain/pybrain) - Another Python Machine Learning Library.
* [Brainstorm](https://github.com/IDSIA/brainstorm) - Fast, flexible and fun neural networks. This is the successor of PyBrain.
* [Surprise](https://surpriselib.com) - A scikit for building and analyzing recommender systems.
* [implicit](https://implicit.readthedocs.io/en/latest/quickstart.html) - Fast Python Collaborative Filtering for Implicit Datasets.
* [LightFM](https://making.lyst.com/lightfm/docs/home.html) -  A Python implementation of a number of popular recommendation algorithms for both implicit and explicit feedback.
* [Crab](https://github.com/muricoca/crab) - A flexible, fast recommender engine. **[Deprecated]**
* [python-recsys](https://github.com/ocelma/python-recsys) - A Python library for implementing a Recommender System.
* [thinking bayes](https://github.com/AllenDowney/ThinkBayes) - Book on Bayesian Analysis.
* [Image-to-Image Translation with Conditional Adversarial Networks](https://github.com/williamFalcon/pix2pix-keras) - Implementation of image to image (pix2pix) translation from the paper by [isola et al](https://arxiv.org/pdf/1611.07004.pdf).[DEEP LEARNING]
* [Restricted Boltzmann Machines](https://github.com/echen/restricted-boltzmann-machines) -Restricted Boltzmann Machines in Python. [DEEP LEARNING]
* [Bolt](https://github.com/pprett/bolt) - Bolt Online Learning Toolbox. **[Deprecated]**
* [CoverTree](https://github.com/patvarilly/CoverTree) - Python implementation of cover trees, near-drop-in replacement for scipy.spatial.kdtree **[Deprecated]**
* [nilearn](https://github.com/nilearn/nilearn) - Machine learning for NeuroImaging in Python.
* [neuropredict](https://github.com/raamana/neuropredict) - Aimed at novice machine learners and non-expert programmers, this package offers easy (no coding needed) and comprehensive machine learning (evaluation and full report of predictive performance WITHOUT requiring you to code) in Python for NeuroImaging and any other type of features. This is aimed at absorbing much of the ML workflow, unlike other packages like nilearn and pymvpa, which require you to learn their API and code to produce anything useful.
* [imbalanced-learn](https://imbalanced-learn.org/stable/) - Python module to perform under sampling and oversampling with various techniques.
* [imbalanced-ensemble](https://github.com/ZhiningLiu1998/imbalanced-ensemble) - Python toolbox for quick implementation, modification, evaluation, and visualization of ensemble learning algorithms for class-imbalanced data. Supports out-of-the-box multi-class imbalanced (long-tailed) classification.
* [Shogun](https://github.com/shogun-toolbox/shogun) - The Shogun Machine Learning Toolbox.
* [Pyevolve](https://github.com/perone/Pyevolve) - Genetic algorithm framework. **[Deprecated]**
* [Caffe](https://github.com/BVLC/caffe) - A deep learning framework developed with cleanliness, readability, and speed in mind.
* [breze](https://github.com/breze-no-salt/breze) - Theano based library for deep and recurrent neural networks.
* [Cortex](https://github.com/cortexlabs/cortex) - Open source platform for deploying machine learning models in production.
* [pyhsmm](https://github.com/mattjj/pyhsmm) - library for approximate unsupervised inference in Bayesian Hidden Markov Models (HMMs) and explicit-duration Hidden semi-Markov Models (HSMMs), focusing on the Bayesian Nonparametric extensions, the HDP-HMM and HDP-HSMM, mostly with weak-limit approximations.
* [SKLL](https://github.com/EducationalTestingService/skll) - A wrapper around scikit-learn that makes it simpler to conduct experiments.
* [neurolab](https://github.com/zueve/neurolab)
* [Spearmint](https://github.com/HIPS/Spearmint) - Spearmint is a package to perform Bayesian optimization according to the algorithms outlined in the paper: Practical Bayesian Optimization of Machine Learning Algorithms. Jasper Snoek, Hugo Larochelle and Ryan P. Adams. Advances in Neural Information Processing Systems, 2012. **[Deprecated]**
* [Pebl](https://github.com/abhik/pebl/) - Python Environment for Bayesian Learning. **[Deprecated]**
* [Theano](https://github.com/Theano/Theano/) - Optimizing GPU-meta-programming code generating array oriented optimizing math compiler in Python.
* [TensorFlow](https://github.com/tensorflow/tensorflow/) - Open source software library for numerical computation using data flow graphs.
* [pomegranate](https://github.com/jmschrei/pomegranate) - Hidden Markov Models for Python, implemented in Cython for speed and efficiency.
* [python-timbl](https://github.com/proycon/python-timbl) - A Python extension module wrapping the full TiMBL C++ programming interface. Timbl is an elaborate k-Nearest Neighbours machine learning toolkit.
* [deap](https://github.com/deap/deap) - Evolutionary algorithm framework.
* [pydeep](https://github.com/andersbll/deeppy) - Deep Learning In Python. **[Deprecated]**
* [mlxtend](https://github.com/rasbt/mlxtend) - A library consisting of useful tools for data science and machine learning tasks.
* [neon](https://github.com/NervanaSystems/neon) - Nervana's [high-performance](https://github.com/soumith/convnet-benchmarks) Python-based Deep Learning framework [DEEP LEARNING]. **[Deprecated]**
* [Optunity](https://optunity.readthedocs.io/en/latest/) - A library dedicated to automated hyperparameter optimization with a simple, lightweight API to facilitate drop-in replacement of grid search.
* [Neural Networks and Deep Learning](https://github.com/mnielsen/neural-networks-and-deep-learning) - Code samples for my book "Neural Networks and Deep Learning" [DEEP LEARNING].
* [Annoy](https://github.com/spotify/annoy) - Approximate nearest neighbours implementation.
* [TPOT](https://github.com/EpistasisLab/tpot) - Tool that automatically creates and optimizes machine learning pipelines using genetic programming. Consider it your personal data science assistant, automating a tedious part of machine learning.
* [pgmpy](https://github.com/pgmpy/pgmpy) A python library for working with Probabilistic Graphical Models.
* [DIGITS](https://github.com/NVIDIA/DIGITS) - The Deep Learning GPU Training System (DIGITS) is a web application for training deep learning models.
* [Orange](https://orange.biolab.si/) - Open source data visualization and data analysis for novices and experts.
* [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.
* [milk](https://github.com/luispedro/milk) - Machine learning toolkit focused on supervised classification. **[Deprecated]**
* [TFLearn](https://github.com/tflearn/tflearn) - Deep learning library featuring a higher-level API for TensorFlow.
* [REP](https://github.com/yandex/rep) - an IPython-based environment for conducting data-driven research in a consistent and reproducible way. REP is not trying to substitute scikit-learn, but extends it and provides better user experience. **[Deprecated]**
* [rgf_python](https://github.com/RGF-team/rgf) - Python bindings for Regularized Greedy Forest (Tree) Library.
* [skbayes](https://github.com/AmazaspShumik/sklearn-bayes) - Python package for Bayesian Machine Learning with scikit-learn API.
* [fuku-ml](https://github.com/fukuball/fuku-ml) - Simple machine learning library, including Perceptron, Regression, Support Vector Machine, Decision Tree and more, it's easy to use and easy to learn for beginners.
* [Xcessiv](https://github.com/reiinakano/xcessiv) - A web-based application for quick, scalable, and automated hyperparameter tuning and stacked ensembling.
* [PyTorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration
* [PyTorch Lightning](https://github.com/PyTorchLightning/pytorch-lightning) - The lightweight PyTorch wrapper for high-performance AI research.
* [PyTorch Lightning Bolts](https://github.com/PyTorchLightning/pytorch-lightning-bolts) - Toolbox of models, callbacks, and datasets for AI/ML researchers.
* [skorch](https://github.com/skorch-dev/skorch) - A scikit-learn compatible neural network library that wraps PyTorch.
* [ML-From-Scratch](https://github.com/eriklindernoren/ML-From-Scratch) - Implementations of Machine Learning models from scratch in Python with a focus on transparency. Aims to showcase the nuts and bolts of ML in an accessible way.
* [Edward](http://edwardlib.org/) - A library for probabilistic modeling, inference, and criticism. Built on top of TensorFlow.
* [xRBM](https://github.com/omimo/xRBM) - A library for Restricted Boltzmann Machine (RBM) and its conditional variants in Tensorflow.
* [CatBoost](https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box. It is easy to install, well documented and supports CPU and GPU (even multi-GPU) computation.
* [stacked_generalization](https://github.com/fukatani/stacked_generalization) - Implementation of machine learning stacking technique as a handy library in Python.
* [modAL](https://github.com/modAL-python/modAL) - A modular active learning framework for Python, built on top of scikit-learn.
* [Cogitare](https://github.com/cogitare-ai/cogitare): A Modern, Fast, and Modular Deep Learning and Machine Learning framework for Python.
* [Parris](https://github.com/jgreenemi/Parris) - Parris, the automated infrastructure setup tool for machine learning algorithms.
* [neonrvm](https://github.com/siavashserver/neonrvm) - neonrvm is an open source machine learning library based on RVM technique. It's written in C programming language and comes with Python programming language bindings.
* [Turi Create](https://github.com/apple/turicreate) - Machine learning from Apple. Turi Create simplifies the development of custom machine learning models. You don't have to be a machine learning expert to add recommendations, object detection, image classification, image similarity or activity classification to your app.
* [xLearn](https://github.com/aksnzhy/xlearn) - A high performance, easy-to-use, and scalable machine learning package, which can be used to solve large-scale machine learning problems. xLearn is especially useful for solving machine learning problems on large-scale sparse data, which is very common in Internet services such as online advertisement and recommender systems.
* [mlens](https://github.com/flennerhag/mlens) - A high performance, memory efficient, maximally parallelized ensemble learning, integrated with scikit-learn.
* [Thampi](https://github.com/scoremedia/thampi) - Machine Learning Prediction System on AWS Lambda
* [MindsDB](https://github.com/mindsdb/mindsdb) - Open Source framework to streamline use of neural networks.
* [Microsoft Recommenders](https://github.com/Microsoft/Recommenders): Examples and best practices for building recommendation systems, provided as Jupyter notebooks. The repo contains some of the latest state of the art algorithms from Microsoft Research as well as from other companies and institutions.
* [StellarGraph](https://github.com/stellargraph/stellargraph): Machine Learning on Graphs, a Python library for machine learning on graph-structured (network-structured) data.
* [BentoML](https://github.com/bentoml/bentoml): Toolkit for package and deploy machine learning models for serving in production
* [MiraiML](https://github.com/arthurpaulino/miraiml): An asynchronous engine for continuous & autonomous machine learning, built for real-time usage.
* [numpy-ML](https://github.com/ddbourgin/numpy-ml): Reference implementations of ML models written in numpy
* [Neuraxle](https://github.com/Neuraxio/Neuraxle): A framework providing the right abstractions to ease research, development, and deployment of your ML pipelines.
* [Cornac](https://github.com/PreferredAI/cornac) - A comparative framework for multimodal recommender systems with a focus on models leveraging auxiliary data.
* [JAX](https://github.com/google/jax) - JAX is Autograd and XLA, brought together for high-performance machine learning research.
* [Catalyst](https://github.com/catalyst-team/catalyst) - High-level utils for PyTorch DL & RL research. It was developed with a focus on reproducibility, fast experimentation and code/ideas reusing. Being able to research/develop something new, rather than write another regular train loop.
* [Fastai](https://github.com/fastai/fastai) - High-level wrapper built on the top of Pytorch which supports vision, text, tabular data and collaborative filtering.
* [scikit-multiflow](https://github.com/scikit-multiflow/scikit-multiflow) - A machine learning framework for multi-output/multi-label and stream data.
* [Lightwood](https://github.com/mindsdb/lightwood) - A Pytorch based framework that breaks down machine learning problems into smaller blocks that can be glued together seamlessly with objective to build predictive models with one line of code.
* [bayeso](https://github.com/jungtaekkim/bayeso) - A simple, but essential Bayesian optimization package, written in Python.
* [mljar-supervised](https://github.com/mljar/mljar-supervised) - An Automated Machine Learning (AutoML) python package for tabular data. It can handle: Binary Classification, MultiClass Classification and Regression. It provides explanations and markdown reports.
* [evostra](https://github.com/alirezamika/evostra) - A fast Evolution Strategy implementation in Python.
* [Determined](https://github.com/determined-ai/determined) - Scalable deep learning training platform, including integrated support for distributed training, hyperparameter tuning, experiment tracking, and model management.
* [PySyft](https://github.com/OpenMined/PySyft) - A Python library for secure and private Deep Learning built on PyTorch and TensorFlow.
* [PyGrid](https://github.com/OpenMined/PyGrid/) - Peer-to-peer network of data owners and data scientists who can collectively train AI models using PySyft
* [sktime](https://github.com/alan-turing-institute/sktime) - A unified framework for machine learning with time series
* [OPFython](https://github.com/gugarosa/opfython) - A Python-inspired implementation of the Optimum-Path Forest classifier.
* [Opytimizer](https://github.com/gugarosa/opytimizer) - Python-based meta-heuristic optimization techniques.
* [Gradio](https://github.com/gradio-app/gradio) - A Python library for quickly creating and sharing demos of models. Debug models interactively in your browser, get feedback from collaborators, and generate public links without deploying anything.
* [Hub](https://github.com/activeloopai/Hub) - Fastest unstructured dataset management for TensorFlow/PyTorch. Stream & version-control data. Store even petabyte-scale data in a single numpy-like array on the cloud accessible on any machine. Visit [activeloop.ai](https://activeloop.ai) for more info.
* [Synthia](https://github.com/dmey/synthia) - Multidimensional synthetic data generation in Python.
* [ByteHub](https://github.com/bytehub-ai/bytehub) - An easy-to-use, Python-based feature store. Optimized for time-series data.
* [Backprop](https://github.com/backprop-ai/backprop) - Backprop makes it simple to use, finetune, and deploy state-of-the-art ML models.
* [River](https://github.com/online-ml/river): A framework for general purpose online machine learning.
* [FEDOT](https://github.com/nccr-itmo/FEDOT): An AutoML framework for the automated design of composite modeling pipelines. It can handle classification, regression, and time series forecasting tasks on different types of data (including multi-modal datasets).
* [Sklearn-genetic-opt](https://github.com/rodrigo-arenas/Sklearn-genetic-opt): An AutoML package for hyperparameters tuning using evolutionary algorithms, with built-in callbacks, plotting, remote logging and more.
* [Evidently](https://github.com/evidentlyai/evidently): Interactive reports to analyze machine learning models during validation or production monitoring.
* [Streamlit](https://github.com/streamlit/streamlit): Streamlit is an framework to create beautiful data apps in hours, not weeks.
* [Optuna](https://github.com/optuna/optuna): Optuna is an automatic hyperparameter optimization software framework, particularly designed for machine learning.
* [Deepchecks](https://github.com/deepchecks/deepchecks): Validation & testing of machine learning models and data during model development, deployment, and production. This includes checks and suites related to various types of issues, such as model performance, data integrity, distribution mismatches, and more.

<a name="python-data-analysis--data-visualization"></a>
#### Data Analysis / Data Visualization
* [DataVisualization](https://github.com/Shanky-21/Data_visualization) - A Github Repository Where you can Learn Datavisualizatoin Basics to Intermediate level.
* [Cartopy](https://scitools.org.uk/cartopy/docs/latest/) - Cartopy is a Python package designed for geospatial data processing in order to produce maps and other geospatial data analyses.
* [SciPy](https://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [NumPy](https://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [AutoViz](https://github.com/AutoViML/AutoViz) AutoViz performs automatic visualization of any dataset with a single line of Python code. Give it any input file (CSV, txt or json) of any size and AutoViz will visualize it. See <a href="https://towardsdatascience.com/autoviz-a-new-tool-for-automated-visualization-ec9c1744a6ad?source=friends_link&sk=c9e9503ec424b191c6096d7e3f515d10">Medium article</a>.
* [Numba](https://numba.pydata.org/) - Python JIT (just in time) compiler to LLVM aimed at scientific Python by the developers of Cython and NumPy.
* [Mars](https://github.com/mars-project/mars) - A tensor-based framework for large-scale data computation which is often regarded as a parallel and distributed version of NumPy.
* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [igraph](https://igraph.org/python/) - binding to igraph library - General purpose graph library.
* [Pandas](https://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [ParaMonte](https://github.com/cdslaborg/paramonte) - A general-purpose Python library for Bayesian data analysis and visualization via serial/parallel Monte Carlo and MCMC simulations. Documentation can be found [here](https://www.cdslab.org/paramonte/).
* [Vaex](https://github.com/vaexio/vaex) - A high performance Python library for lazy Out-of-Core DataFrames (similar to Pandas), to visualize and explore big tabular datasets. Documentation can be found [here](https://vaex.io/docs/index.html).
* [Open Mining](https://github.com/mining/mining) - Business Intelligence (BI) in Python (Pandas web interface) **[Deprecated]**
* [PyMC](https://github.com/pymc-devs/pymc) - Markov Chain Monte Carlo sampling toolkit.
* [zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library.
* [PyDy](https://www.pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion based around NumPy, SciPy, IPython, and matplotlib.
* [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.
* [astropy](https://www.astropy.org/) - A community Python library for Astronomy.
* [matplotlib](https://matplotlib.org/) - A Python 2D plotting library.
* [bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
* [plotly](https://plot.ly/python/) - Collaborative web plotting for Python and matplotlib.
* [altair](https://github.com/altair-viz/altair) - A Python to Vega translator.
* [d3py](https://github.com/mikedewar/d3py) - A plotting library for Python, based on [D3.js](https://d3js.org/).
* [PyDexter](https://github.com/D3xterjs/pydexter) - Simple plotting for Python. Wrapper for D3xterjs; easily render charts in-browser.
* [ggplot](https://github.com/yhat/ggpy) - Same API as ggplot2 for R. **[Deprecated]**
* [ggfortify](https://github.com/sinhrks/ggfortify) - Unified interface to ggplot2 popular R packages.
* [Kartograph.py](https://github.com/kartograph/kartograph.py) - Rendering beautiful SVG maps in Python.
* [pygal](http://pygal.org/en/stable/) - A Python SVG Charts Creator.
* [PyQtGraph](https://github.com/pyqtgraph/pyqtgraph) - A pure-python graphics and GUI library built on PyQt4 / PySide and NumPy.
* [pycascading](https://github.com/twitter/pycascading) **[Deprecated]**
* [Petrel](https://github.com/AirSage/Petrel) - Tools for writing, submitting, debugging, and monitoring Storm topologies in pure Python.
* [Blaze](https://github.com/blaze/blaze) - NumPy and Pandas interface to Big Data.
* [emcee](https://github.com/dfm/emcee) - The Python ensemble sampling toolkit for affine-invariant MCMC.
* [windML](https://github.com/cigroup-ol/windml) - A Python Framework for Wind Energy Analysis and Prediction.
* [vispy](https://github.com/vispy/vispy) - GPU-based high-performance interactive OpenGL 2D/3D data visualization library.
* [cerebro2](https://github.com/numenta/nupic.cerebro2) A web-based visualization and debugging platform for NuPIC. **[Deprecated]**
* [NuPIC Studio](https://github.com/htm-community/nupic.studio) An all-in-one NuPIC Hierarchical Temporal Memory visualization and debugging super-tool! **[Deprecated]**
* [SparklingPandas](https://github.com/sparklingpandas/sparklingpandas) Pandas on PySpark (POPS).
* [Seaborn](https://seaborn.pydata.org/) - A python visualization library based on matplotlib.
* [ipychart](https://github.com/nicohlr/ipychart) - The power of Chart.js in Jupyter Notebook.
* [bqplot](https://github.com/bloomberg/bqplot) - An API for plotting in Jupyter (IPython).
* [pastalog](https://github.com/rewonc/pastalog) - Simple, realtime visualization of neural network training performance.
* [Superset](https://github.com/apache/incubator-superset) - A data exploration platform designed to be visual, intuitive, and interactive.
* [Dora](https://github.com/nathanepstein/dora) - Tools for exploratory data analysis in Python.
* [Ruffus](http://www.ruffus.org.uk) - Computation Pipeline library for python.
* [SOMPY](https://github.com/sevamoo/SOMPY) - Self Organizing Map written in Python (Uses neural networks for data analysis).
* [somoclu](https://github.com/peterwittek/somoclu) Massively parallel self-organizing maps: accelerate training on multicore CPUs, GPUs, and clusters, has python API.
* [HDBScan](https://github.com/lmcinnes/hdbscan) - implementation of the hdbscan algorithm in Python - used for clustering
* [visualize_ML](https://github.com/ayush1997/visualize_ML) - A python package for data exploration and data analysis. **[Deprecated]**
* [scikit-plot](https://github.com/reiinakano/scikit-plot) - A visualization library for quick and easy generation of common plots in data analysis and machine learning.
* [Bowtie](https://github.com/jwkvam/bowtie) - A dashboard library for interactive visualizations using flask socketio and react.
* [lime](https://github.com/marcotcr/lime) - Lime is about explaining what machine learning classifiers (or models) are doing. It is able to explain any black box classifier, with two or more classes.
* [PyCM](https://github.com/sepandhaghighi/pycm) - PyCM is a multi-class confusion matrix library written in Python that supports both input data vectors and direct matrix, and a proper tool for post-classification model evaluation that supports most classes and overall statistics parameters
* [Dash](https://github.com/plotly/dash) - A framework for creating analytical web applications built on top of Plotly.js, React, and Flask
* [Lambdo](https://github.com/asavinov/lambdo) - A workflow engine for solving machine learning problems by combining in one analysis pipeline (i) feature engineering and machine learning (ii) model training and prediction (iii) table population and column evaluation via user-defined (Python) functions.
* [TensorWatch](https://github.com/microsoft/tensorwatch) - Debugging and visualization tool for machine learning and data science. It extensively leverages Jupyter Notebook to show real-time visualizations of data in running processes such as machine learning training.
* [dowel](https://github.com/rlworkgroup/dowel) - A little logger for machine learning research. Output any object to the terminal, CSV, TensorBoard, text logs on disk, and more with just one call to `logger.log()`.

<a name="python-misc-scripts--ipython-notebooks--codebases"></a>
#### Misc Scripts / iPython Notebooks / Codebases
* [MiniGrad](https://github.com/kennysong/minigrad) – A minimal, educational, Pythonic implementation of autograd (~100 loc).
* [Map/Reduce implementations of common ML algorithms](https://github.com/Yannael/BigDataAnalytics_INFOH515): Jupyter notebooks that cover how to implement from scratch different ML algorithms (ordinary least squares, gradient descent, k-means, alternating least squares), using Python NumPy, and how to then make these implementations scalable using Map/Reduce and Spark.
* [BioPy](https://github.com/jaredthecoder/BioPy) - Biologically-Inspired and Machine Learning Algorithms in Python. **[Deprecated]**
* [CAEs for Data Assimilation](https://github.com/julianmack/Data_Assimilation) - Convolutional autoencoders for 3D image/field compression applied to reduced order [Data Assimilation](https://en.wikipedia.org/wiki/Data_assimilation).
* [SVM Explorer](https://github.com/plotly/dash-svm) - Interactive SVM Explorer, using Dash and scikit-learn
* [pattern_classification](https://github.com/rasbt/pattern_classification)
* [thinking stats 2](https://github.com/Wavelets/ThinkStats2)
* [hyperopt](https://github.com/hyperopt/hyperopt-sklearn)
* [numpic](https://github.com/numenta/nupic)
* [2012-paper-diginorm](https://github.com/dib-lab/2012-paper-diginorm)
* [A gallery of interesting IPython notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
* [ipython-notebooks](https://github.com/ogrisel/notebooks)
* [data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks) - Continually updated Data Science Python Notebooks: Spark, Hadoop MapReduce, HDFS, AWS, Kaggle, scikit-learn, matplotlib, pandas, NumPy, SciPy, and various command lines.
* [decision-weights](https://github.com/CamDavidsonPilon/decision-weights)
* [Sarah Palin LDA](https://github.com/Wavelets/sarah-palin-lda) - Topic Modeling the Sarah Palin emails.
* [Diffusion Segmentation](https://github.com/Wavelets/diffusion-segmentation) - A collection of image segmentation algorithms based on diffusion methods.
* [Scipy Tutorials](https://github.com/Wavelets/scipy-tutorials) - SciPy tutorials. This is outdated, check out scipy-lecture-notes.
* [Crab](https://github.com/marcelcaraciolo/crab) - A recommendation engine library for Python.
* [BayesPy](https://github.com/maxsklar/BayesPy) - Bayesian Inference Tools in Python.
* [scikit-learn tutorials](https://github.com/GaelVaroquaux/scikit-learn-tutorial) - Series of notebooks for learning scikit-learn.
* [sentiment-analyzer](https://github.com/madhusudancs/sentiment-analyzer) - Tweets Sentiment Analyzer
* [sentiment_classifier](https://github.com/kevincobain2000/sentiment_classifier) - Sentiment classifier using word sense disambiguation.
* [group-lasso](https://github.com/fabianp/group_lasso) - Some experiments with the coordinate descent algorithm used in the (Sparse) Group Lasso model.
* [jProcessing](https://github.com/kevincobain2000/jProcessing) - Kanji / Hiragana / Katakana to Romaji Converter. Edict Dictionary & parallel sentences Search. Sentence Similarity between two JP Sentences. Sentiment Analysis of Japanese Text. Run Cabocha(ISO--8859-1 configured) in Python.
* [mne-python-notebooks](https://github.com/mne-tools/mne-python-notebooks) - IPython notebooks for EEG/MEG data processing using mne-python.
* [Neon Course](https://github.com/NervanaSystems/neon_course) - IPython notebooks for a complete course around understanding Nervana's Neon.
* [pandas cookbook](https://github.com/jvns/pandas-cookbook) - Recipes for using Python's pandas library.
* [climin](https://github.com/BRML/climin) - Optimization library focused on machine learning, pythonic implementations of gradient descent, LBFGS, rmsprop, adadelta and others.
* [Allen Downey’s Data Science Course](https://github.com/AllenDowney/DataScience) - Code for Data Science at Olin College, Spring 2014.
* [Allen Downey’s Think Bayes Code](https://github.com/AllenDowney/ThinkBayes) - Code repository for Think Bayes.
* [Allen Downey’s Think Complexity Code](https://github.com/AllenDowney/ThinkComplexity) - Code for Allen Downey's book Think Complexity.
* [Allen Downey’s Think OS Code](https://github.com/AllenDowney/ThinkOS) - Text and supporting code for Think OS: A Brief Introduction to Operating Systems.
* [Python Programming for the Humanities](https://www.karsdorp.io/python-course/) - Course for Python programming for the Humanities, assuming no prior knowledge. Heavy focus on text processing / NLP.
* [GreatCircle](https://github.com/mwgg/GreatCircle) - Library for calculating great circle distance.
* [Optunity examples](http://optunity.readthedocs.io/en/latest/notebooks/index.html) - Examples demonstrating how to use Optunity in synergy with machine learning libraries.
* [Dive into Machine Learning  with Python Jupyter notebook and scikit-learn](https://github.com/hangtwenty/dive-into-machine-learning) - "I learned Python by hacking first, and getting serious *later.* I wanted to do this with Machine Learning. If this is your style, join me in getting a bit ahead of yourself."
* [TDB](https://github.com/ericjang/tdb) - TensorDebugger (TDB) is a visual debugger for deep learning. It features interactive, node-by-node debugging and visualization for TensorFlow.
* [Suiron](https://github.com/kendricktan/suiron/) - Machine Learning for RC Cars.
* [Introduction to machine learning with scikit-learn](https://github.com/justmarkham/scikit-learn-videos) - IPython notebooks from Data School's video tutorials on scikit-learn.
* [Practical XGBoost in Python](https://parrotprediction.teachable.com/p/practical-xgboost-in-python) - comprehensive online course about using XGBoost in Python.
* [Introduction to Machine Learning with Python](https://github.com/amueller/introduction_to_ml_with_python) - Notebooks and code for the book "Introduction to Machine Learning with Python"
* [Pydata book](https://github.com/wesm/pydata-book) - Materials and IPython notebooks for "Python for Data Analysis" by Wes McKinney, published by O'Reilly Media
* [Homemade Machine Learning](https://github.com/trekhleb/homemade-machine-learning) - Python examples of popular machine learning algorithms with interactive Jupyter demos and math being explained
* [Prodmodel](https://github.com/prodmodel/prodmodel) - Build tool for data science pipelines.
* [the-elements-of-statistical-learning](https://github.com/maitbayev/the-elements-of-statistical-learning) - This repository contains Jupyter notebooks implementing the algorithms found in the book and summary of the textbook.
* [Hyperparameter-Optimization-of-Machine-Learning-Algorithms](https://github.com/LiYangHart/Hyperparameter-Optimization-of-Machine-Learning-Algorithms) - Code for hyperparameter tuning/optimization of machine learning and deep learning algorithms.
* [Heart_Disease-Prediction](https://github.com/ShivamChoudhary17/Heart_Disease) - Given clinical parameters about a patient, can we predict whether or not they have heart disease?
* [Flight Fare Prediction](https://github.com/ShivamChoudhary17/Flight_Fare_Prediction) - This basically to gauge the understanding of Machine Learning Workflow and Regression technique in specific.
* [Keras Tuner](https://github.com/keras-team/keras-tuner) - An easy-to-use, scalable hyperparameter optimization framework that solves the pain points of hyperparameter search.



<a name="python-neural-networks"></a>
#### Neural Networks

* [nn_builder](https://github.com/p-christ/nn_builder) - nn_builder is a python package that lets you build neural networks in 1 line
* [NeuralTalk](https://github.com/karpathy/neuraltalk) - NeuralTalk is a Python+numpy project for learning Multimodal Recurrent Neural Networks that describe images with sentences.
* [Neuron](https://github.com/molcik/python-neuron) - Neuron is simple class for time series predictions. It's utilize LNU (Linear Neural Unit), QNU (Quadratic Neural Unit), RBF (Radial Basis Function), MLP (Multi Layer Perceptron), MLP-ELM (Multi Layer Perceptron - Extreme Learning Machine) neural networks learned with Gradient descent or LeLevenberg–Marquardt algorithm.

* [NeuralTalk](https://github.com/karpathy/neuraltalk2) - NeuralTalk is a Python+numpy project for learning Multimodal Recurrent Neural Networks that describe images with sentences. **[Deprecated]**
* [Neuron](https://github.com/molcik/python-neuron) - Neuron is simple class for time series predictions. It's utilize LNU (Linear Neural Unit), QNU (Quadratic Neural Unit), RBF (Radial Basis Function), MLP (Multi Layer Perceptron), MLP-ELM (Multi Layer Perceptron - Extreme Learning Machine) neural networks learned with Gradient descent or LeLevenberg–Marquardt algorithm. **[Deprecated]**
* [Data Driven Code](https://github.com/atmb4u/data-driven-code) - Very simple implementation of neural networks for dummies in python without using any libraries, with detailed comments.
* [Machine Learning, Data Science and Deep Learning with Python](https://www.manning.com/livevideo/machine-learning-data-science-and-deep-learning-with-python) - LiveVideo course that covers machine learning, Tensorflow, artificial intelligence, and neural networks.
* [TResNet: High Performance GPU-Dedicated Architecture](https://github.com/mrT23/TResNet) - TResNet models were designed and optimized to give the best speed-accuracy tradeoff out there on GPUs.
* [TResNet: Simple and powerful neural network library for python](https://github.com/zueve/neurolab) - Variety of supported types of Artificial Neural Network and learning algorithms.
* [Jina AI](https://jina.ai/) An easier way to build neural search in the cloud. Compatible with Jupyter Notebooks.
* [sequitur](https://github.com/shobrook/sequitur) PyTorch library for creating and training sequence autoencoders in just two lines of code

<a name="python-kaggle-competition-source-code"></a>
#### Kaggle Competition Source Code
* [open-solution-home-credit](https://github.com/neptune-ml/open-solution-home-credit) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Home-Credit-Default-Risk) for [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk).
* [open-solution-googleai-object-detection](https://github.com/neptune-ml/open-solution-googleai-object-detection) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Google-AI-Object-Detection-Challenge) for [Google AI Open Images - Object Detection Track](https://www.kaggle.com/c/google-ai-open-images-object-detection-track).
* [open-solution-salt-identification](https://github.com/neptune-ml/open-solution-salt-identification) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Salt-Detection) for [TGS Salt Identification Challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge).
* [open-solution-ship-detection](https://github.com/neptune-ml/open-solution-ship-detection) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Ships) for [Airbus Ship Detection Challenge](https://www.kaggle.com/c/airbus-ship-detection).
* [open-solution-data-science-bowl-2018](https://github.com/neptune-ml/open-solution-data-science-bowl-2018) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Data-Science-Bowl-2018) for [2018 Data Science Bowl](https://www.kaggle.com/c/data-science-bowl-2018).
* [open-solution-value-prediction](https://github.com/neptune-ml/open-solution-value-prediction) -> source code and [experiments results](https://app.neptune.ml/neptune-ml/Santander-Value-Prediction-Challenge) for [Santander Value Prediction Challenge](https://www.kaggle.com/c/santander-value-prediction-challenge).
* [open-solution-toxic-comments](https://github.com/neptune-ml/open-solution-toxic-comments) -> source code for [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).
* [wiki challenge](https://github.com/hammer/wikichallenge) - An implementation of Dell Zhang's solution to Wikipedia's Participation Challenge on Kaggle.
* [kaggle insults](https://github.com/amueller/kaggle_insults) - Kaggle Submission for "Detecting Insults in Social Commentary".
* [kaggle_acquire-valued-shoppers-challenge](https://github.com/MLWave/kaggle_acquire-valued-shoppers-challenge) - Code for the Kaggle acquire valued shoppers challenge.
* [kaggle-cifar](https://github.com/zygmuntz/kaggle-cifar) - Code for the CIFAR-10 competition at Kaggle, uses cuda-convnet.
* [kaggle-blackbox](https://github.com/zygmuntz/kaggle-blackbox) - Deep learning made easy.
* [kaggle-accelerometer](https://github.com/zygmuntz/kaggle-accelerometer) - Code for Accelerometer Biometric Competition at Kaggle.
* [kaggle-advertised-salaries](https://github.com/zygmuntz/kaggle-advertised-salaries) - Predicting job salaries from ads - a Kaggle competition.
* [kaggle amazon](https://github.com/zygmuntz/kaggle-amazon) - Amazon access control challenge.
* [kaggle-bestbuy_big](https://github.com/zygmuntz/kaggle-bestbuy_big) - Code for the Best Buy competition at Kaggle.
* [kaggle-bestbuy_small](https://github.com/zygmuntz/kaggle-bestbuy_small)
* [Kaggle Dogs vs. Cats](https://github.com/kastnerkyle/kaggle-dogs-vs-cats) - Code for Kaggle Dogs vs. Cats competition.
* [Kaggle Galaxy Challenge](https://github.com/benanne/kaggle-galaxies) - Winning solution for the Galaxy Challenge on Kaggle.
* [Kaggle Gender](https://github.com/zygmuntz/kaggle-gender) - A Kaggle competition: discriminate gender based on handwriting.
* [Kaggle Merck](https://github.com/zygmuntz/kaggle-merck) - Merck challenge at Kaggle.
* [Kaggle Stackoverflow](https://github.com/zygmuntz/kaggle-stackoverflow) - Predicting closed questions on Stack Overflow.
* [kaggle_acquire-valued-shoppers-challenge](https://github.com/MLWave/kaggle_acquire-valued-shoppers-challenge) - Code for the Kaggle acquire valued shoppers challenge.
* [wine-quality](https://github.com/zygmuntz/wine-quality) - Predicting wine quality.

<a name="python-reinforcement-learning"></a>
#### Reinforcement Learning
* [DeepMind Lab](https://github.com/deepmind/lab) - DeepMind Lab is a 3D learning environment based on id Software's Quake III Arena via ioquake3 and other open source software. Its primary purpose is to act as a testbed for research in artificial intelligence, especially deep reinforcement learning.
* [Gym](https://github.com/openai/gym) - OpenAI Gym is a toolkit for developing and comparing reinforcement learning algorithms.
* [Serpent.AI](https://github.com/SerpentAI/SerpentAI) - Serpent.AI is a game agent framework that allows you to turn any video game you own into a sandbox to develop AI and machine learning experiments. For both researchers and hobbyists.
* [ViZDoom](https://github.com/mwydmuch/ViZDoom) - ViZDoom allows developing AI bots that play Doom using only the visual information (the screen buffer). It is primarily intended for research in machine visual learning, and deep reinforcement learning, in particular.
* [Roboschool](https://github.com/openai/roboschool) - Open-source software for robot simulation, integrated with OpenAI Gym.
* [Retro](https://github.com/openai/retro) - Retro Games in Gym
* [SLM Lab](https://github.com/kengz/SLM-Lab) - Modular Deep Reinforcement Learning framework in PyTorch.
* [Coach](https://github.com/NervanaSystems/coach) - Reinforcement Learning Coach by Intel® AI Lab enables easy experimentation with state of the art Reinforcement Learning algorithms
* [garage](https://github.com/rlworkgroup/garage) - A toolkit for reproducible reinforcement learning research
* [metaworld](https://github.com/rlworkgroup/metaworld) - An open source robotics benchmark for meta- and multi-task reinforcement learning
* [acme](https://deepmind.com/research/publications/Acme) - An Open Source Distributed Framework for Reinforcement Learning that makes build and train your agents easily.
* [Spinning Up](https://spinningup.openai.com) - An educational resource designed to let anyone learn to become a skilled practitioner in deep reinforcement learning
* [Maze](https://github.com/enlite-ai/maze) - Application-oriented deep reinforcement learning framework addressing real-world decision problems.
* [RLlib](https://github.com/ray-project/ray) - RLlib is an industry level, highly scalable RL library for tf and torch, based on Ray. It's used by companies like Amazon and Microsoft to solve real-world decision making problems at scale.

<a name="tensorflow"></a>
## TensorFlow

<a name="tensorflow-general-purpose-machine-learning"></a>
#### General-Purpose Machine Learning
* [Golden TensorFlow](https://golden.com/wiki/TensorFlow) - A page of content on TensorFlow, including academic papers and links to related topics.

<a name="github-tutorials" />

#### Tutorials

* [TensorFlow Tutorial 1](https://github.com/pkmital/tensorflow_tutorials) - From the basics to slightly more interesting applications of TensorFlow
* [TensorFlow Tutorial 2](https://github.com/nlintz/TensorFlow-Tutorials) - Introduction to deep learning based on Google's TensorFlow framework. These tutorials are direct ports of Newmu's Theano
* [TensorFlow Tutorial 3](https://github.com/Hvass-Labs/TensorFlow-Tutorials) - These tutorials are intended for beginners in Deep Learning and TensorFlow with well-documented code and YouTube videos.
* [TensorFlow Examples](https://github.com/aymericdamien/TensorFlow-Examples) - TensorFlow tutorials and code examples for beginners
* [Sungjoon's TensorFlow-101](https://github.com/sjchoi86/Tensorflow-101) - TensorFlow tutorials written in Python with Jupyter Notebook
* [Terry Um’s TensorFlow Exercises](https://github.com/terryum/TensorFlow_Exercises) - Re-create the codes from other TensorFlow examples
* [Installing TensorFlow on Raspberry Pi 3](https://github.com/samjabrahams/tensorflow-on-raspberry-pi) - TensorFlow compiled and running properly on the Raspberry Pi
* [Classification on time series](https://github.com/guillaume-chevalier/LSTM-Human-Activity-Recognition) - Recurrent Neural Network classification in TensorFlow with LSTM on cellphone sensor data
* [Getting Started with TensorFlow on Android](https://omid.al/posts/2017-02-20-Tutorial-Build-Your-First-Tensorflow-Android-App.html) - Build your first TensorFlow Android app
* [Predict time series](https://github.com/guillaume-chevalier/seq2seq-signal-prediction) - Learn to use a seq2seq model on simple datasets as an introduction to the vast array of possibilities that this architecture offers
* [Single Image Random Dot Stereograms](https://github.com/Mazecreator/TensorFlow-SIRDS) - SIRDS is a means to present 3D data in a 2D image. It allows for scientific data display of a waterfall type plot with no hidden lines due to perspective.
* [CS20 SI: TensorFlow for DeepLearning Research](http://web.stanford.edu/class/cs20si/syllabus.html) - Stanford Course about Tensorflow from 2017 - [Syllabus](http://web.stanford.edu/class/cs20si/syllabus.html) - [Unofficial Videos](https://youtu.be/g-EvyKpZjmQ?list=PLSPPwKHXGS2110rEaNH7amFGmaD5hsObs)
* [TensorFlow World](https://github.com/astorfi/TensorFlow-World) - Concise and ready-to-use TensorFlow tutorials with detailed documentation are provided.
* [Effective Tensorflow](https://github.com/vahidk/EffectiveTensorflow) - TensorFlow howtos and best practices. Covers the basics as well as advanced topics.
* [TensorLayer](http://tensorlayer.readthedocs.io/en/latest/user/tutorial.html) - Modular implementation for TensorFlow's official tutorials. ([CN](https://tensorlayercn.readthedocs.io/zh/latest/user/tutorial.html)).
* [Understanding The Tensorflow Estimator API](https://www.lighttag.io/blog/tensorflow-estimator-api/) A conceptual overview of the Estimator API, when you'd use it and why. 
* [Convolutional Neural Networks in TensorFlow](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow) - Convolutional Neural Networks in Tensorflow, offered by Coursera

<a name="github-projects" />

#### Models/Projects

* [Tensorflow-Project-Template](https://github.com/Mrgemy95/Tensorflow-Project-Template) - A simple and well-designed template for your tensorflow project.
* [Domain Transfer Network](https://github.com/yunjey/dtn-tensorflow) - Implementation of Unsupervised Cross-Domain Image Generation
* [Show, Attend and Tell](https://github.com/yunjey/show_attend_and_tell) - Attention Based Image Caption Generator
* [Neural Style](https://github.com/cysmith/neural-style-tf) Implementation of Neural Style
* [SRGAN](https://github.com/tensorlayer/srgan) - Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network
* [Pretty Tensor](https://github.com/google/prettytensor) - Pretty Tensor provides a high level builder API
* [Neural Style](https://github.com/anishathalye/neural-style) - An implementation of neural style
* [AlexNet3D](https://github.com/denti/AlexNet3D) - An implementations of AlexNet3D. Simple AlexNet model but with 3D convolutional layers (conv3d).
* [TensorFlow White Paper Notes](https://github.com/samjabrahams/tensorflow-white-paper-notes) - Annotated notes and summaries of the TensorFlow white paper, along with SVG figures and links to documentation
* [NeuralArt](https://github.com/ckmarkoh/neuralart_tensorflow) - Implementation of A Neural Algorithm of Artistic Style
* [Generative Handwriting Demo using TensorFlow](https://github.com/hardmaru/write-rnn-tensorflow) - An attempt to implement the random handwriting generation portion of Alex Graves' paper
* [Neural Turing Machine in TensorFlow](https://github.com/carpedm20/NTM-tensorflow) - implementation of Neural Turing Machine
* [GoogleNet Convolutional Neural Network Groups Movie Scenes By Setting](https://github.com/agermanidis/thingscoop) - Search, filter, and describe videos based on objects, places, and other things that appear in them
* [Neural machine translation between the writings of Shakespeare and modern English using TensorFlow](https://github.com/tokestermw/tensorflow-shakespeare) - This performs a monolingual translation, going from modern English to Shakespeare and vice-versa.
* [Chatbot](https://github.com/Conchylicultor/DeepQA) - Implementation of ["A neural conversational model"](http://arxiv.org/abs/1506.05869)
* [Seq2seq-Chatbot](https://github.com/tensorlayer/seq2seq-chatbot) - Chatbot in 200 lines of code
* [DCGAN](https://github.com/tensorlayer/dcgan) - Deep Convolutional Generative Adversarial Networks
* [GAN-CLS](https://github.com/zsdonghao/text-to-image) -Generative Adversarial Text to Image Synthesis
* [im2im](https://github.com/zsdonghao/Unsup-Im2Im) - Unsupervised Image to Image Translation with Generative Adversarial Networks
* [Improved CycleGAN](https://github.com/luoxier/CycleGAN_Tensorlayer) - Unpaired Image to Image Translation
* [DAGAN](https://github.com/nebulaV/DAGAN) - Fast Compressed Sensing MRI Reconstruction
* [Colornet - Neural Network to colorize grayscale images](https://github.com/pavelgonchar/colornet) - Neural Network to colorize grayscale images
* [Neural Caption Generator](https://github.com/jazzsaxmafia/show_attend_and_tell.tensorflow) - Implementation of ["Show and Tell"](http://arxiv.org/abs/1411.4555)
* [Neural Caption Generator with Attention](https://github.com/jazzsaxmafia/show_attend_and_tell.tensorflow) - Implementation of ["Show, Attend and Tell"](http://arxiv.org/abs/1502.03044)
* [Weakly_detector](https://github.com/jazzsaxmafia/Weakly_detector) - Implementation of ["Learning Deep Features for Discriminative Localization"](http://cnnlocalization.csail.mit.edu/)
* [Dynamic Capacity Networks](https://github.com/jazzsaxmafia/dcn.tf) - Implementation of ["Dynamic Capacity Networks"](http://arxiv.org/abs/1511.07838)
* [HMM in TensorFlow](https://github.com/dwiel/tensorflow_hmm) - Implementation of viterbi and forward/backward algorithms for HMM
* [DeepOSM](https://github.com/trailbehind/DeepOSM) - Train TensorFlow neural nets with OpenStreetMap features and satellite imagery.
* [DQN-tensorflow](https://github.com/devsisters/DQN-tensorflow) - TensorFlow implementation of DeepMind's 'Human-Level Control through Deep Reinforcement Learning' with OpenAI Gym by Devsisters.com
* [Policy Gradient](https://github.com/zsdonghao/tensorlayer/blob/master/example/tutorial_atari_pong.py) - For Playing Atari Ping Pong
* [Deep Q-Network](https://github.com/zsdonghao/tensorlayer/blob/master/example/tutorial_frozenlake_dqn.py) - For Playing Frozen Lake Game
* [AC](https://github.com/zsdonghao/tensorlayer/blob/master/example/tutorial_cartpole_ac.py) - Actor Critic for Playing Discrete Action space Game (Cartpole)
* [A3C](https://github.com/zsdonghao/tensorlayer/blob/master/example/tutorial_bipedalwalker_a3c_continuous_action.py) - Asynchronous Advantage Actor Critic (A3C) for Continuous Action Space (Bipedal Walker)
* [DAGGER](https://github.com/zsdonghao/Imitation-Learning-Dagger-Torcs) - For Playing [Gym Torcs](https://github.com/ugo-nama-kun/gym_torcs)
* [TRPO](https://github.com/jjkke88/RL_toolbox) - For Continuous and Discrete Action Space by
* [Highway Network](https://github.com/fomorians/highway-cnn) - TensorFlow implementation of ["Training Very Deep Networks"](http://arxiv.org/abs/1507.06228) with a [blog post](https://medium.com/jim-fleming/highway-networks-with-tensorflow-1e6dfa667daa#.ndicn1i27)
* [Hierarchical Attention Networks](https://github.com/tqtg/hierarchical-attention-networks) - TensorFlow implementation of ["Hierarchical Attention Networks for Document Classification"](https://www.cs.cmu.edu/~hovy/papers/16HLT-hierarchical-attention-networks.pdf)
* [Sentence Classification with CNN](https://github.com/dennybritz/cnn-text-classification-tf) - TensorFlow implementation of ["Convolutional Neural Networks for Sentence Classification"](http://arxiv.org/abs/1408.5882) with a [blog post](http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/)
* [End-To-End Memory Networks](https://github.com/domluna/memn2n) - Implementation of [End-To-End Memory Networks](http://arxiv.org/abs/1503.08895)
* [Character-Aware Neural Language Models](https://github.com/carpedm20/lstm-char-cnn-tensorflow) - TensorFlow implementation of [Character-Aware Neural Language Models](http://arxiv.org/abs/1508.06615)
* [YOLO TensorFlow ++](https://github.com/thtrieu/yolotf) - TensorFlow implementation of 'YOLO: Real-Time Object Detection', with training and an actual support for real-time running on mobile devices.
* [Wavenet](https://github.com/ibab/tensorflow-wavenet) - This is a TensorFlow implementation of the [WaveNet generative neural network architecture](https://deepmind.com/blog/wavenet-generative-model-raw-audio/) for audio generation.
* [Mnemonic Descent Method](https://github.com/trigeorgis/mdm) - Tensorflow implementation of ["Mnemonic Descent Method: A recurrent process applied for end-to-end face alignment"](http://ibug.doc.ic.ac.uk/media/uploads/documents/trigeorgis2016mnemonic.pdf)
* [CNN visualization using Tensorflow](https://github.com/InFoCusp/tf_cnnvis) - Tensorflow implementation of ["Visualizing and Understanding Convolutional Networks"](https://www.cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf)
* [VGAN Tensorflow](https://github.com/Singularity42/VGAN-Tensorflow) - Tensorflow implementation for MIT ["Generating Videos with Scene Dynamics"](http://carlvondrick.com/tinyvideo/) by Vondrick et al.
* [3D Convolutional Neural Networks in TensorFlow](https://github.com/astorfi/3D-convolutional-speaker-recognition) - Implementation of ["3D Convolutional Neural Networks for Speaker Verification application"](https://arxiv.org/abs/1705.09422) in TensorFlow by Torfi et al.
* [U-Net](https://github.com/zsdonghao/u-net-brain-tumor) - For Brain Tumor Segmentation
* [Spatial Transformer Networks](https://github.com/zsdonghao/Spatial-Transformer-Nets) - Learn the Transformation Function 
* [Lip Reading - Cross Audio-Visual Recognition using 3D Architectures in TensorFlow](https://github.com/astorfi/lip-reading-deeplearning) - TensorFlow Implementation of ["Cross Audio-Visual Recognition in the Wild Using Deep Learning"](https://arxiv.org/abs/1706.05739) by Torfi et al.
* [Attentive Object Tracking](https://github.com/akosiorek/hart) - Implementation of ["Hierarchical Attentive Recurrent Tracking"](https://arxiv.org/abs/1706.09262)
* [Holographic Embeddings for Graph Completion and Link Prediction](https://github.com/laxatives/TensorFlow-TransX) - Implementation of [Holographic Embeddings of Knowledge Graphs](http://arxiv.org/abs/1510.04935)
* [Unsupervised Object Counting](https://github.com/akosiorek/attend_infer_repeat) - Implementation of ["Attend, Infer, Repeat"](https://papers.nips.cc/paper/6230-attend-infer-repeat-fast-scene-understanding-with-generative-models)
* [Tensorflow FastText](https://github.com/apcode/tensorflow_fasttext) - A simple embedding based text classifier inspired by Facebook's fastText.
* [MusicGenreClassification](https://github.com/mlachmish/MusicGenreClassification) - Classify music genre from a 10 second sound stream using a Neural Network.
* [Kubeflow](https://github.com/kubeflow/kubeflow) - Framework for easily using Tensorflow with Kubernetes.
* [TensorNets](https://github.com/taehoonlee/tensornets) - 40+ Popular Computer Vision Models With Pre-trained Weights.
* [Ladder Network](https://github.com/divamgupta/ladder_network_keras) - Implementation of Ladder Network for Semi-Supervised Learning in Keras and Tensorflow
* [TF-Unet](https://github.com/juniorxsound/TF-Unet) - General purpose U-Network implemented in Keras for image segmentation
* [Sarus TF2 Models](https://github.com/sarus-tech/tf2-published-models) - A long list of recent generative models implemented in clean, easy to reuse, Tensorflow 2 code (Plain Autoencoder, VAE, VQ-VAE, PixelCNN, Gated PixelCNN, PixelCNN++, PixelSNAIL, Conditional Neural Processes).
* [Model Maker](https://www.tensorflow.org/lite/guide/model_maker) - A transfer learning library that simplifies the process of training, evaluation and deployment for TensorFlow Lite models (support: Image Classification, Object Detection, Text Classification, BERT Question Answer, Audio Classification, Recommendation etc.; [API reference](https://www.tensorflow.org/lite/api_docs/python/tflite_model_maker)).



<a name="github-powered-by" />

#### Powered by TensorFlow

* [YOLO TensorFlow](https://github.com/gliese581gg/YOLO_tensorflow) - Implementation of 'YOLO : Real-Time Object Detection'
* [android-yolo](https://github.com/natanielruiz/android-yolo) - Real-time object detection on Android using the YOLO network, powered by TensorFlow.
* [Magenta](https://github.com/tensorflow/magenta) - Research project to advance the state of the art in machine intelligence for music and art generation


<a name="libraries" />

#### Libraries

* [TensorFlow Estimators](https://www.tensorflow.org/guide/estimators) - high-level TensorFlow API that greatly simplifies machine learning programming (originally [tensorflow/skflow](https://github.com/tensorflow/skflow))
* [R Interface to TensorFlow](https://tensorflow.rstudio.com/) - R interface to TensorFlow APIs, including Estimators, Keras, Datasets, etc.
* [Lattice](https://github.com/tensorflow/lattice) - Implementation of Monotonic Calibrated Interpolated Look-Up Tables in TensorFlow
* [tensorflow.rb](https://github.com/somaticio/tensorflow.rb) - TensorFlow native interface for ruby using SWIG
* [tflearn](https://github.com/tflearn/tflearn) - Deep learning library featuring a higher-level API
* [TensorLayer](https://github.com/tensorlayer/tensorlayer) - Deep learning and reinforcement learning library for researchers and engineers
* [TensorFlow-Slim](https://github.com/tensorflow/models/tree/master/inception/inception/slim) - High-level library for defining models
* [TensorFrames](https://github.com/tjhunter/tensorframes) - TensorFlow binding for Apache Spark
* [TensorForce](https://github.com/reinforceio/tensorforce) - TensorForce: A TensorFlow library for applied reinforcement learning
* [TensorFlowOnSpark](https://github.com/yahoo/TensorFlowOnSpark) - initiative from Yahoo! to enable distributed TensorFlow with Apache Spark.
* [caffe-tensorflow](https://github.com/ethereon/caffe-tensorflow) - Convert Caffe models to TensorFlow format
* [keras](http://keras.io) - Minimal, modular deep learning library for TensorFlow and Theano
* [SyntaxNet: Neural Models of Syntax](https://github.com/tensorflow/models/tree/master/syntaxnet) - A TensorFlow implementation of the models described in [Globally Normalized Transition-Based Neural Networks, Andor et al. (2016)](http://arxiv.org/pdf/1603.06042.pdf)
* [keras-js](https://github.com/transcranial/keras-js) - Run Keras models (tensorflow backend) in the browser, with GPU support
* [NNFlow](https://github.com/welschma/NNFlow) - Simple framework allowing to read-in ROOT NTuples by converting them to a Numpy array and then use them in Google Tensorflow.
* [Sonnet](https://github.com/deepmind/sonnet) - Sonnet is DeepMind's library built on top of TensorFlow for building complex neural networks.
* [tensorpack](https://github.com/ppwwyyxx/tensorpack) - Neural Network Toolbox on TensorFlow focusing on training speed and on large datasets.
* [tf-encrypted](https://github.com/mortendahl/tf-encrypted) - Layer on top of TensorFlow for doing machine learning on encrypted data
* [pytorch2keras](https://github.com/nerox8664/pytorch2keras) - Convert PyTorch models to Keras (with TensorFlow backend) format
* [gluon2keras](https://github.com/nerox8664/gluon2keras) - Convert Gluon models to Keras (with TensorFlow backend) format
* [TensorIO](https://doc-ai.github.io/tensorio/) - Lightweight, cross-platform library for deploying TensorFlow Lite models to mobile devices. 
* [StellarGraph](https://github.com/stellargraph/stellargraph) - Machine Learning on Graphs, a Python library for machine learning on graph-structured (network-structured) data.
* [DeepBay](https://github.com/ElPapi42/DeepBay) - High-Level Keras Complement for implement common architectures stacks, served as easy to use plug-n-play modules

<a name="tools-utils" />

#### Tools/Utilities

* [Guild AI](https://guild.ai) - Task runner and package manager for TensorFlow
* [ML Workspace](https://github.com/ml-tooling/ml-workspace) - All-in-one web IDE for machine learning and data science. Combines Tensorflow, Jupyter, VS Code, Tensorboard, and many other tools/libraries into one Docker image.


<a name="tools"></a>
## Tools

<a name="tools-misc"></a>
#### Misc

* [CatalyzeX](https://chrome.google.com/webstore/detail/code-finder-for-research/aikkeehnlfpamidigaffhfmgbkdeheil) - Browser extension ([Chrome](https://chrome.google.com/webstore/detail/code-finder-for-research/aikkeehnlfpamidigaffhfmgbkdeheil) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/code-finder-catalyzex/)) that automatically finds and shows code implementations for machine learning papers anywhere: Google, Twitter, Arxiv, Scholar, etc.
* [ML Workspace](https://github.com/ml-tooling/ml-workspace) - All-in-one web-based IDE for machine learning and data science. The workspace is deployed as a docker container and is preloaded with a variety of popular data science libraries (e.g., Tensorflow, PyTorch) and dev tools (e.g., Jupyter, VS Code).
* [Notebooks](https://github.com/rlan/notebooks) - A starter kit for Jupyter notebooks and machine learning. Companion docker images consist of all combinations of python versions, machine learning frameworks (Keras, PyTorch and Tensorflow) and CPU/CUDA versions.
* [DVC](https://github.com/iterative/dvc) - Data Science Version Control is an open-source version control system for machine learning projects with pipelines support. It makes ML projects reproducible and shareable.
* [DVClive](https://github.com/iterative/dvclive) - Python library for experiment metrics logging into simply formatted local files.
* [Kedro](https://github.com/quantumblacklabs/kedro/) - Kedro is a data and development workflow framework that implements best practices for data pipelines with an eye towards productionizing machine learning models.
* [guild.ai](https://guild.ai/) - Tool to log, analyze, compare and "optimize" experiments. It's cross-platform and framework independent, and provided integrated visualizers such as tensorboard.
* [Sacred](https://github.com/IDSIA/sacred) - Python tool to help  you configure, organize, log and reproduce experiments. Like a notebook lab in the context of Chemistry/Biology. The community has built multiple add-ons leveraging the proposed standard.
* [MLFlow](https://mlflow.org/) - platform to manage the ML lifecycle, including experimentation, reproducibility and deployment. Framework and language agnostic, take a look at all the built-in integrations.
* More tools to improve the ML lifecycle: [Catalyst](https://github.com/catalyst-team/catalyst), [PachydermIO](https://github.com/pachyderm/pachyderm).
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A tool that allows the conversion of ML models into native code (Java, C, Python, Go, JavaScript, Visual Basic, C#, R, PowerShell, PHP, Dart) with zero dependencies.
* [CML](https://github.com/iterative/cml) - A library for doing continuous integration with ML projects. Use GitHub Actions & GitLab CI to train and evaluate models in production like environments and automatically generate visual reports with metrics and graphs in pull/merge requests. Framework & language agnostic.
* [Pythonizr](https://github.com/akashp1712/pythonizr) - An online tool to generate boilerplate machine learning code that uses scikit-learn.
* [Flyte](https://github.com/flyteorg/flyte) - Flyte makes it easy to create concurrent, scalable, and maintainable workflows for machine learning and data processing.

## Credits

* Some of the python libraries were cut-and-pasted from [vinta](https://github.com/vinta/awesome-python)
