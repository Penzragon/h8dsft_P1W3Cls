# Hacktiv8 Phase 1: Graded Challenge 4

Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada konsep Clustering.

---

By [Rifky Aliffa](https://github.com/Penzragon)

![Image](https://www.dbs.com.sg/iwov-resources/media/images/nav/credit-card-strategies/credit-card-strategies-1404x630.jpg)

## Dataset

Pada project kali ini dataset yang digunakan adalah data dari customers kartu kredit sebuah bank. Dataset ini berisi 8950 baris dengan 18 kolom yang di antaranya adalah kolom CUSTID, BALANCE, BALANCEFREQUENCY, PURCHASES, ONEOFFPURCHASES, dan masih banyak lagi. Dataset dapat dilihat di [Kaggle](https://www.kaggle.com/arjunbhasin2013/ccdata).

Keterangan kolom pada dataset ini adalah:

| Feature                        | Description                                                                                                                 |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| CUSTID                         | Identification of Credit Card holder (Categorical)                                                                          |
| BALANCE                        | Balance amount left in their account to make purchases                                                                      |
| BALANCEFREQUENCY               | How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)           |
| PURCHASES                      | Amount of purchases made from account                                                                                       |
| ONEOFFPURCHASES                | Maximum purchase amount done in one-go                                                                                      |
| INSTALLMENTSPURCHASES          | Amount of purchase done in installment                                                                                      |
| CASHADVANCE                    | Cash in advance given by the user                                                                                           |
| PURCHASESFREQUENCY             | How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased) |
| ONEOFFPURCHASESFREQUENCY       | How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)                   |
| PURCHASESINSTALLMENTSFREQUENCY | How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)                      |
| CASHADVANCEFREQUENCY           | How frequently the cash in advance being paid                                                                               |
| CASHADVANCETRX                 | Number of Transactions made with "Cash in Advanced"                                                                         |
| PURCHASESTRX                   | Number of purchase transactions made                                                                                        |
| CREDITLIMIT                    | Limit of Credit Card for user                                                                                               |
| PAYMENTS                       | Amount of Payment done by user                                                                                              |
| MINIMUM_PAYMENTS               | Minimum amount of payments made by user                                                                                     |
| PRCFULLPAYMENT                 | Percent of full payment paid by user                                                                                        |
| TENURE                         | Tenure of credit card service for user                                                                                      |

## Objectives

**Graded Challenge 4** ini dibuat guna mengevaluasi konsep Clustering sebagai berikut:

- Mampu memahami konsep Clustering dengan menggunakan Scikit-Learn.
- Mampu mempersiapkan data untuk digunakan dalam Clustering.
- Mampu mengimplementasikan Clustering pada data yang diberikan.
