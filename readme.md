Laravel Framework 5.6.40
PHP 7.2
node v12.22.9

/usr/local/lib
└── laravel-echo-server@1.6.3

├── axios@0.18.1
├── bootstrap@4.6.2
├── cross-env@5.2.1
├── express@4.19.2
├── ioredis@5.3.2
├── jquery@3.7.1
├── laravel-echo@1.16.1
├── laravel-mix@2.1.14
├── lodash@4.17.21
├── popper.js@1.16.1
├── socket.io-client@2.3.0
├── socket.io@4.7.5
└── vue@2.7.16


chat запуск (redis-server для очередей):
php artisan queue:work
laravel-echo-server start
php artisan serve
