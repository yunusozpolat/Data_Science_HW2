# Data_Science_HW2
## EN
The number of gold, silver and bronze medals won by the countries participating in these games in the summer Olympics held between 1896-2008 are given in the files ‘altin.xlsx’, ‘gumus.xlsx’ ve ‘bronz.xlsx’. Human development indexes of 2008 belonging to 196 countries around the world are included in the 'insani_gelisim_indeksi.xlsx' file. (Human Development Index is a measurement prepared for countries in the world in terms of life expectancy, literacy rate, education and life level)
Write Python code that performs the following operations:
1) Read and save the data files as dataframe.
2) Combine the gold, silver and bronze medal numbers of the countries mentioned in at least one of the gold, silver or bronze medal files into a single dataframe you call df_madalya.
3) There should be three column information in df_madalya and column names should be “Ulke”, “Altin”, “Gumus”, “Bronz” respectively.
4) Set the NaN values in df_madalya to 0.
5) Add the Gold, Silver and Bronze medal numbers for each country in df_medalya and keep this total in a new column called “Toplam”.
6) Create a new dataframe named df_countries that contains the Gold, Silver, Bronze, Total medal numbers of the countries in df_medalya and human development index information for 2008.
7) df_countries should contain five column information and the column names should be “Ulke”, “Altın”, “Gumus”, “Bronz”, “Toplam” ve “2008_Insani gelisim indeksi” respectively.
8) Using df_countries, draw the scatter graph of the countries' total medals and human development index.
9) Draw a bar chart showing the number of gold medals and total medals for countries with a human development index of 0.9 and above.
## TR
1896-2008 yılları arasında yapılan yaz olimpiyatlarında bu oyunlara katılan ülkelerin kazandıkları altın, gümüş ve bronz madalya sayıları ‘altin.xlsx’, ‘gumus.xlsx’ ve ‘bronz.xlsx’ dosyalarında verilmiştir. Dünya üzerindeki 196 ülkeye ait 2008 yılı insani gelişme indeksleri ise ‘insani_gelisim_indeksi.xlsx’ dosyasında yer almaktadır. (İnsani Gelişme İndeksi (Human Development Index), Dünya'daki ülkeler için yaşam uzunluğu, okur yazar oranı, eğitim ve yaşam düzeyi doğrultusunda hazırlanan bir ölçümdür)
Aşağıdaki işlemleri gerçekleştiren Python kodunu yazınız:
1) Veri dosyalarını dataframe olarak okuyup kaydediniz.
2) Altın, gümüş ya da bronz madalya dosyalarının en az birinde adı geçen ülkelerin aldıkları altın, gümüş ve bronze madalya sayılarını df_madalya adını verdiğiniz tek bir dataframede birleştiriniz. 
3) df_madalya’da üç adet sütun bilgisi yer almalıdır ve sütun isimleri sırası ile “Ulke”, “Altin”, “Gumus”, “Bronz” şeklinde olmalıdır. 
4) df_madalya’da NaN olan değerleri 0 yapınız.
5) df_madalya ‘da yer alan her ülke için Altın, Gumus ve Bronz madalya sayılarını toplayanız ve bu toplamı  “Toplam” adındaki yeni bir sütunda tutunuz. 
6) df_madalya ‘da yer alan ülkelerin Altın, Gumus, Bronz, Toplam madalya sayılarını ve 2008 yılı insani gelişim indeks bilgilerini içeren df_ulkeler adında yeni bir dataframe oluşturunuz. 
7) df_ulkeler’de beş adet sütun bilgisi yer almalıdır ve sütun isimleri sırası ile “Ulke”, “Altın”, “Gumus”, “Bronz”, “Toplam” ve “2008_Insani gelisim indeksi” şeklinde olmalıdır. 
8) df_ulkeler ‘i kullanarak ülkelerin toplam madalya sayısına ve insani gelişim indeksine ait dağılım (scatter, serpme) grafiğini çizdiriniz.
9) İnsani gelişim indeksi 0.9 ve üzeri olan ülkelere ait altın madalya ve toplam madalya sayılarını gösteren sütun grafiğini (bar chart) çizdiriniz.
