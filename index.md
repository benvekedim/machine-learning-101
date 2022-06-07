
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
![image](/img/customerDF.png)

<p> İşlenmemiş veri için Age ve İncome saçılım grafiğini çizelim.</p>

```
plt.figure(figsize = (12, 9))
plt.scatter(df.iloc[:, 2], df.iloc[:, 4])
plt.xlabel('Age')
plt.ylabel('Income')
plt.title('Visualization of raw data')

```
![image](/img/customer-RAW.png)

<p> Müşteri verisinde StandardScaler ve KMeans algoritmalarını uygulayalım. </p>

![image](/img/customer-KMEANS.png)

<p>Müşteri verisinde PCA ve KMeans algoritmalarını uygulayalım. </p>

![image](/img/customer-PCA.png)

<p>Okuduğunuz için teşekkürler </p>


