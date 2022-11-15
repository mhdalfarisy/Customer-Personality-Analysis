# Segmentation Customer Supermarket


- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Analytical Approach](#analytical-approach)
- [Definisi Kolom](#definisi-kolom)
- [Data Analyst dan Clustering](#data-analyst-dan-clustering) 
- [Kesimpulan](#kesimpulan)
- [Saran](#saran)
- [Others Project](#others-project)
  

### **Problem Statement**
Analisis Kepribadian Pelanggan adalah analisis terperinci tentang pelanggan ideal perusahaan. Ini membantu bisnis untuk lebih memahami pelanggannya dan memudahkan mereka untuk memodifikasi produk sesuai dengan kebutuhan, perilaku, dan perhatian khusus dari berbagai jenis pelanggan.

Analisis kepribadian pelanggan membantu bisnis untuk memodifikasi produknya berdasarkan target pelanggan dari berbagai jenis segmen pelanggan. Misalnya, alih-alih mengeluarkan uang untuk memasarkan produk baru ke setiap pelanggan di database perusahaan, perusahaan dapat menganalisis segmen pelanggan mana yang paling mungkin membeli produk dan kemudian memasarkan produk hanya pada segmen tertentu.

### **Objectives**
Segmentasi berbasis nilai mengevaluasi kelompok pelanggan dalam hal pendapatan yang mereka hasilkan dan biaya untuk membangun dan memelihara hubungan dengan mereka. Ini juga membantu perusahaan menentukan segmen mana yang paling dan paling tidak menguntungkan sehingga mereka dapat menyesuaikan anggaran pemasaran mereka.

Segmentasi berbasis nilai membantu mengidentifikasi pelanggan yang Memerlukan lebih banyak perhatian dari tim penjualan dan layanan.
  
### **Analytical Approach**
Dalam analisa ini akan dilakukan 2 tahapan :
    - Melakukan EDA untuk melihat perkembangan bisnis perusahaan
    - Melakukan Clustering untuk menjawab permasalahan yang dibutuhkan perusahaan

### **Definisi Kolom**
#

| **Nama Kolom** | **Keterangan Kolom** |
| --- | --- |
|**PEOPLE**||
|ID| Customer's unique identifier|
|Year_Birth| Customer's birth year|
|Education| Customer's education level|
|Marital_Status| Customer's marital status|
|Income| Customer's yearly household income|
|Kidhome| Number of children in customer's household|
|Teenhome| Number of teenagers in customer's household|
|Dt_Customer| Date of customer's enrollment with the company|
|Recency| Number of days since customer's last purchase|
|Complain| 1 if customer complained in the last 2 years, 0 otherwise|
|**PRODUCT**||
|MntWines| Amount spent on wine in last 2 years|
|MntFruits| Amount spent on fruits in last 2 years|
|MntMeatProducts| Amount spent on meat in last 2 years|
|MntFishProducts| Amount spent on fish in last 2 years|
|MntSweetProducts| Amount spent on sweets in last 2 years|
|MntGoldProds| Amount spent on gold in last 2 years|
|**PROMOTION**||
|NumDealsPurchases| Number of purchases made with a discount
|AcceptedCmp1| 1 if customer accepted the offer in the 1st campaign, 0 otherwise|
|AcceptedCmp2| 1 if customer accepted the offer in the 2nd campaign, 0 otherwise|
|AcceptedCmp3| 1 if customer accepted the offer in the 3rd campaign, 0 otherwise|
|AcceptedCmp4| 1 if customer accepted the offer in the 4th campaign, 0 otherwise|
|AcceptedCmp5| 1 if customer accepted the offer in the 5th campaign, 0 otherwise|
|Response | 1 if customer accepted the offer in the last campaign, 0 otherwise|
|**PLACE**||
|NumWebPurchases| Number of purchases made through the company’s web site|
|NumCatalogPurchases| Number of purchases made using a catalogue|
|NumStorePurchases| Number of purchases made directly in stores|
|NumWebVisitsMonth| Number of visits to company’s web site in the last month|

### Data Analyst dan Clustering

### **Kesimpulan**
- Clustering Gold :
  - Education : Basic
  - Age : 54
  - Children : 1
  - NumDealsPurchases : 2
  - NumWebPurchases : 5
  - NumCatalogPurchases : 5
  - NumStorePurchases : 8
  - NumWebVisitsMonth : 4
  - AcceptedCmp1 : 1
  - AcceptedCmp2 : 0
  - AcceptedCmp3 : 1
  - AcceptedCmp4 : 1
  - AcceptedCmp5 : 1
  - Income : 70.298
  - Total_Spendings : 1.075
  - Percentage 0,015%
  - Customer ini memiliki pendapatan yang paling tinggi, pembelian dengan quantity terbanyak.
  
- Clustering Silver :
  - Education : 2n Cycle
  - Age : 51
  - Children : 1
  - NumDealsPurchases : 2
  - NumWebPurchases : 3
  - NumCatalogPurchases : 1
  - NumStorePurchases : 4
  - NumWebVisitsMonth : 7
  - AcceptedCmp1 : 0
  - AcceptedCmp2 : 0
  - AcceptedCmp3 : 1
  - AcceptedCmp4 : 0
  - AcceptedCmp5 : 0
  - Income : 34.561
  - Total_Spendings : 164
  - Percentage : 0,004%
  - Customer ini memiliki pendapatan yang sedang, pembelian dengan quantity sedang.
 
- Clustering Silver :
  - Education : Basic
  - Age : 54
  - Children : 1
  - NumDealsPurchases : 3
  - NumWebPurchases : 4
  - NumCatalogPurchases : 2
  - NumStorePurchases : 5
  - NumWebVisitsMonth : 5
  - AcceptedCmp1 : 1
  - AcceptedCmp2 : 0
  - AcceptedCmp3 : 0
  - AcceptedCmp4 : 1
  - AcceptedCmp5 : 0
  - Income : 666.667
  - Total_Spendings : 471
  - Percentage : 0,70%
  - Customer ini memiliki pendapatan yang paling kecil, pembelian dengan quantity terkecil.


### **Saran**
- Tim marketing perlu menjaga hubungan baik pada customer yang masuk clustering "Gold", hal ini di karenakan customer memiliki pendapatan yang tinggi dan total pengeluaran untuk belanja yang tinggi. Ini bisa menjadi peluang untuk perusahaan dan tim marketing melakukan pemasaran sedangkan untuk customer yang masuk dalam clustering 'Silver' dan 'Platinum' tidak dijadikan fokus untuk pemasaran/target hal ini dikarenakan total pendapatan dan total pengeluaran uangnya untuk belanja lebih sedikit, jika hal ini menjadi fokus perusahaan maka akan membesarkan beban pada laporan keuangannya saja.


<br>

# **OTHERS PROJECT**

**My Project :** [Data Analyst](#data-analyst) | [Machine Learning](#machine-learning) | [Data Visualization](#data-visualization)

**Tech stacks currently using** <br>

<code><a href="https://code.visualstudio.com/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-ar21.svg"></a></code>
<code><a href="https://jupyter.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/jupyter/jupyter-ar21.svg"></a></code>
<code><a href="https://www.python.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"></a></code>
<code><a href="https://www.mysql.com/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/mysql/mysql-ar21.svg"></a></code>
<code><a href="https://www.microsoft.com/en-us/sql-server/sql-server-downloads" target="_blank"><img height="50" src="https://cdn.worldvectorlogo.com/logos/microsoft-sql-server-1.svg"></a></code>
<code><a href="https://www.postgresql.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/postgresql/postgresql-ar21.svg"></a></code>
<code><a href="https://powerbi.microsoft.com/en-us/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/microsoft_powerbi/microsoft_powerbi-ar21.svg"></a></code>
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147" target="_blank"><img height="30" src="https://cdn.worldvectorlogo.com/logos/tableau-logo.svg"></a></code>
<br>
<br>
<table>
<tbody>
 <tr>

<h1 align="left">Data Analyst</h1>
  
<td align="left" width="50%">
<span><b><Left>E-Commers Pakistan</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/EDA---Pakistan-s-Larges-Ecommers" target="_blank">
<img height=250px src="https://github.com/mhdalfarisy/EDA---Pakistan-s-Larges-Ecommers/blob/main/Images/62253a402fccf.jpg"> 
</td>
<!-- <tr> -->
<td align="left" width="50%">
<span><b><Left>Employee Attrition</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Employee-Analysis-Attrition-Report" target="_blank">
<img height=250px src="https://github.com/mhdalfarisy/Employee-Analysis-Attrition-Report/blob/main/Aset/Reasons-Attrition1_large%20(1).jpg"> 
</td>
</tbody>
</table>
 <tr>
<br>
<table>
<tbody>
 <tr>
 
<h1 align="left">Machine Learning - Supervised</h1>

<td align="left" width="20%">
<span><b><left>California House Price</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/California-House-Price-Prediction-Using-Machine-Learning" target="_blank">
<img height=150px src="https://github.com/mhdalfarisy/California-House-Price-Prediction-Using-Machine-Learning/blob/main/gambar/CA-Sales-Home-Volume.png"> 
</td>

<td align="left" width="20%">
<span><b><left>Credit Card Fraud</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Credit-Card-Fraud-Prediction" target="_blank">
<img height=150px src="https://github.com/mhdalfarisy/Credit-Card-Fraud-Prediction/blob/main/68747470733a2f2f65787465726e616c2d636f6e74656e742e6475636b6475636b676f2e636f6d2f69752f3f753d687474707325334125324625324661692d6a6f75726e65792e636f6d25324677702d636f6e74656e7425324675706c6f61647325324632303139253246.jfif"> 
</td>

<!-- <tr> -->
<td align="left" width="20%">
<span><b><left>Telco Customer Churn</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Employee-Promotion" target="_blank">
<img height=150px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/7-Strategies-To-Reduce-Customer-Churn-Rate.png"> 
</td>

<!-- <tr> -->
<td align="left" width="20%">
<span><b><left>Employee Promotion</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Telco-Customer-Churn-Predict" target="_blank">
<img height=150px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/advance-career.jpg"> 
</td>

</tbody>
</table>
 <tr>
  
<h1 align="left">Machine Learning - Unsupervised</h1>  

<table>
<tbody>
 <tr>  
  
<!-- <tr> -->
<td align="center" width="30%">
<span><b><left>Segmentation Customer Mall</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Segmentation-Customer-Mall" target="_blank">
<img height=250px src="https://github.com/mhdalfarisy/Segmentation-Customer-Mall/blob/main/2.-Customer-Segmentation.jpg"> 
</td>
 
<!-- <tr> -->
<td align="center" width="30%">
<span><b><left>Segmentation Customer Supermarket</center></b></span>
<code><a href="https://github.com/mhdalfarisy/Customer-Supermarket" target="_blank">
<img height=250px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/istockphoto-1254636143-612x612.jpg"> 
</td> 

<!-- <tr> -->
<td align="center" width="30%">
<span><b><left>Segmentation German Credit Risk</center></b></span>
<code><a href="https://github.com/mhdalfarisy/German-Credit-Risk" target="_blank">
<img height=250px src="https://media.istockphoto.com/vectors/banking-credit-card-vector-id1353716726?b=1&k=20&m=1353716726&s=612x612&w=0&h=qkwNRlcHCDUxeSgVYau8FczoM6x0sl693nvjAAcRmio="> 
</td> 
 
</tbody>
</table>
 <tr>
  
<br>

<table>
<tbody>
 <tr>

<h1 align="left">Data Visualization</h1>
  
<td align="left" width="20%">
<span><b><Left>E-Commers Pakistan</center></b></span> 
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147/viz/ProjectE-CommersPakistanDashboard/Dashboard1" target="_blank">
<img height=200px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/Pakistan%20Visualisasi.png"> 
</td>
 
<!-- <tr> -->
<td align="left" width="30%">
<span><b><left>Employee Attrition Report</center></b></span> 
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147/viz/ProjectHumanResourceAttritionAnalysisDashboard/Dashboard1" target="_blank">
<img height=200px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/HRD%20VIsualisasi.png"> 
</td>
 
<!-- <tr> -->
<td align="left" width="25%">
<span><b><left>Telco Customer Churn</center></b></span> 
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147/viz/CustomerChunVisualization/Dashboard2?publish=yes" target="_blank">
<img height=200px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/Telco%20Customer%20Churn.png"> 
</td>
 
</tbody>
</table>
 <tr>



<br>
<!-- <h1 align="center">Others Data Visualization Report</h1> -->
<td align="left" width="30%">
<span><b><left>Others Data Visualization Report (Click Picture) :   </left></b></span> 
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147" target="_blank"><img height="100" src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/tol_devices_optimized.png"></a></code>
<br>
<br>
<br>
 
**💬 Ask me about anything, I'll be happy to help!** <br>
**💬 My inbox is always open, Contact me**
<br>
<br> 
  </a>
  <a href="mailto:m.alfarisy797@gmail.com">
    <img align="left" alt="Muhammad Al-farisy | Gmail" width="26px" src="https://cdn.worldvectorlogo.com/logos/official-gmail-icon-2020-.svg" />
  </a>
  <a href="https://www.linkedin.com/in/m-alfarisy97/">
    <img align="left" alt="Muhammad Al-farisy | LinkedIN" width="26px" src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" />    
  </a>
<br>
<br>


| <a href="https://github.com/mhdalfarisy"><img align="center" src="https://github-readme-stats.vercel.app/api?username=mhdalfarisy&show_icons=true&include_all_commits=true&theme=buefy&hide_border=true" alt="Anurag's github stats" /></a> | <a href="https://github.com/mhdalfarisy/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mhdalfarisy&layout=compact&theme=buefy&hide_border=true" /></a> |
| ------------- | ------------- |
 
<table>
<tbody>
 <tr>
 
<h1 align="left">THANKS YOU !!! </h1>

<td align="center" width="30%">
<img height=300px src="https://media.giphy.com/media/dyzew7Py7bnW9DiJJj/giphy.gif"> 
</td>  
  
<!-- <td align="center" width="30%">
<img height=300px src="https://media.giphy.com/media/7c8QeB0VMddFOuu4iR/giphy.gif"> 
</td>
  
<td align="right" width="30%">
<img height=300px src="https://media.giphy.com/media/gutZ5Pm6Xl62eIf5RZ/giphy.gif"> 
</td>    -->

⭐️ From [Muhammad Al-farisy](https://github.com/mhdalfarisy)
