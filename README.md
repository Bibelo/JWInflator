# JWInflator

## UNZIP

```
$ ./jwlibrary_unzip -h
```

Usage: ./jwlibrary_unzip <JW backup>.jwlibrary

Will simply expand to a folder containing the .jwlibrary file, the manifest.json and the userData.db.
You can then simply edit the userData.db with SQLite software.

The JW Library file will be modified, so make a backup of this file if needed.

## ZIP

```
Usage: ./jwlibrary_zip <JW folder>
```

JW folder: WITHOUT the .jwlibrary extension
               folder created by jwlibrary_deflate
               bears the name of the JW backup file without the .jwlibrary extension
               contains the .jwlibrary file, the manifest.json and the userData.db

Will simply update the existing .jwlibrary file with the modified userData.db and the manifest.json.
Will remove these last two files so make a backup if needed.

More info at [bibelo.info](https://bibelo.info/edit-content-of-jw-library-backup-files/)
