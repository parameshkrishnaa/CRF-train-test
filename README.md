# CRF++

## Download and Install
### Download CRF
Download CRF from <a href="https://drive.google.com/drive/u/0/folders/0B4y35FiV1wh7fngteFhHQUN2Y1B5eUJBNHZUemJYQV9VWlBUb3JlX0xBdWVZTWtSbVBneU0?resourcekey=0-NW5cPRv1Xr2-Vfo_xlDTLQ" target="_blank">here</a

### Install
```
./configure ​
make​
su​
make install
```

### Test CRF installation
crf_test --version

### Installation possible error and fix
**if you get an error as below if libcrfpp.so.0 not found after CRF installation than execute the below command**
````
ln -s /usr/local/lib/libcrfpp.so.0 /usr/lib/libcrfpp.so.0
````

### To train
crf_learn <template_file> <train_file> <model>

### To predict
crf_test -m <model_file> <test_file>

