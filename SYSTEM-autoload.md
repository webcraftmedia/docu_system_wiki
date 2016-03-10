SYSTEM\autoload
===============






* Class name: autoload
* Namespace: SYSTEM





Properties
----------


### $files

    private mixed $files = array()





* Visibility: **private**
* This property is **static**.


### $folders

    private mixed $folders = array()





* Visibility: **private**
* This property is **static**.


### $func

    private mixed $func = array()





* Visibility: **private**
* This property is **static**.


Methods
-------


### getClassFromFile

    mixed SYSTEM\autoload::getClassFromFile($file)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $file **mixed**



### getClassNamespaceFromClass

    mixed SYSTEM\autoload::getClassNamespaceFromClass($class)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $class **mixed**



### autoload_

    mixed SYSTEM\autoload::autoload_($class, $namespace)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $class **mixed**
* $namespace **mixed**



### registerFile

    mixed SYSTEM\autoload::registerFile($file, $namespace)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $file **mixed**
* $namespace **mixed**



### registerFolder

    mixed SYSTEM\autoload::registerFolder($folder, $namespace)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $folder **mixed**
* $namespace **mixed**



### registerFunc

    mixed SYSTEM\autoload::registerFunc($func, $namespace)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $func **mixed**
* $namespace **mixed**



### register_autoload

    mixed SYSTEM\autoload::register_autoload()





* Visibility: **public**
* This method is **static**.




### autoload

    mixed SYSTEM\autoload::autoload($class)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $class **mixed**



### file_extension

    mixed SYSTEM\autoload::file_extension($filename)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $filename **mixed**



### autoload_all

    mixed SYSTEM\autoload::autoload_all()





* Visibility: **public**
* This method is **static**.



