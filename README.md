### **Bash Script İle Lamp Wordpress Kurulumu**

>Bu uygulama Ubuntu 18.04 üzerinde yapılmıştır
 
**Nedir?**

- Bu script lamp wordpress kurulumunu içermektedir
- **lamp** (Linux, Apache2, MySQL, PHP)
- Lamp Wordpress kurulumu belli bir süreç ve zaman gerektirir bu kurulum script haline getirilerek zaman israfı ortadan kaldırılıyor
- Kurulum başladıktan sonra girmemiz gereken değerler bulunuyor bunları göstereceğiz


**Kurulum**

- Root yetkisine sahip oluyoruz

```
sudo -i
```

- Dosyalarımızı github üzerinden çekiyoruz

```
git clone https://github.com/denomasdenetimotomasyon/lampwpscript
```

- Dosyaya girelim

```
cd bashscriptlampwp
```

- chmod 777 komutu ile lampwp.sh dosyasını herkes tarafından okunabilir, çalıştırılabilir ve yazılabilir hale getiriyoruz

```
chmod 777 lampwp.sh
```

- Çalıştıralım

```
bash lampwp.sh
```

- Enter'e basın

![lawp](/img/lawp.png)


- Enter'e basın

![lawp](/img/lawp1.png)

- PHPMYADMİN için bir şifre girin

![lawp](/img/lawp2.png)

- Şifrenizi tekrar girin

![lawp](/img/lawp3.png)

- **Y** yazıp enter'e basın


```
Press y/Y for Yes, any other key for No: 
```

- **1** yazıp enter'e basın

```
Please enter 0 = LOW, 1 = MEDİUM and 2 = STRONG: 
```

- Şifrenizi girin

```
New password:
```

- Şifrenizi tekrar girin

```
Re-enter new password:
```

- **Y** yazıp enter'e basın

```
Do you wish to continue with the password provided(Press y/Y for Yes, any other key for no) :
```

- **Y** yazıp enter'e basın

```
Remove anonymous users? (Press y/Y for Yes, any other key for no) :
```

- **Y** yazıp enter'e basın

```
Disallow root login remotely? (Press y/Y for Yes, any other key for no) :
```

- **Y** yazıp enter'e basın

```
Remove test database and access to it? (Press y/Y for Yes, any other key for no) :
```

- **Y** yazıp enter'e basın

```
Reload privilege tables now? (Press y/Y for Yes, any other key for no) :
```


- Kurulum tamamlandı 


- Kurulumu kontrol edelim

```
IP_ADRESİ/wordpress
```

![lawp](/img/lawp5.jpg)

- İndirdiğiniz dosyayı silin

```
rm -r lampwp.sh
```
