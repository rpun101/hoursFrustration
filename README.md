# Hours of Frustration #
These things took me more than hour to figure it out. Wise man said, learn from your failure. I am keeping this log so next time, i will save a hour of life.

## Hour ##

1. SQL Server
    + SSMS(SQL Management Tool) is different than SQL Server. They are installed separately.
    + Check `SQL Server` services, if it is running for Database Engine.
    + If any package is not found, usually it is because of dependency, needs to uninstall previous packages `C++ 2005 Redistrubution` or Uninstall previous versions if any.
    + Put `*.bak` file in Backup folder and restore it to get the database. [sample database in Github](https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks)