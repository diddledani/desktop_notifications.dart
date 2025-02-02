# Changelog

## 0.6.1

* Fix incorrect data type used in NotificationHint.location().
* Replace Uint8List in NotificationHint.imageData() with Iterable<int>.
* Fix specification link in README.

## 0.6.0

* Update to dbus 0.6.

## 0.5.0

* Update to dbus 0.5.
* Rename test file so can just run 'dart test'.

## 0.4.0

* Update to dbus 0.4

## 0.3.0

* Rename NotificationClient to NotificationsClient (was a typo).
* Replace action and closed callbacks with futures.
* Fix invalid default value for replacesId.
* Make constructors constant.
* Add regression tests.

## 0.2.2

* Bump dbus dependency to avoid a signal subscription bug.

## 0.2.1

* Make the DBusClient parameter optional.
* Code tidy ups to pass dart analyze in 1.12 final release.

## 0.2.0

* Add null safety support

## 0.1.0

* Initial release
