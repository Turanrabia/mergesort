# mergesort
#  ALGORİTMALAR PROJE 2 (BİRLEŞTİRME SIRALAMA)

##  SORU

[16,21,11,8,12,22] -> Sıralamayı Birleştir

- Fiyatlandırma sıralamasına göre aşamalarını ifade eder.
- Büyük-O'nu yazınız.

##  CEVAP

>                          [16,21,11,8,12,22]
> > [16,21,11] - [8,12,22]
> > [16]-[21,11] - [8]-[12,22]
> > [16]-[21]-[11] - [8]-[12]-[22]
> > [16]-[11,21] - [8]-[12,22]
> > [11,16,21] - [8,12,22]
> > [8,11,12,16,21,22]
> Büyük-O notasyonu
> >**A(nlogn)**