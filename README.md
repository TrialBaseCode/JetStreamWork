# JetStream Laravel
> jet stream is laravel dashboard where you need to work admin base project.

> I register Then login
When i Update the photos not show in profile update.

1. Go to config then jetstream.php
2. Uncomment in  Features::profilePhotos() in feature
3. Then we can upload the photo but not see the photo some time so Go to
   1. env
       -Change APP_URL=http://localhost to APP_URL=http://127.0.0.1:8000
4. Make local databse jetstream
    -Give jetstream  database in laravel .env file.

