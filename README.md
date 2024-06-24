### Environnement AWS Local pour Terraform

### Dépendances nécessaires

- aws-cli
- Python
- Docker
- Terraform

1. Installation de la AWS CLI Tool

```sh
pip install awscli
aws --version
```

2. Installation de localstack

```sh
pip install localstack
 ```

3. installation de aws-cli local

```sh
pip install awscli-local
```

4. Demmarrage de LocalStack

```sh
docker-compose up -d 
```

5. Credentials

```sh
aws configure set aws_access_key_id test
aws configure set aws_secret_access_key test
aws configure set region us-east-1
```
