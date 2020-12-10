# Integração com PHPMAILER v6.0.7

### Depedências
* PHP >= 7.2
* PHPMAILER 6.0.7



### Installation:

No arquivo composer.json, adicione a seguinte dependency no seu projeto:

```json
"require": {
    "ja-martins/emailmailer": "1.0.*"
}
```



### Adicione no config do seu projeto o seguinte

```php
define("MAIL", [
    "host" => "smtp.example.com",
    "port" => "587",
    "user" => "user@example.com",
    "passwd" => "secret",
    "from_name" => "Your name",
    "from_email" => "Your email"
]);



### Developer
* [Jorge Almir Martins] - Desenvolvedor da bíblioteca

License
----

MIT
