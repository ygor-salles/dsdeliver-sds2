# dsdeliver-sds2

Aplicativo Web de entrga de pedidos - Deliver

## Tecnologias utilizadas:

### Backend
* Java com SpringBoot framework


### Frontend
* ReactJS com typescript
* Maps com React Leaflet

## Armazenamento em nuvem:
* frontend: Netlify
* backend: Heroku

## Link do site:
https://ygor-salles-sds2.netlify.app/

* Link do backend heroku
https://ygor-dsdeliver.herokuapp.com/

## ATENÇÃO: O PROJETO NÃO RODA LOCALMENTE NO PROFILE PROD! Para rodar o projeto localmente, mude para o profile test.

```bash
heroku login
heroku git:remote -a <nome-do-app>
git remote -v
git subtree push --prefix backend heroku main
```
