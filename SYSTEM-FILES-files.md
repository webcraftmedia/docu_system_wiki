SYSTEM\FILES\files
===============






* Class name: files
* Namespace: SYSTEM\FILES





Properties
----------


### $folders

    private mixed $folders = array()





* Visibility: **private**
* This property is **static**.


Methods
-------


### registerFolder

    mixed SYSTEM\FILES\files::registerFolder($path, $cat)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $path **mixed**
* $cat **mixed**



### get

    mixed SYSTEM\FILES\files::get($cat, $id, $returnasjson)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cat **mixed**
* $id **mixed**
* $returnasjson **mixed**



### put

    mixed SYSTEM\FILES\files::put($cat, $id, $contents)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cat **mixed**
* $id **mixed**
* $contents **mixed**



### delete

    mixed SYSTEM\FILES\files::delete($cat, $id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cat **mixed**
* $id **mixed**



### rename

    mixed SYSTEM\FILES\files::rename($cat, $id, $newid)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cat **mixed**
* $id **mixed**
* $newid **mixed**



### getFolder

    mixed SYSTEM\FILES\files::getFolder($folder)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $folder **mixed**



### getURL

    mixed SYSTEM\FILES\files::getURL($cat, $id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cat **mixed**
* $id **mixed**



### file_get_contents_chunked

    mixed SYSTEM\FILES\files::file_get_contents_chunked($file, $chunk_size, $callback)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $file **mixed**
* $chunk_size **mixed**
* $callback **mixed**


