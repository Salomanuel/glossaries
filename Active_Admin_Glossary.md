# Active Admin

## install
`$ rails generate active_model:install`

## add models
`$ rails generate active_admin:resource Potatoes`

## configure dashboard
`app/admin/dashboard.rb`

## admin roles
are defined in `db/seeds.rb`
and in our case, the credentials are in:
`db/seeds/development.yml`
```
- email: 'jw@cashcape.com'
- password: 'pleasechangeme'
```

## `default actions`

The `default_actions` method adds the “View”, “Edit” and “Destroy” links.