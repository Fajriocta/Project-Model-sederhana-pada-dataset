# Project-Model-sederhana-pada-dataset
pada respository ini, saya akan melakukan pengolahan data dan memprediksikan harga (_charges_)

```sh
https://www.kaggle.com/datasets/mirichoi0218/insurance
```

# content of dataset
beberapa variabel yang tersedia pada dataset

- age: age of primary beneficiary
- sex: insurance contractor gender, female, male
- bmi: Body mass index
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
- charges: Individual medical costs billed by health insurance

# step of project

- eaning data = membersihkan data dari missing value dan duplikasi data

- sualization data = melakukan analisa dari dataset

- ature Engineering = proses pengolahan data untuk memilih variabel yang cocok sebelum memasuki ML, pada dataset ini, dilakukan binary encoder dan on hot encoding

- chine Learning = pada dataset ini bertujuan untuk menganalisa dan memprediksi harga insurance dengan menggunakan permodelan Lasso Regression

