# NotifyMe

It's a simple google FCM based app to receive notifications.

you need to create a Project in Google Console for FCM ( https://console.firebase.google.com/ ) & add android app com.xenum.notifyme to receive the notification.

Details:

After creating a new fcm token (first time startup/startup after cache clearing), this app tries to POST the fcm_token to an api (http://192.168.1.102:8000/users/insert/)

this api is written in Django framework to send the notifications using fcm-django package (http://fcm-django.readthedocs.io/en/latest/)

