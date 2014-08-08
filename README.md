#PHP on heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

*	heroku上でPHPを動かすための基本セットです。
*	Procfileでドキュメントルートを指定しています。ドキュメントルートは`/htdocs`です。
*	composerでマルチバイトをプリセットしています。
*	composer内では、sendgrid、facebookをコメントアウトで入れています。ご自由にインストール下さい。

---

[sendgrid/sendgrid-php](https://github.com/sendgrid/sendgrid-php)  
[facebook/facebook-php-sdk-v4](https://github.com/facebook/facebook-php-sdk-v4)