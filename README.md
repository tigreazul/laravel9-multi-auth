<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# Multi Autenticacion con Laravel 9

## Instalación

 - composer install
 - npm install
 - php artisan migrate
 
##### Desplegar el proyecto
 - npm run dev
 - php artisan serve

## Perfil Usuario


```mermaid
graph LR
A[Login User] -- Redirect --> B{Dashboard User}
```


## Perfil Administrador

```mermaid
graph LR
A[Login Admin] -- Redirect --> B{Dashboard Admin}
```


> **Luego:** Creación de perfiles por permisos y accesos.
