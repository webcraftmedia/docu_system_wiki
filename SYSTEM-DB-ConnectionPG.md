SYSTEM\DB\ConnectionPG
===============






* Class name: ConnectionPG
* Namespace: SYSTEM\DB
* Parent class: [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)





Properties
----------


### $connection

    private mixed $connection = NULL





* Visibility: **private**


Methods
-------


### __construct

    mixed SYSTEM\DB\ConnectionAbstr::__construct(\SYSTEM\DB\DBInfo $dbinfo)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)


#### Arguments
* $dbinfo **[SYSTEM\DB\DBInfo](SYSTEM-DB-DBInfo.md)**



### __destruct

    mixed SYSTEM\DB\ConnectionAbstr::__destruct()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)




### prepare

    mixed SYSTEM\DB\ConnectionAbstr::prepare($stmtName, $stmt, $values)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)


#### Arguments
* $stmtName **mixed**
* $stmt **mixed**
* $values **mixed**



### close

    mixed SYSTEM\DB\ConnectionAbstr::close()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)




### query

    mixed SYSTEM\DB\ConnectionAbstr::query($query)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)


#### Arguments
* $query **mixed**



### trans

    mixed SYSTEM\DB\ConnectionAbstr::trans()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)




### commit

    mixed SYSTEM\DB\ConnectionAbstr::commit()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)




### getPrepareValueType

    mixed SYSTEM\DB\ConnectionAbstr::getPrepareValueType($value)





* Visibility: **protected**
* This method is **static**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr.md)


#### Arguments
* $value **mixed**


