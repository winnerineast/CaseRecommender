Case Recommender - A Recommender Framework for Python
======================================================

Case Recommender is a Python implementation of a number of popular recommendation algorithms for both implicit and explicit feedback.  The framework aims to provide a rich set of components from which you can construct a customized recommender system from a set of algorithms. Case Recommender has different types of item recommendation and rating prediction approaches, and different metrics validation and evaluation.

Algorithms
^^^^^^^^^^^^

Item Recommendation:

- BPRMF

- ItemKNN

- Item Attribute KNN

- UserKNN

- User Attribute KNN

- Most Popular

- Random

Rating Prediction:

- Matrix Factorization (with and without baseline)

- SVD

- SVD++

- ItemKNN

- Item Attribute KNN

- UserKNN

- User Attribute KNN

- Item NSVD1 (with and without Batch)

- User NSVD1 (with and without Batch)


Evaluation and Validation Metrics
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- All-but-one Protocol

- Cross-fold- Validation

- Item Recommendation: Precision, Recall, NDCG and Map

- Rating Prediction: MAE and RMSE

- Statistical Analysis (T-test and Wilcoxon)

Requirements
^^^^^^^^^^^^^

- Python >= 3.5
- scipy
- numpy
- pandas
- scikit-learn

For Linux, Windows and MAC use:

    $ pip install requirements

For Windows libraries help use:

    http://www.lfd.uci.edu/~gohlke/pythonlibs/#matplotlib

Quick start
^^^^^^^^^^^^

Case Recommender can be installed using pip:

    $ pip install caserecommender

If you want to run the latest version of the code, you can install from git:

    $ pip install -U git+git://github.com/ArthurFortes/CaseRecommender.git

More Details
^^^^^^^^^^^^^

    `https://github.com/ArthurFortes/CaseRecommender <https://github.com/ArthurFortes/CaseRecommender>`_


Developed By
^^^^^^^^^^^^^

Arthur Fortes da Costa

University of São Paulo - ICMC (USP)

fortes.arthur@gmail.com

Reference
^^^^^^^^^^

da Costa Fortes, A. and Manzato, M. G. Case recommender: A recommender framework. In Proceedings of the
22Nd Brazilian Symposium on Multimedia and the Web. Webmedia ’16. SBC, pp. 99–102, 2016.

BibTex (.bib)

    @inproceedings{daCostaCase:16,
    author = {da Costa Fortes, Arthur and Manzato, Marcelo Garcia},
    title = {Case Recommender: A Recommender Framework},
    booktitle = {Proceedings of the 22Nd Brazilian Symposium on Multimedia and the Web},
    series = {Webmedia '16},
    year = {2016},
    pages = {99--102},
    numpages = {4},
    publisher = {SBC}
    }

License (MIT)
^^^^^^^^^^^^^^

    © 2018. Case Recommender All Rights Reserved

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
    documentation files (the "Software"), to deal in the Software without restriction, including without limitation the
    rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
