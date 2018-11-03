# uts-algoritma


#latihan1# Menentukan nilai perulangan

Alur Algoritmanya.

-Mendeklarasikan int x,y,a,b,progres.
-Program mulai berjalan dengan membaca nilai input a dan b
-nilai a=x dan b=y
-Mendeklarasikan nilai (x!=y) jika bernilai benar maka akan dibandingkan (x<y)
	jika x<y maka nilai x+a
	jika y<x maka nilai y+b
-sampai nilai x=y
-jika nilai x!=y bernilai salah maka program akan mencetak nilai x dan programpun berhenti.

*Berikut kode lengkapnya

int main()
{
    int x,y,a,b,progres;
    cout<< " Masukan nilai a :";
    cin>> a;
    cout<< " Masukan nilai b :";
    cin>> b;
    progres= true;
    x=a;
    y=b;

    while (progres)
    {
    if (x!=y)
     {
    if (x<y)
      {
     	x=x+a;
        }
        else
            {
     	 y=y+b;
    }
    else
          {
           progres=false;
           }
    }
    cout<< x;
	return 0;
}

![img](https://github.com/sitidarojah28/uts-algoritma/blob/master/latihan1/hasil1.png)
![img](https://github.com/sitidarojah28/uts-algoritma/blob/master/latihan1/hasil2.png)


#latihan2 #Menentukan nilai perulangan dan menentukan nilai NIM

Alur algoritmanya

-mendeklarasikan int T,X,N,Batas
-mendeklarasikan variabel T,X sebagai penyimpan nilai
-mendeklarasikan variabel N sebagai inputan
-mendeklarsikan variabel Batas sebagai perulangan.
-Membuat perbandingan untuk perulangan 
	while ( T<= Batas)
	T=N+X
	X=X+10
Berikut kode lengkapnya.

int main()
{
    int N,X,T,Batas;
    cout<< " Masukan Nilai N :" ;
    cin>> N;
    cout<< endl;

    Batas = N + 100;
    X=20;
    T=N;

    while ( T <= Batas)
    {
        T=T+X;
        X=X+10;
    }
    cout << "Hasilnya Adalah :" << T;
	return 0;
}
![img](https://github.com/sitidarojah28/uts-algoritma/blob/master/latihan2/hasil3.png)