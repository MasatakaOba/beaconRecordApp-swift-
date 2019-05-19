# beaconRecordApp-swift-
This app is for iOS and that automatically record the signal of specific ibeacon when you entere the region.

`Caution!`
This app is mainly consists of two langage, Swift and PHP.
Another code(PHP) is here
https://github.com/MasatakaOba/beaconRecordApp-PHP-

Flow image: MySql<->PHP<->swift

This repository is a part of `beacon recorder app` and connect swift to PHP.

Please take a look if you can read Japanese!
https://qiita.com/takachan_coding/items/827e5be4c7670d3530ed

# Dependency
- PHP 7.1
- Swift 4
- MySql 5.6.23

# Setup
- Upload those PHP files to the server which you like and set the details to connect to MySql (api/recordbeacon.php)
- Prepare a beacon transmitter or an alternative
- Install iOS App
https://github.com/MasatakaOba/beaconRecordApp-swift-
- Allow the permission of location information on this App
- ibeacon on, off, on, off...
- Oh! I made it! (please check your MySql)

# Usage
Only you have to do is to install this App and allow permittion of location information.
When you enter the region of specific ibeacon, App will record "1" on MySql automatically. 
And When you leave the region, App will record "0" on MySql automatically as well.

# License
This software is released under the MIT License, see LICENSE.

# Authors
Masataka Oba

# References
- https://www.simplifiedios.net/swift-php-mysql-tutorial/
- https://qiita.com/egplnt/items/b9deefa85992bdad356f
