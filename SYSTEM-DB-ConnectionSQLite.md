SYSTEM\DB\ConnectionSQLite
===============






* Class name: ConnectionSQLite
* Namespace: SYSTEM\DB
* Parent class: [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)





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
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)


#### Arguments
* $dbinfo **[SYSTEM\DB\DBInfo](SYSTEM-DB-DBInfo)**



### __destruct

    mixed SYSTEM\DB\ConnectionAbstr::__destruct()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)




### prepare

    mixed SYSTEM\DB\ConnectionAbstr::prepare($stmtName, $stmt, $values)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)


#### Arguments
* $stmtName **mixed**
* $stmt **mixed**
* $values **mixed**



### close

    mixed SYSTEM\DB\ConnectionAbstr::close()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)




### query

    mixed SYSTEM\DB\ConnectionAbstr::query($query)





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)


#### Arguments
* $query **mixed**



### exec

    mixed SYSTEM\DB\ConnectionSQLite::exec($query)





* Visibility: **public**


#### Arguments
* $query **mixed**



### commit

    mixed SYSTEM\DB\ConnectionAbstr::commit()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)




### trans

    mixed SYSTEM\DB\ConnectionAbstr::trans()





* Visibility: **public**
* This method is **abstract**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)




### getPrepareValueType

    mixed SYSTEM\DB\ConnectionAbstr::getPrepareValueType($value)





* Visibility: **protected**
* This method is **static**.
* This method is defined by [SYSTEM\DB\ConnectionAbstr](SYSTEM-DB-ConnectionAbstr)


#### Arguments
* $value **mixed**


