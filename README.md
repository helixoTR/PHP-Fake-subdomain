# PHP-Fakesubdomain
Bu projede sizlere nasıl basit bir şekilde php kullanarak sahte alt alanadı yapılır bunu gösterdim.
Bu kodlar sadece Apache destekli sunucularda çalışmaktadır, nginx vb. altyapılı sunucularda çalışmamaktadır.
.htaccess dosyası içerisinde ki yourdomain.com olarak bıraktığım yere kendi domaininizi yazmalısınız.
Alan adı dns yönetim panelinizden bir adet A kaydı oluşturup adını * olarak bırakıp kaydetmelisiniz yani örnek;
Type: A
Name: *
IPv4 address: Hosting IPv4 adresiniz

[EN]
In this project, I showed you how to make a fake subdomain using php in a simple way.
These codes only work on apache supported servers.
You should write your own domain in the .htaccess file where I left it as yourdomain.com.
You should create an A record from your domain name dns management panel, leave the name as * and save it, so for example;
Type: A
Name: *
IPv4 address: Your Hosting IPv4 address
