# Soldier-Guard-Application
In this repo, an application has been shared that will display the soldiers' guard system. In the project, c# and sql are used.
 
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/6e196902-ebc3-4dbc-8610-9cfee6a8ff36)

•	Asker adında database oluşturduk.
•	İd için idenditity(Birer birer artırma) Kullandık.
•	Ad için varchar ile 25 karakter sınırlaması ile tablomuzu oluşturduk.
•	İnsert İnto ve values ile tek tek tablomuza isimleri ekledik.
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/9ff9c814-f8c7-4eaa-a577-7b090544da50)

![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/6e196902-ebc3-4dbc-8610-9cfee6a8ff36)

Form 1

 
•	4 Adet groupBox kullanıldı
•	7 adet Label kullanıldı.
•	7 adet listbox kullanıldı.
•	2 adet button kullanıldı.

Form 1 Kodlar
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/1f18091c-cda8-40f7-a385-c13e209069dd)


 
Sql ile bağlantı kodumuz.
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/7f3c39db-d79c-46b0-a1d0-7d2fcccc46f5)

 
Form 2 ye geçiş kodumuz button_2 ye atadık.

![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/5d86193d-61e7-4e5f-9db4-4b8948fed3b4)



 
Button 1 içine arraylist değişkeni oluşturduk.
Random değişkeni oluşturduk.
Bağlantımızı açtık.
İsimler tablomuz için değişken atadık.
While döngüsü ile dizilere ad sutununu çağırdık.
For içinde rastgele listbox da listelemesi için yönlendirdik.
Listboxa atamalarımızı yaptık.

 
Listboxdaki isimleri temizleme için yazdığımız kod.
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/b0d96cd7-233f-4666-8c8d-681eefb5c096)



Form2 
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/91536cbf-a601-4f6b-a8d4-381b8e88ead8)

 

3 adet groupbox kullanıldı.
1 adet dataGridView kullanıldı.
4 adet button kullanıldı.
3 adet label kullanıldı.
3 adet textbox kullanıldı.
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/b0f92687-59e7-4a2b-bede-f2cff6607a53)




 
Sql bağlantı kodumuz.
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/96928711-fca3-402b-884f-f3e79de880c8)


 

DataGrirdWiev da tablolarımızı listelemek için kullandığımız kod.
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/26ec4806-f0fc-4a84-8daf-bd3cd4bac014)

 
Button 3 e DataGrirdWiev tablolarımızı çağırması için atama yaptım.
![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/aa6b37e3-89f0-4c7e-ad31-26f5d2bb454b)


 

Button1 e Try Catch bloğu ile kayıt eklemek için tekrar tablomuza bağlantı yaptık ve komutlar ile ekle butonunu aktifleştirdim.
 ![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/beda8c43-734f-4d9d-9947-a23020d0492a)


Button2 ye silme oparatörünü atadık. Sql den tablomuzu çağırdık. Delete from kodu ile textbox5 e girilen isim silinir. Mesaage box ile silinen kayıt başarılı ise mesaj alınır.
 ![image](https://github.com/BerkayTemel/Soldier-Guard-Application/assets/34957283/4522c174-fcc8-485e-a57f-6e59c1e673d9)


Button 4 e Güncelleme atamasını yaptık. String olarak güncellemekomut parametresini oluşturduk. Update İsimler Set ad ile güncelle kodumuzu çağırdık. Şart olarak textbox5 e girilen ismin textbox 2 ye girilen ile değiştirilmesini sağladık.

