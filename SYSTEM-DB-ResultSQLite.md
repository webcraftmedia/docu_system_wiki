SYSTEM\DB\ResultSQLite
===============






* Class name: ResultSQLite
* Namespace: SYSTEM\DB
* Parent class: [SYSTEM\DB\Result](SYSTEM-DB-Result)





Properties
----------


### $res

    private mixed $res = NULL





* Visibility: **private**


### $stmt

    private mixed $stmt = NULL





* Visibility: **private**


### $current

    private mixed $current = NULL





* Visibility: **private**


Methods
-------


### __construct

    mixed SYSTEM\DB\ResultSQLite::__construct($res, $stmt)





* Visibility: **public**


#### Arguments
* $res **mixed**
* $stmt **mixed**



### __destruct

    mixed SYSTEM\DB\ResultSQLite::__destruct()





* Visibility: **public**




### close

    mixed SYSTEM\DB\Result::close()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result)




### count

    mixed SYSTEM\DB\Result::count()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result)




### affectedRows

    mixed SYSTEM\DB\Result::affectedRows()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result)




### next

    mixed SYSTEM\DB\Result::next($object)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result)


#### Arguments
* $object **mixed**



### seek

    mixed SYSTEM\DB\Result::seek($row_number)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\Result](SYSTEM-DB-Result)


#### Arguments
* $row_number **mixed**


