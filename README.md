## Docker üzerinde Airflow'a PostgreSql bağlantısı

Airflow PostgreSql bağlantı aktifleştirmek için docker-compose.yml sağlayıcımıza postgres servis kısmında port ekleyip tekrar çalıştırmnız gerekmektedir.

![Ekran Alıntısı](https://user-images.githubusercontent.com/89980402/177709743-dca11d06-d59c-405d-938b-d7c1e27edd3e.PNG)

 docker-compose up -d --no-deps --build postgres

Hemen ardından Dbeaver ile airflow kullanıcı adı şifresini kullanarak bağlantı sağlayabilirsiniz.

 * Dbeaver: https://dbeaver.io/download/
 
 
