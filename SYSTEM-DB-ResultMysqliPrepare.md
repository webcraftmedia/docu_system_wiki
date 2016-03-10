SYSTEM\DB\ResultMysqliPrepare
===============






* Class name: ResultMysqliPrepare
* Namespace: SYSTEM\DB
* Parent class: [SYSTEM\DB\Result](SYSTEM-DB-Result.md)





Properties
----------


### $res

    private mixed $res = NULL





* Visibility: **private**


### $meta

    private mixed $meta = NULL





* Visibility: **private**


### $binds

    private mixed $binds = array()





* Visibility: **private**


### $connection

    private mixed $connection = NULL





* Visibility: **private**


Methods
-------


### __construct

    mixed SYSTEM\DB\ResultMysqliPrepare::__construct($res, $connection)





* Visibility: **public**


#### Arguments
* $res **mixed**
* $connection **mixed**



### __destruct

    mixed SYSTEM\DB\ResultMysqliPrepare::__destruct()





* Visibility: **public**




### close

    mixed SYSTEM\DB\Result::close()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result.md)




### count

    mixed SYSTEM\DB\Result::count()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result.md)




### affectedRows

    mixed SYSTEM\DB\Result::affectedRows()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result.md)




### next

    mixed SYSTEM\DB\Result::next($object)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result.md)


#### Arguments
* $object **mixed**



### seek

    mixed SYSTEM\DB\Result::seek($row_number)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result.md)


#### Arguments
* $row_number **mixed**


