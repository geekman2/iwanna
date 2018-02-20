# iwanna
Frictionless Infrastructure

Single command management

## SMS notifications

Recieve SMS notifications on the hour while working and when you have fifteen minutes left. 

## Usage

```
iwanna
iwanna jupyter
iwanna mongo -t inf
iwanna jupyter t2.xlarge
iwanna jupyter -t 3h
iwanna jupyter large -t 2hrs -i jupyter/datascience-notebook
iwanna extend -t 1h -n deep_learning_awesomeness
iwanna setup
```

- Defaults to five hours up time if not specified.
- Defaults to `jupyter/scipy-notebook`
- returns ip:port and security credentials

## Compose Systems

```
iwanna jupyter+mongo+redis
New Jupiter created at ...
New mongo created at ...
New redis created at ...

Access mongo in jupyter via hostname this_mongo.
Access redis in jupyter via hostname this_redis.
```

## Connect to Github

```
iwanna jupyter t2.xlarge -g joshuacook/redhat
iwanna jupyter t2.xlarge -r redhat
```

## Preconfigure with your dotfiles

## Push to github branch named with date and time on shutdown
