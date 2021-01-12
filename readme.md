# django-staticfiles-to-keycdn buildpack

Collects staticfiles and sends them to keycdn

Required env variables:

* KEYCDN_USER: keycdn username
* KEYCDN_ZONE: keycdn push zone name

Example usage:

```bash
heroku buildpacks:add https://github.com/JaakkoRoponen/django-staticfiles-to-keycdn

git push heroku master
```
