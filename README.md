This is an extension for Drive Badger. It provides a sample `filevault.keys` file, containing a list of Apple FileVault encryption keys.

Drive Badger is able to automatically detect and decrypt FileVault-encrypted APFS partitions, using both user passwords and recovery keys.
It doesn't support recovery via iCloud, or HFS+ encryption.

### Installing

Do NOT clone this repository directly. Instead, **fork it** (possibly multiple times), or create similar repositories from stratch
(empty repository with just `filevault.keys` file is enough).

Next, clone each of them as `/opt/drivebadger/config/keys-filevault-yourchosenname` local directory on your Drive Badger persistent partition.

This way, you are able to update all cloned repositories in the future by a single command `/opt/drivebadger/update.sh`.

### More information

- [Drive Badger main repository](https://github.com/drivebadger/drivebadger)
- [Drive Badger wiki](https://github.com/drivebadger/drivebadger/wiki)
- [description, how configuration repositories work](https://github.com/drivebadger/drivebadger/wiki/Configuration-repositories)
