# OneSignal Push Notification Demo

Simple example of OneSignal Push Notification SDK

## Send Example Push Notification 

```
curl --include \
     --request POST \
     --header "Content-Type: application/json; charset=utf-8" \
     --header "Authorization: Basic ZjhmZjkxNmItZWY3MC00ZDA4LWFhMDgtNzY3MzRjZTQ0ZTc5" \
     --data-binary "{\"app_id\": \"91e56e15-5049-4f98-b331-1a941688d454\",
\"contents\": {\"en\": \"English Message\"},
\"filters\": [{\"field\": \"tag\", \"key\": \"id\", \"relation\": \"=\", \"value\": \"1\"}]}" \
     https://onesignal.com/api/v1/notifications
```     