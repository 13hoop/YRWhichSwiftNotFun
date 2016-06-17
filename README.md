# YRWhichSwiftNotFun


__which way is stupid more?__
```objective-c
  + (void)foo: (ClassType<OneDelegate, TwoDelegate> *) param{ 
  }
```

```swift
  class func foo<T : ClassType where T:OneDelegate, T: TwoDelegate> (outName nameParam: T) {
  }
```
