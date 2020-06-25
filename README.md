# libsvm_avgsn
Assessed the average sentisivity of cross validation in multi-classfication

Libsvm_avgsn is based on libsvm-3.22, which modified the accuracy to average sentivity of cross validation in multi-classfication.

=========================

Usage: svm-train -v 5 [options] test.scale


1.Download Libsvm_avgsn at and prepare your data in scale format.

2. Type

    cd Libsvm_avgsn && make clean && make

3. To get the result of cross validation.

    ./svm-train -v 5 [options] test.scale
