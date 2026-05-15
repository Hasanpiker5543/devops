# DevOps Django Bank

[![CI/CD](https://github.com/El-Mehdi-Taoufik/devops/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/El-Mehdi-Taoufik/devops/actions/workflows/ci-cd.yml)

Mini-projet DevOps basé sur une application de gestion bancaire avec login, client dashboard, admin dashboard, comptes, transferts et transactions.

## Auteurs

El-Mehdi Taoufik | Bilal Chbanat |Mohamed Reda Bouchaiba

## DevOps

- Dockerfile
- docker-compose.yml
- GitHub Actions CI/CD
- Tests automatisés
- README
- Rapport PDF

## Lancement local

```powershell
pip install -r requirements.txt
cd bank
python manage.py migrate
python manage.py runserver
```

## Compte admin local

```text
URL: http://127.0.0.1:8000/admin/
Username: admin
Password: admin12345
```

## Docker

```powershell
docker compose up --build
```

## Tests

```powershell
cd bank
python manage.py test
```

## Image Docker

```text
ghcr.io/el-mehdi-taoufik/devops-django-bank:latest
```
