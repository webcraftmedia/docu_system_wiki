SYSTEM\DB\ResultMysqli
===============






* Class name: ResultMysqli
* Namespace: SYSTEM\DB
* Parent class: [SYSTEM\DB\Result](SYSTEM-DB-Result.md)





Properties
----------


### $res

    private mixed $res = NULL





* Visibility: **private**


### $current

    private mixed $current = NULL





* Visibility: **private**


Methods
-------


### __construct

    mixed SYSTEM\DB\ResultMysqli::__construct($res)





* Visibility: **public**


#### Arguments
* $res **mixed**



### __destruct

    mixed SYSTEM\DB\ResultMysqli::__destruct()





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


