SYSTEM\SECURITY\Security
===============






* Class name: Security
* Namespace: SYSTEM\SECURITY



Constants
----------


### FAIL

    const FAIL = false





### OK

    const OK = true







Methods
-------


### create

    mixed SYSTEM\SECURITY\Security::create($username, $password, $email, $locale, $advancedResult, $checkAvailable)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $username **mixed**
* $password **mixed**
* $email **mixed**
* $locale **mixed**
* $advancedResult **mixed**
* $checkAvailable **mixed**



### changePassword

    mixed SYSTEM\SECURITY\Security::changePassword($username, $password_sha_old, $password_sha_new)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $username **mixed**
* $password_sha_old **mixed**
* $password_sha_new **mixed**



### login

    mixed SYSTEM\SECURITY\Security::login($username, $password_sha, $password_md5, $locale, $advancedResult, $password_sha_new)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $username **mixed**
* $password_sha **mixed**
* $password_md5 **mixed**
* $locale **mixed**
* $advancedResult **mixed**
* $password_sha_new **mixed**



### getUser

    mixed SYSTEM\SECURITY\Security::getUser()





* Visibility: **public**
* This method is **static**.




### available

    mixed SYSTEM\SECURITY\Security::available($username)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $username **mixed**



### check

    mixed SYSTEM\SECURITY\Security::check($rightid)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $rightid **mixed**



### logout

    mixed SYSTEM\SECURITY\Security::logout()





* Visibility: **public**
* This method is **static**.




### save

    mixed SYSTEM\SECURITY\Security::save($key, $value)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**
* $value **mixed**



### load

    mixed SYSTEM\SECURITY\Security::load($key)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $key **mixed**



### isLoggedIn

    mixed SYSTEM\SECURITY\Security::isLoggedIn()





* Visibility: **public**
* This method is **static**.




### startSession

    mixed SYSTEM\SECURITY\Security::startSession()





* Visibility: **protected**
* This method is **static**.



