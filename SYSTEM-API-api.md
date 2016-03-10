SYSTEM\API\api
===============






* Class name: api
* Namespace: SYSTEM\API



Constants
----------


### ROOT_PARENTID

    const ROOT_PARENTID = -1





### DEFAULT_GROUP

    const DEFAULT_GROUP = 0





### DEFAULT_STRICT

    const DEFAULT_STRICT = true





### DEFAULT_DEFAULT

    const DEFAULT_DEFAULT = false







Methods
-------


### run

    mixed SYSTEM\API\api::run($verifyclassname, $apiclassname, $params, $group, $strict, $default)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $verifyclassname **mixed**
* $apiclassname **mixed**
* $params **mixed**
* $group **mixed**
* $strict **mixed**
* $default **mixed**



### getApiTree

    mixed SYSTEM\API\api::getApiTree($group)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $group **mixed**



### do_statics

    mixed SYSTEM\API\api::do_statics($params, $tree, $apiclassname, $verifyclassname, $default)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $params **mixed**
* $tree **mixed**
* $apiclassname **mixed**
* $verifyclassname **mixed**
* $default **mixed**



### do_default

    mixed SYSTEM\API\api::do_default($default, $apiclassname, $call_funcname)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $default **mixed**
* $apiclassname **mixed**
* $call_funcname **mixed**



### do_strict

    mixed SYSTEM\API\api::do_strict($strict, $params, $statics, $commands, $parameters, $parameters_opt)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $strict **mixed**
* $params **mixed**
* $statics **mixed**
* $commands **mixed**
* $parameters **mixed**
* $parameters_opt **mixed**



### do_commands

    mixed SYSTEM\API\api::do_commands($params, $tree)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $params **mixed**
* $tree **mixed**



### do_parameters

    mixed SYSTEM\API\api::do_parameters($params, $tree, $parentid, $lastcommandvalue, $verifyclassname)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $params **mixed**
* $tree **mixed**
* $parentid **mixed**
* $lastcommandvalue **mixed**
* $verifyclassname **mixed**



### do_parameters_opt

    mixed SYSTEM\API\api::do_parameters_opt($params, $tree, $parentid, $lastcommandvalue, $verifyclassname)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $params **mixed**
* $tree **mixed**
* $parentid **mixed**
* $lastcommandvalue **mixed**
* $verifyclassname **mixed**



### do_func_name

    mixed SYSTEM\API\api::do_func_name($commands)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $commands **mixed**



### do_func_params

    mixed SYSTEM\API\api::do_func_params($parameters, $parameters_opt)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $parameters **mixed**
* $parameters_opt **mixed**


