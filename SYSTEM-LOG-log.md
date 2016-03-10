SYSTEM\LOG\log
===============






* Class name: log
* Namespace: SYSTEM\LOG



Constants
----------


### HANDLER_FUNC_CALL

    const HANDLER_FUNC_CALL = 'CALL'





Properties
----------


### $handlers

    private mixed $handlers = array()





* Visibility: **private**
* This property is **static**.


Methods
-------


### registerHandler

    mixed SYSTEM\LOG\log::registerHandler($handler)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $handler **mixed**



### call_handlers

    mixed SYSTEM\LOG\log::call_handlers(\Exception $E, $thrown)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $E **Exception**
* $thrown **mixed**



### __exception_handler

    mixed SYSTEM\LOG\log::__exception_handler(\Exception $E, $thrown)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $E **Exception**
* $thrown **mixed**



### __error_handler

    mixed SYSTEM\LOG\log::__error_handler($code, $message, $file, $line, $thrown)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $code **mixed**
* $message **mixed**
* $file **mixed**
* $line **mixed**
* $thrown **mixed**



### __shutdown_handler

    mixed SYSTEM\LOG\log::__shutdown_handler($thrown)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $thrown **mixed**



### __fatal_error_handler

    mixed SYSTEM\LOG\log::__fatal_error_handler($bufferContent, $thrown)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $bufferContent **mixed**
* $thrown **mixed**


