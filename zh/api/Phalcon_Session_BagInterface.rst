Interface **Phalcon\\Session\\BagInterface**
============================================

Phalcon\\Session\\BagInterface initializer


Methods
---------

abstract public  **initialize** ()

Initializes the session bag. This method must not be called directly, the class calls it when its internal data is accesed



abstract public  **destroy** ()

Destroyes the session bag



abstract public  **__set** (*string* $property, *string* $value)

Setter of values



abstract public *string*  **__get** (*string* $property)

Getter of values



abstract public *boolean*  **__isset** (*string* $property)

Isset property



