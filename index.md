
## Customer Segmentation

Yazar: Mustafa Eroğlu

Tarih: 7 Haziran 2022

<p>
Bu projede sahte müşteri veri setiyle çalıştım. StandardScaler, KMeans ve PCA kullanarak analiz yaptım
</p>

<p> Verileri keşfedelim.</p>

```
df.head()
```
![image](https://github.com/benvekedim/machine-learning-101/blob/gh-pages/img/customerDF.png?raw=true)

<p> İşlenmemiş veri için Age ve İncome saçılım grafiğini çizelim.</p>

```
plt.figure(figsize = (12, 9))
plt.scatter(df.iloc[:, 2], df.iloc[:, 4])
plt.xlabel('Age')
plt.ylabel('Income')
plt.title('Visualization of raw data')

```
![image](https://github.com/benvekedim/machine-learning-101/blob/gh-pages/img/customer-RAW.png?raw=true)

<p> Müşteri verisinde StandardScaler ve KMeans algoritmalarını uygulayalım. </p>

![image](https://github.com/benvekedim/machine-learning-101/blob/gh-pages/img/customer-KMEANS.png?raw=true)

<p>Müşteri verisinde PCA ve KMeans algoritmalarını uygulayalım. </p>

![image](https://github.com/benvekedim/machine-learning-101/blob/gh-pages/img/customer-PCA.png?raw=true)

<p>Okuduğunuz için teşekkürler </p>
