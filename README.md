

 
<br>
<p align="center">Turbopass</p>


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
git clone git@bitbucket.org:Turbop/turbopass.git <path>
```
 
Switch the branch to `main`

```bash
git main
```

Git pull 

```bash
git pull
```
 
Switch the branch to `main`

```bash
 composer install
```

## run php server like wamp , xamp , mamp
```bash
create bagisto empty DB and set users and pass (bagisto,bagisto)
```

## Migrations
```bash
php artisan optimize:clear 
php artisan migrate:fresh --seed 
php artisan storage:link 
php artisan bagisto:publish --force 
php artisan optimize:clear 
```
### Rollback (if failed)
```bash
php artisan migrate:rollback 
```
### executing final commands (Run)
```bash
php artisan serve
```

 
 
