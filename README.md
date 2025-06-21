/***************** installation de mon projet de formation en ligne et de E-commerce. ************************/ 

  ------ > ce projet fonctionne avec docker, symfony , mysql , phpmyadmin, mailhog ------->

  Structure des fichier

  my-project/
├── docker-compose.yml
├── .env
├── web/
│   ├── Dockerfile
│   └── symfony/ (votre projet Symfony)
└── mailhog/
    └── Dockerfile (optionnel ou pas)

    ############## intallation des fichiers ##################

1) docker
    docker-compose up -build
2) symfony
   migration uniquement
