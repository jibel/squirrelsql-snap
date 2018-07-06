# squirrelsql-snap

This is the `snapcraft.yaml` file to build the snap package of SQuirreL SQL.

In addition to the upstream distribution of SQuirreL SQL, this package includes
the JDBC drivers for MySQL, PostgreSQL and SQLite. The corresponding plugins
have been enabled.

## How to build the package
Download a squirrel-sql jar file from [SQuirreL SQL website](http://www.squirrelsql.org/#installation)
in the same directory than the file `snapcraft.yaml`.

Then run the command:
```
$ snapcraft
```

## Known Issues
Printing from a java app is not working and printing is disabled.

## Contact Information
If you have a problem with the packaging as a snap don't hesitate to contact
me. If it's an issue with the software itselft please contact the upstream
developer.

Thanks.
