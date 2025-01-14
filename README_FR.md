# API Suno Non Officielle

API non officielle basée sur **Python** et **FastAPI** pour Suno. Elle prend actuellement en charge la génération de morceaux de musique et de paroles.
Grâce à la gestion automatique des tokens et à une fonctionnalité de "keep-alive", vous n'avez pas à vous soucier de l'expiration des tokens.

## Caractéristiques

- Maintenance automatique des tokens et "keep-alive"
- Complètement asynchrone, rapide, et évolutif pour les futures extensions
- Code simple, facile à maintenir, idéal pour le développement secondaire

## Instructions d'utilisation

### Configuration

1. Modifiez le fichier `.env.example` puis renommez-le en `.env`.
2. Renseignez les champs `session_id` et `cookie`.

Ces informations doivent être récupérées initialement depuis un navigateur, puis sont ensuite maintenues automatiquement.

![cookie](./images/cover.png)

### Exécution

1. Installez les dépendances :

   ```bash
   pip3 install -r requirements.txt
   ```

2. Lancez l'application avec FastAPI :

   ```bash
   uvicorn main:app
   ```

### Utilisation avec Docker

```bash
docker compose build && docker compose up
```

### Documentation

Une fois le service configuré, accédez à `/docs` pour consulter la documentation API.

![docs](./images/docs.png)

### Contact

<img src="./images/wechat.jpg" width="382px" height="511px" />
