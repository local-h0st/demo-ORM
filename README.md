# EZ ORM - A Python-Sqlite ORM Framework
## database structure:
```commandline
database:<in memory>
    |---- table:user
    |           |---- colunm:id<primary key>
    |           |---- column:username
    |---- table:comment
                |---- column:id<primary key>
                |---- column:user_comments
                |---- column:belongs_to_whom
```

## TODO
* insert没写完
* 一堆没写