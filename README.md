# firebaseStarter
Auth Starter with Firebase

Instructions here:  http://market.ionic.io/starters/firebaseauthstarter

1- Download the zip file and move to your directory www/ or using ionic start:
```
$ ionic start [yourapp] https://github.com/ion-book/firebaseStarter
```
2- go to www/js/app.js and edit FURL
```
.constant('FURL', 'https://asfirebase.firebaseio.com/')
```
with your firebase App URL.

You need enable the option "Enable Email & Password Authentication" in your Firebase App.

3- Try.
```
$ ionic serve -b -c -s
```
