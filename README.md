# ionicPushNotifFirebase
Working code. Tutorial followed: http://tphangout.com/ionic-2-push-notifications-with-firebase/

## Screencast of the Tutorial: https://www.youtube.com/watch?v=sUjQ3G17T80

## Important points
* New command syntax: 
> ionic cordova plugin add phonegap-plugin-push --variable SENDER_ID=XXXXXXXXX

* Download _google-services.json_ from firebase dashboard and put it in root app folder, also under app/src/folder

* Make sure 'widget-id' in config.xml is sa me as package-name in google-services.json

## Troubleshooting links for errors faced:
https://stackoverflow.com/questions/43933459/declaring-custom-clean-task-when-using-the-standard-gradle-lifecycle-plugins-i

https://stackoverflow.com/questions/42065625/ionic-no-matching-client-found-for-package-name-org-apache-cordova-firebase/45783502#45783502

https://stackoverflow.com/questions/43933459/declaring-custom-clean-task-when-using-the-standard-gradle-lifecycle-plugins-i/44115159#44115159

https://stackoverflow.com/questions/25994163/could-not-resolve-all-dependencies-for-configuration-classpath/48223385#48223385
