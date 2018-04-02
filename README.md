## configuring the jupyter password

Open an python REPL (ipython), then import the passwd lib:
```
In [1]: from IPython.lib import passwd
In [2]: passwd()
Enter password:
Verify password:
Out[2]: 'sha1:67c9e60bb8b6:9ffede0825894254b2e042ea597d771089e11aed'
```

In the above example 'sha1:67c9e60bb8b6:9ffede0825894254b2e042ea597d771089e11aed' would be what you need to copy in your docker-compose.yml file for the jupiter service.

## start

### change the permissions on the data/jupiter subdirectory
### docker-compose up -d

