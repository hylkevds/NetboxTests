# Setup

```
docker-compose exec netbox /opt/netbox/netbox/manage.py createsuperuser
```

# Development commands
```
docker exec -ti netbox_netbox_1 /bin/bash
/opt/netbox/venv/bin/python manage.py makemigrations &&
```
