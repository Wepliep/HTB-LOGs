
# cURL


| Command                                                                                                         | Description                                          |
|-----------------------------------------------------------------------------------------------------------------|------------------------------------------------------|
|  curl ***-h***                                                                                                        | cURL yardım menüsü.                                       |
|  curl inlanefreight.com                                                                                         | Basit GET isteği.                                    |
|  curl -s ***-O*** inlanefreight.com/index.html                                                                        | Dosya indirme.                                        |
|  curl ***-k*** https://test.com                                                                              | HTTPS sertifika doğrulamasını atlama.              |
|  curl inlanefreight.com ***-v***                                                                                      | HTTP istek ve yanıtlarını detaylı bir şekilde yazdırma.             |
|  curl ***-I*** https://test.com                                                                          | HEAD isteği göndererek yanlızca yanıt başlıklarını yazdırır.     |
|  curl ***-i*** https://test.com                                                                          | Yanıt başlığını ve gövdesini yazdırır.             |
|  curl https://test.com ***-A*** 'Mozilla/5.0'                                                            | User-Agent başlığını belirtmek için kullanılır.                                |
|  curl ***-u*** admin:admin http://<SERVER_IP>:<PORT>/                                                                 | HTTP kullanıcı girişlerinde kullanılır.             |
|  curl http://***admin:admin@<SERVER_IP>***:<PORT>/                                                                    | HTTP de kullanıcı girişlerini URL de yapmakta kullanılır. |
|  curl ***-H 'Authorization: Basic YWRtaW46YWRtaW4='*** http://<SERVER_IP>:<PORT>/                                     | İstek başlığı yazma                                   |
|  curl 'http://<SERVER_IP>:<PORT>/***search.php?search=le***'                                                          | GET isteğinde parametre belirtme                                  |
|  curl ***-X POST -d 'username=admin&password=admin'*** http://<SERVER_IP>:<PORT>/                                     | POST isteğiyle veri gönderme                     |
|  curl ***-b 'PHPSESSID=c1nsa6op7vtk7kdis7bcnbadf1'*** http://<SERVER_IP>:<PORT>/                                      | İstek çerezi ayarlama                                  |
|  curl -X POST ***-d '{"search":"london"}'*** -H 'Content-Type: application/json' http://<SERVER_IP>:<PORT>/search.php | JSON verileriyle POST isteği gönderme                     |

# APIs

| Command                                                                                                                                                | Description           |
|--------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|
|  curl http://<SERVER_IP>:<PORT>/api.php/city/london                                                                                                    | Girişi okuma            |
|  curl http://<SERVER_IP>:<PORT>/api.php/city/                                                                                                 | Tüm girişleri okuma      |
|  curl http://<SERVER_IP>:<PORT>/api.php/city/ ***\| jq***                                                                                                 | Tüm girişleri okunabilir moda getirme      |
|  curl ***-s*** http://<SERVER_IP>:<PORT>/api.php/city/ \| jq                                                                                                 | Gereksiz JSON içeriklerini gizleme      |
|  curl ***-X POST*** http://<SERVER_IP>:<PORT>/api.php/city/ -d '{"city_name":"HTB_City", "country_name":"HTB"}' -H 'Content-Type: application/json'          | Giriş oluşturma    |
|  curl ***-X PUT*** http://<SERVER_IP>:<PORT>/api.php/city/london -d '{"city_name":"New_HTB_City", "country_name":"HTB"}' -H 'Content-Type: application/json' | Giriş güncelleme |
|  curl ***-X DELETE*** http://<SERVER_IP>:<PORT>/api.php/city/New_HTB_City                                                                                    | Giriş silme          |