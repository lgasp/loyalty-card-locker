# Loyalty Card Locker
[![Build Status](https://travis-ci.org/brarcher/loyalty-card-locker.svg?branch=master)](https://travis-ci.org/brarcher/loyalty-card-locker)

[![F-Droid](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Get_it_on_F-Droid.svg/160px-Get_it_on_F-Droid.svg.png)](https://f-droid.org/repository/browse/?fdid=protect.card_locker "Loyalty Card Locker on F-Droid")


Stores all of your store loyalty cards on your phone, removing the need to carry them around.  Currently the following barcode types are supported:

- AZTEC
- CODABAR
- CODE_39
- CODE_128
- DATA_MATRIX
- EAN_8
- EAN_13
- ITF
- PDF_417
- QR_CODE
- UPC_A

If there is any interest in improving this project, kindly submit a pull request with
proposed changes.

# Screenshots

[<img src="" width=250>]()
[<img src="" width=250>]()
[<img src="" width=250>]()

[<img src="" width=250>]()
[<img src="" width=250>]()

Main screen, listing all loyalty cards:

![screenshot_2016-08-28-15-16-12](https://cloud.githubusercontent.com/assets/5264535/18036233/32fae9a6-6d33-11e6-81e4-55ba60e83d9b.png)

Selecting a card brings up its barcode:

![screenshot_2016-08-28-15-14-00](https://cloud.githubusercontent.com/assets/5264535/18036246/7ee5c7f0-6d33-11e6-90cf-d2b3ca5a94c7.png)

When adding a new card one may choose to capture it via the camera or manually entering the barcode:

![screenshot_2016-08-28-15-17-26](https://cloud.githubusercontent.com/assets/5264535/18036258/bb19562e-6d33-11e6-856e-740e8785ad71.png)

If adding a card by typing it in, simply select the generated barcode which looks like the loyalty card:

![screenshot_2016-08-28-15-16-41](https://cloud.githubusercontent.com/assets/5264535/18036269/0202baf8-6d34-11e6-9c17-449d5b348738.png)


# Building

To build, use the gradle wrapper scripts provided in the top level directory of the project. The following will
compile the application and run all unit tests:

GNU/Linux, OSX, UNIX:
```
./gradlew build
```

Windows:
```
./gradlew.bat build
```

# Thanks

App icon originals by [Freepik](https://www.flaticon.com) and distributed under the [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) license,
and formatted using [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/index.html).
