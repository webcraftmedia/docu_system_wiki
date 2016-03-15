SYSTEM\LOG\JsonResult
===============






* Class name: JsonResult
* Namespace: SYSTEM\LOG
* Parent class: [SYSTEM\LOG\AbstractResult](SYSTEM-LOG-AbstractResult)



Constants
----------


### JSONRESULT_OK

    const JSONRESULT_OK = true





### JSONRESULT_ERROR

    const JSONRESULT_ERROR = false







Methods
-------


### toString

    mixed SYSTEM\LOG\AbstractResult::toString($json_array, $status, $start_time)





* Visibility: **public**
* This method is **static**.
* This method is defined by [SYSTEM\LOG\AbstractResult](SYSTEM-LOG-AbstractResult)


#### Arguments
* $json_array **mixed**
* $status **mixed**
* $start_time **mixed**



### error

    mixed SYSTEM\LOG\AbstractResult::error(\Exception $e)





* Visibility: **public**
* This method is **static**.
* This method is defined by [SYSTEM\LOG\AbstractResult](SYSTEM-LOG-AbstractResult)


#### Arguments
* $e **Exception**



### ok

    mixed SYSTEM\LOG\AbstractResult::ok()





* Visibility: **public**
* This method is **static**.
* This method is defined by [SYSTEM\LOG\AbstractResult](SYSTEM-LOG-AbstractResult)




### fail

    mixed SYSTEM\LOG\JsonResult::fail()





* Visibility: **public**
* This method is **static**.



