

 
<br>
 


<br>
<p align="center">
 <a align="center" href="https://www.turbopass.com/">
    <img src="https://www.turbopass.com/themes/turbopass/img/logo.png" alt="Turbopass Logo" title="Turbopass"   height="60" />
</a>
</p>
<p align="center">With</p>


<p align="center">
    <a href="http://www.bagisto.com"><img src="https://bagisto.com/wp-content/themes/bagisto/images/logo.png" alt="Total Downloads"></a>
</p>


<p align="center">
    ➡️ <a href="https://bagisto.com/en/">Website</a> | <a href="https://devdocs.bagisto.com/">Documentation</a> | <a href="https://webkul.com/blog/laravel-ecommerce-website/">Installation Guide</a> | <a href="https://forums.bagisto.com/">Forums</a> | <a href="https://www.facebook.com/groups/bagisto/">Community</a> ⬅️
</p>
  

 
 
## Local Installation

  
 

#### Linux or Mac users or windows
 

```bash
git clone 
```
 
<br> 

copy .env.example to a new file named .env
```bash
cp .env.example .env
```

```bash
 composer install
```

## for Database and Redis with Docker 

```bash
docker-compose up -d 
```
## Migrations
```bash
php artisan optimize:clear 
php artisan migrate:fresh --seed 
php artisan storage:link 
php artisan bagisto:publish --force 
php artisan optimize:clear 
```
### executing final commands (Run)
```bash
php artisan serve
```

### admin dashboard
```bash
admin@example.com
admin123 
```

### Rollback (if failed)
```bash
php artisan migrate:rollback 
```

 
 
