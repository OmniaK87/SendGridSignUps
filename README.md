Initial README.  

This will be a repo for all of the information required to run a model of signup issues on a dataset



Install XGBoost on Mac OSX:

git clone --recursive https://github.com/dmlc/xgboost
cd xgboost
cp make/minimum.mk ./config.mk
make -j4
cd python-package
sudo python setup.py install