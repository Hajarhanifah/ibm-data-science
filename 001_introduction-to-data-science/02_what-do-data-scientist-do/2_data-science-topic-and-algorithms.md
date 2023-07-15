- Regression : help to understand the data
- Data visualization : a key element for people to get across their message to people that don't understand that well what data science is
- Artificial neural networks : we have a lot to learn with nature so when we are trying to mimic our, our brain we can do some applications with this behavior with this biological behavior in algorithms.
- Data visualization with R : to gets the best results so many more times than some overblown, overworked algorithm that's just as likely to overfit as it is to make a good fit.
- So structured data : is more like tabular data things that you’re familiar with in Microsoft Excel format (rows and columns that's called structured data)
- Unstructured data : is basically data that is coming from mostly from web where it's not tabular (text, video, audio <<-- need to deploy more sophisticated algorithms to extract cata)

# Regresion
-  If you have ever taken a cab ride, a taxi ride, you understand regression.
- The moment you sit in a cab ride, in a cab, you see that there's a fixed amount there --> It says #250, You rather the cab, moves or you get off
- You have to pay that amount if you have stepped into a cab --> are increases when tha cab moving
- so, theres is a RELATIONSHIPS between **Distance** and **Amount**
- if you're not moving and you're stuck in traffic, then every additional minute you have to pay more
    - as the minutes increase, your fare increases.
    - As the distance increases, your fare increases
- while all this is happening you've already paid a base fare which is the constant.
- Regression tells you what the base fare is and what is the relationship between time and the fare you have paid, and the distance you have traveled and the fare you've paid
- regression allows you to compute that constant that you didn't know. That it was $2.50, and it would compute the relationship between the fare and and the distance and the fare and the time.
- That is regression

# Note
- Using complicated machine learning algorithms does not always guarantee achieving a better performance. Occasionally, a simple algorithm such as k-nearest neighbor can yield a satisfactory performance comparable to the one achieved using a complicated algorithm. It all depends on the data
- In any field, and data science is no different, a simple solution is always preferred over a complicated one, especially if the performance is comparable.


- Regression analisis —> form dari predictive model teknik yang menginvestigate dipendent dan independent variabel
    - data dibagi 2 dipendent variable dan independent variable
    - Dipendent Variable —> variable yang tergantung kepada variable independen (mempengaruhi)
    - Dipendent —> dipengaruhi
    - Independent —> mempengaruhi
    - ex. berat badan (dependent variable): dipengaruhi oleh makanan, hormon, dkk (independent variable) —> yang paling signifikan memengaruhi : makanan
        - ada variable yang berpengaruh positif dan negatif
        - ex. negatif : olah raga, stress, dll (berat badan mennurun) 
        - ex. positif : makanan (makin banyak makan makin gendut)
     
## PENGGUNAAN REGRESION
- menentukan strength predictord
- forcasting an effect 
- menentukan trend forcasting —> bakal naik atau tidak berat badannya?


## LINIAR VS LOGISTIC REGRESSION
- Linear 
    - menggunakan straightline method
    - menggunakan continues variable (berat badan, gaji, umur)
    - output = value
- Logistic (categorical variable)
    - menggunakan signoid
    - output = probabilitas

## LINEAR REGRESSION 
- metode untuk memprediksi dipendent variable berdasarkan values independen variable X yang dapat digunakan untuk kasu2 yang sifatnya kontinyu (berat badan, gaji, umur, dll)
- Selection Criteria
    - classification and regression capabilities —> memastikan tools yang dipakai bisa melakukan regresi
    - data quality —> data berkualitas / bukan missing data
    - computational complexity —>  komputasi bisa menggunakan phyton, R, dsb
    - comperhensible and transparent —>
- SERING DIGUNAKAN
    - evaluasi trends dan sales 
        - memperkirakan sales akan naik/ turun menjadi berapa persen ??
    - Analyzing the impact of price change
        - ketika harga berubah, variable mana yang bisa memengaruhi orang untuk membeli / penjualan
    - Risk Management 
        - lihat resiko yang terjadi
        - mana yang paling beresiko dan tidak

## LINEAR REGRESSION ALGORITHM 


## R SQUERE 
- Statictical measure, ttg seberapa dekatnya dengan regresi yang sempurna/
- koofesien dari multiple regression
- seberapa besar presentase model terhadap hasil

