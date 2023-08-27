# laravel-react-env-template

This repository is a template repository of backend Laravel and frontend React projects.

In this repository, I built an environment by using the following technology.
I also focused on not using helpful tools like `create-react-app` and something like that.
So, every library related to React is installed manually.

- Docker
- PHP(8.1)
- Laravel(10.10)
- TypeScript(5.2.2)
- React(18.2.0)
- Vite(4.0.0)

# flow
1. Create a new repository with this template
2. `$ cd path-to-the/created-repository && docker-compose build`
3. `$ docker-compose exec -it laravel-react-app`
4. `# npm install`
5. `# composer install`
6. `# cp .env.example .env`
7. `# php artisan key:generate`
