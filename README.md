## Initializing and Creating users
* Run `./init.sh`
* To create a user:
```sh
airflow users create [-h] -e EMAIL -f FIRSTNAME -l LASTNAME [-p PASSWORD] -r
                     ROLE [--use-random-password] -u USERNAME

# Example:
airflow users create \
          --username admin \
          --firstname Ahmed \
          --lastname Maawy \
          --role Admin \
          --email ultimateprogramer@gmail.com \
          --password passwrd12345
```
