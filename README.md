Generating Mailables Documetation: https://laravel.com/docs/10.x/mail#generating-mailables

## Generate mailable class command

```
php artisan make:mail OTPMail

```

## SMTP Setup

```
MAIL_MAILER=smtp
MAIL_HOST=mail.host
MAIL_PORT=587
MAIL_USERNAME=info@teamrabbil.com
MAIL_PASSWORD=host.password
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS="info@teamrabbil.com"
MAIL_FROM_NAME="POS Project"
```
