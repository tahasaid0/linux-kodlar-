# Linux Konsol Komutları

Bu projede, Linux işletim sisteminde sık kullanılan 20 komut ve işlevleri ele alınmıştır.

### CD Komutu
Bu komut, bir klasöre geçmek için kullanılır.<br>
>Kullanım : cd  <Klasör_Adı>

`cd`

![image](https://github.com/user-attachments/assets/cf2cdcb5-e1f7-430b-80c0-e95dfe809538)
>[!WARNING]
>Klasör adı yazarken adını hatasız ve büyük harf küçük harf uyumuna dikkat ediniz!

#

### DİR Komutu
Bu komut, terminalin bulunduğu konumdaki dosyanın içindeki öğeleri listeler.<br>
>Kullanım : dir <Klasör_Adı>

`dir`

![image](https://github.com/user-attachments/assets/6ff0b3d6-6de1-4839-a84b-eed34990c081)

#

### MKDİR Komutu
Bu komut, klasör içerisinde yeni bir klasör oluşturmak için kullanılır.<br>
>Kullanım : mkdir <Klasör_Adı>

`mkdir`

![image](https://github.com/user-attachments/assets/6e719fa8-b280-4b7a-a5ab-67ceb5901101)

#

### TOUCH Komutu 
Bu komut, yeni bir belge oluşturmak için kullanılır.<br>
>Kullanım : touch <belge_adı>

`touch`

![image](https://github.com/user-attachments/assets/b76bd981-6d30-4a07-8b3d-7b7b676fcc86)

#

### ECHO Komutu
Bu komut, belgenin içerisine yazı yazmaya yarar.<br>
>Kullanım : echo <yazı> > <dosya_adı>

`echo`

![image](https://github.com/user-attachments/assets/68452a91-84f8-43e7-af48-aaf6e7157e1b)

>[!TIP]
>İşlem çıktısı aşağıdaki gibidir.

![image](https://github.com/user-attachments/assets/f6122983-52f8-4d68-900d-bb7a84f06f06)

#

### REMOVE Komutu
Bu komut, silme işlemi yapmak için kullanılır.<br>
>Kullanım : rm <dosya_adı>

`rm`

![image](https://github.com/user-attachments/assets/89af8ea6-3152-4567-9527-66783970c1b9)

#

### MOVE Komutu
Bu komut, belgenin veya klasörün adını değiştirmeye yarar.<br>
>Kullanım : mv <dosya_adı> <yeni_dosya_adı>

`mv`

![image](https://github.com/user-attachments/assets/be1f3a67-fe2c-4c84-b778-53150506af11)

#

### COPY Komutu
Bu komut, dosya veya dizin kopyalamaya yarar.<br>
>Kullanım : cp <dosya_adı> <dosya_adı>

`cp`

![image](https://github.com/user-attachments/assets/1c2efff5-9594-4445-8537-e6f8f77be0a0)

#

### CAT Komutu
Bu komut, dosyanın içeriğini terminalde gösterir.<br>
>Kullanım : cat <dosya_adı>

`cat`

![image](https://github.com/user-attachments/assets/e029f383-ef24-4270-82d7-5f350ac7608e)

#

### DF Komutu
Bu komut, disk kullanımını gösterir.<br>
>Kullanım : df

`df`

![image](https://github.com/user-attachments/assets/826098e2-e1ae-48d8-8b96-259962b21dc6)

#

### HISTORY Komutu
Bu komut, linuxta kullanılan bütün komutların hepsini listelemeye yarar.<br>
>Kullanım : history

`history`

![image](https://github.com/user-attachments/assets/1a66b889-ab33-4bf9-9247-4efba49445be)

>[!NOTE]
>Bu komutta;
>
>`history 30`
>
>yazarak son 30 komutu görüntüleyebiliriz.

#

### PİNG Komutu
Bu komut, bir internet sitesinin ağ bağlantısını test etmeye yarar.<br>
>Kullanım : <ping www.youtube.com>

`ping`

![image](https://github.com/user-attachments/assets/3d8df195-e322-4f4f-82bd-fe1e742e0709)

#

### İFCONFİG Komutu 
Bu komut bir komut, ağ arayüzlerini ve bağlantı bilgilerini göstermeye yarar.<br>
>Kullanım : ifconfig

`ifconfig`

![image](https://github.com/user-attachments/assets/aab25009-cadd-4aa9-96f2-eaa8710ae402)

#

### SUDO Komutu
Bu komut, bir işlemde kök ayrıcalıkları kullanmak veya idari bir erişim sağlamak için kullanılabilir.<br>
>Kullanım : sudo <apt update>

`sudo`

![image](https://github.com/user-attachments/assets/1065f22e-c9b6-4681-836e-fa51be5a89bd)

>[!NOTE]
>Unutmayın bu işlemi yapmak için paraloyu bilmeniz gerekir :)

#

### FİND Komutu
Bu komut, belirli bir dosya veya dizini aramak için kullanılır.<br>
>Kullanım : find /home -name "<dosya_adı>"

`find /home -name`

![image](https://github.com/user-attachments/assets/6ca11fb4-0232-4061-bbbd-6387c091b0ba)

#

### UNAME Komutu
Bu komut, işlemci mimarisini göstermek için kullanılır.<br>
>Kullanım : uname -m

`uname -m`

![image](https://github.com/user-attachments/assets/5496344d-0083-427b-997d-b74d7a4fd1ae)

#

### FREE Komutu
Bu komut sistem belleği kullanım durumunu görüntülemek için kullanılır.<br>
>Kullanım : free

`free`

![image](https://github.com/user-attachments/assets/9ee6c72f-929b-464c-ba08-d0556f0db695)

#

### CLEAR Komutu
Bu komut terminalde yazılan kodları temizlemeye yarar.<br>
>Kullanım : clear

`clear`

![image](https://github.com/user-attachments/assets/9034b959-752c-4029-917c-0b6a5b7cf7ae)

>[!TIP]
>İşlem çıktısı şu şekildedir:

![image](https://github.com/user-attachments/assets/e57d3779-9063-4058-898c-9dcc5a3a0795)

#

### GREP Komutu
Bu komut, dosyalar içinde metin arar.<br>
>Kullanım : grep <"metin"> <dosya_adı>

`grep`

![image](https://github.com/user-attachments/assets/e471514b-4685-4f1e-af13-04b8a501046e)

#

### ZİP Komutu
Bu komut, dosya veya dizinleri sıkıştırmaya yarar.<br>
>Kullanım : zip <dosya_adı.zip> <dosya_adı>

`zip`

![image](https://github.com/user-attachments/assets/4d4f5ca3-a9fa-432c-a541-664bd4a4258a)

#
