#PHP on heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

*	heroku上でPHPを動かすための基本セットです。
*	Procfileでドキュメントルートを指定しています。ドキュメントルートは`/htdocs`です。

---

###composer

composer.jsonでは、マルチバイトのみ、インストールしています。  
その他、`SendGrid`と`facebook SDK`のインストール用に入れた分を、`composer_optional.json`として入れていますので、ご自由にお使い下さい。  
[sendgrid/sendgrid-php](https://github.com/sendgrid/sendgrid-php)  
[facebook/facebook-php-sdk-v4](https://github.com/facebook/facebook-php-sdk-v4)