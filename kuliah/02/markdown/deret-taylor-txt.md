# Deret Taylor
## Pengenalan
Deret Taylor adalah suatu cara untuk mengekspresikan fungsi matematika sebagai jumlah deret tak berhingga dari suku-suku yang ditentukan berdasarkan turunan fungsi tersebut di suatu titik. Deret Taylor sangat berguna dalam matematika dan banyak disalahgunakan dalam bidang sains dan rekayasa. Deret Taylor pertama kali diperkenalkan oleh matematikawan Inggris, Brook Taylor, pada abad ke-18.

Deret Taylor terdiri dari dua jenis, yakni Deret Taylor dan Deret McLaurin. Deret Taylor adalah deret yang digunakan untuk mengekspresikan fungsi pada titik tertentu yang tidak harus nol. Sedangkan Deret McLaurin adalah kasus khusus dari Deret Taylor, di mana titik yang digunakan adalah nol. Dalam artikel ini, kita akan membahas Deret Taylor secara umum.

## Bentuk Umum
Bentuk umum dari Deret Taylor adalah sebagai berikut:

$$f\left(x+\varDelta x\right)=f\left(x\right)+\dfrac{\varDelta x}{1!}f'\left(x\right)+\dfrac{\varDelta x^{2}}{2!}f''\left(x\right)+\cdots+\dfrac{\varDelta x^{n}}{n!}f^{\left(n\right)}\left(x\right)+\cdots$$

atau 

$$ f(x+\Delta x) = \sum^{\infty}_{n=0} {f^{(n)}(x)\over n!} (\Delta x)^n $$
 
di mana $f^{(n)}(x)$ adalah turunan ke-$n$ dari fungsi $f(x)$ yang dievaluasi pada titik $x$. Dalam kata lain, persamaan di atas dapat digunakan untuk mengekspresikan nilai dari fungsi $f(x)$ di sekitar titik $x$ sebagai jumlah tak berhingga dari suku-suku deret, dengan setiap suku didasarkan pada nilai turunan fungsi tersebut di titik $x$.

Contoh
Mari kita lihat contoh penggunaan Deret Taylor. Misalkan kita ingin mengekspresikan fungsi eksponensial $f(x) = e^x$ dalam bentuk deret Taylor di sekitar titik $x=0$. Kita perlu menentukan turunan ke-n dari fungsi tersebut dan mengevaluasinya pada titik $x=0$. Turunan dari $f(x) = e^x$ adalah sama dengan fungsi itu sendiri, sehingga kita memiliki:

$$ f(x) = e^x , f^{(n)}(x) = e^x $$
 
Maka, kita dapat mengevaluasi turunan ini pada titik $x=0$:

$$ f(0) = e^0 = 1 , f^{(n)}(0) = e^0 = 1 $$ 

Dengan demikian, kita dapat mengganti nilai $f^{(n)}(x)$ dalam persamaan Deret Taylor dengan 1 dan memperoleh bentuk umum sebagai berikut:

$$ e^x = \sum^{\infty}_{n=0} {1\over n!} x^n $$
 
Dalam hal ini, kita telah berhasil mengekspresikan fungsi eksponensial sebagai jumlah deret tak berhingga dari suku-suku yang ditentukan berdasarkan turunan fungsi tersebut pada titik $x=0$.


Dari contoh tersebut kita bisa mengetahui bahwa deret Taylor adalah suatu cara untuk mengekspresikan fungsi matematika sebagai jumlah deret tak berhingga dari suku-suku yang ditentukan berdasarkan turunan fungsi tersebut pada suatu titik.
