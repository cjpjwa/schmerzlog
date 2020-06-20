# schmerzlog
Schmerzlog is a progressive web app (PWA) to create a simple pain diary.
A pain diary can be a helpful to find connections between your pain and special situations, medication or behaviour.
You can set values for pain intensity from 0 to 10 for each time of a day and add an optional comment.
The entries for each day are shown on the app start page. 
A report of all data can be created in CSV format.
Working sample can be found here: https://slog.cjpj.de

## Data Saving
The entered data is saved via indexedDB. 
The optional password is saved via localstorage.

## Data encryption and hashing
Optional password can be set to protect app access and to encrypt saved data (using crypto-js).
When setting a password, data is encrypted using AES, password is hashed via SHA256.
With no individual password the contact data is encrypted with a default password.

## Used Libs
- [crypto-js](https://github.com/brix/crypto-js) under [The MIT License](https://github.com/brix/crypto-js/blob/develop/LICENSE)
- [simple-app-Shell](https://github.com/cjpjwa/simple-app-shell) under [The MIT License](https://github.com/cjpjwa/simple-app-shell/blob/master/LICENSE)

## License
Schmerzlog is licensed under [The MIT License](https://github.com/cjpjwa/schmerzlog/blob/master/LICENSE)

