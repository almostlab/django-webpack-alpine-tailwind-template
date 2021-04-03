# Tixxpass

Ticket reseller system

## Local setup

Make sure you got `yarn` and `poetry` beforehand.

```
yarn install
poetry install
```

Run the Django server (`python manage.py runserver`) and Webpack in another tab (`yarn start`).

Or just: `poetry run honcho start`


## Production

Compile assets first with `yarn build`, then use Django collectstatic: `python manage.py collectstatic`.
