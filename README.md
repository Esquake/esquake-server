# [ESQUAKE](https://github.com/Esquake/esquake)'s server repository


## Server Environment

```
Raspberry Pi 3
Raspbian
```

## Keys

If you want to use this repository,  
you need 

> google key  
> telegram key   
> onesignal key   

Initialize on your own server.
To use the Firebase Admin SDK on your own server, use [a service account.](https://cloud.google.com/compute/docs/access/create-enable-service-accounts-for-instances)

### example key.json 
```
{
  "openAPI": {
    "key": "download your key"
  },
  "oneSignal": {
    "Authorization": "download your key",
    "app_id": "download your key"
  },
  "telegram": {
    "key": "download your key"
    "chat_id": "download your key"
  }
}
```

### earthquake data crawler
```
pip install -r requirements.txt
```


