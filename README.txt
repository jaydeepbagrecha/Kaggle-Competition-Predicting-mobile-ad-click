@@ -1 +1,30 @@
Requirements:
=============
1. Install pypy compiler.
2. Install numpy, scipy (python).

Steps to do before Running FTRL_impl:
=====================================
1. Enter the path of test file and train file in ftrl.py file.
2. Enter the path for the output submisson files.
3. In the ftrl.py file file pass the value of alpha, beta, L1, L2 and epoch.

Flag meanings:
alpha  : step size (alpha).
L1     : L1 regularizer.
L2     : L2 regularizer.
beta   : learning rate decay.
epoch  : epoch size.

Steps to Run:
=============
1. cd to FTRL_impl dir
cd path/to/FTRL_impl
2. Run ftrl.py to do feature engineering and creating the model, cross validation and creation of kaggle submission file.
pypy ftrl.py 

Note:
=====
For default run just copy the test and train file into the  dir and follow "Steps to Run" commands one by one.



