# Swift-notebook


* [Create Singleton in App](#create-singleton-in-app)



## Create Singleton in App

```
class TheOneAndOnlyKraken {
    static let sharedInstance = TheOneAndOnlyKraken()
    private init() {} //This prevents others from using the default '()' initializer for this class.
}

```