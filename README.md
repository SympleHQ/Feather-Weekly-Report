# Feather-Weekly-Report
SQL script that generates Feather's Weekly Report on Jobs &amp; Tasks

### SSH into production box

ssh into any production instance using fab commands. With active <env>, run:
```
$ fab production remote
```

### Run script
Start Django's interactive python shell_plus

```
$ python manage.py shell_plus
```

Copy & paste Script into interactive shell and run. 
`jobs.csv` and `tasks.csv` will be output into the project directory.

### Pull files down locally

Run SCP command to pull files down locally. For example:

```
$ scp ubuntu@52.53.153.161:/home/ubuntu/symple/*.csv ~/Desktop/
```
