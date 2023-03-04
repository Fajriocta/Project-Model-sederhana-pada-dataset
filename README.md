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

- Cleansing data = membersihkan data dari missing value dan duplikasi data

- Exploratory data analysis = melakukan analisa dari dataset

- Feature Engineering = proses pengolahan data untuk memilih variabel yang cocok sebelum memasuki Machine Learning, pada dataset ini, dilakukan binary encoder dan on hot encoding

- Machine Learning = pada dataset ini bertujuan untuk menganalisa dan memprediksi harga insurance dengan menggunakan permodelan Lasso Regression

