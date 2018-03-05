# docker-mariadb-utf8
The official MariaDB Docker image, with sane Unicode defaults.

The only change is a custom config file my.cnf to set default collation and character set to UTF-8
according to official MariaDB documentation. (Props to [MiquelAdell](https://github.com/MiquelAdell/mariadb-utf8mb4) for this solution, which this is definitely not shamelessly ripped off from, but his last build was over 2 years ago as of writing)

## Usage
See official documentation.

## Version
This package will track the latest MariaDB version by use of a Repository Link.

Current tags:
  - 10.3 (latest)
