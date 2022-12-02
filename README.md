# LogiQA2.0_Chinese
The Chinese version of LogiQA2.0
# LogiQA2.0
Logiqa2.0 dataset - logical reasoning in MRC and NLI tasks

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

> This repository contains the datasets and baseline codes for our paper [LogiQA2.0 - An Improved Dataset for Logic Reasoning in Question Answering and Textual Inference Tasks]()
## About
This is the version 2 of the LogiQA dataset, first released as a multi-choice reading comprehension dataset by our previous paper [LogiQA: A Challenge  Dataset for Machine Reading Comprehension with Logical Reasoning](https://arxiv.org/abs/2007.08124). 

The dataset is collected from the [Chinese Civil Service Entrance Examination](chinagwy.org). The dataset is both in Chinese and English (by translation). you can download the version 1 of the LogiQA dataset from [here](https://github.com/lgw863/logiqa-dataset).

To construct LogiQA2.0 dataset, we:
* collect more newly released exam questions and practice questions. There are about 20 provinces in China that hold the exam annually. The exam materials are publicly available on the Internet after the exams. Besides, practice questions are provided by various sources.
* hire professional translators to re-translate the dataset from Chinese to English; verify the labels and annotations with human experts. This program is conducted by [Speechocean](en.speechocean.com), a data annotation service provider. The project is accomplished with the help of Microsoft Research Asia.
* introduce a new NLI task to the dataset. The NLI version of the dataset is converted from the MRC version of the dataset, following previous work such as [Transforming Question Answering Datasets into Natural Language Inference Datasets](https://arxiv.org/abs/1809.02922).
