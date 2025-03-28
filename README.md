## Setup

- git clone git@github.com:denes096/taskmanager.git
- cd taskmanager
- cp .env.example .env
- sail up -d
- sail composer install 
- sail artisan config:cache
- sail artisan migrate 
- sail artisan db:seed