The project is on src

Run it locally without docker:
  - cd src
  - php artisan serve

Build docker image:
  - docker build -t <version-name> .

Example:
  - docker build -t laravel-deploy-gcr-v2 .

Run Docker image:
  - docker run -e PORT=80 -p 80:80 laravel-deploy-gcr-v2
  
Deploy on google cloud, follow:
  - https://youtu.be/00UqiF4hqNw?t=582
  
  
Thnkx to [https://github.com/harshalone/deploy-laravel-9-on-google-cloud-run](https://github.com/harshalone)
