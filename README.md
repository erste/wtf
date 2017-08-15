# wtf

# how to install mysqlclient on mac

    brew unlink mariadb
    brew install mariadb-connector-c
    ln -s /usr/local/opt/mariadb-connector-c/bin/mariadb_config /usr/local/bin/mysql_config
    pip install mysqlclient
    rm /usr/local/bin/mysql_config
    brew unlink mariadb-connector-c
    brew link mariadb