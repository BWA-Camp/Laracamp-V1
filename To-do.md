1. Preparation Project
    - [X] Installation Laravel
        ```bash
        composer create-project laravel/laravel="8.6.2" Laracamp
        ```
    - [X] Create New Database

2. Migration
    - [X] Migration User Table Pt.1
    - [X] Migration User Table Pt.2
    - [X] Migration Camp Table
    - [X] Migration Camp Benefit Table
    - [X] Migration Camp Benefit Relation
    - [X] Migration Checkout Table

    ```bash
    #Command
    php artisan make:migration create_table_camps --table=camps

    php artisan make:model Camps

    php artisan make:model CampBenefit -m