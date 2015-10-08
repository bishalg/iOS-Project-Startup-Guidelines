# iOS-Project-Startup-Guidelines
Guide on how to start a new iOS Project from very start for Swift and Objective-C

## Table Of Contents - 

## Programming Language

 Topics | Objective-C | Swift | Winner |
 Code Syntax | Unorthodox | Similar to many other OOPs languages | Swift |
| 2. | Present Development | Matured Language | Very new language just year old language | ObjC |
| 3. | Future Development | Slowly Dyeing | New Development now towards Swift. | Swift |
| 4. | Debugger / Compiler | Very mature lldb | Sometime tricky to debug | ObjC ( for now ) |

### Decision -

Swift - As Swift can use ObjC project and framework on top of it. 

## JSON Parsing

### Frameworks  - 

 [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) | [Argo](https://github.com/thoughtbot/Argo) | Winner |
| GitHub <span>Rating</span> | 6.2 k | 1.5 k | SwiftyJSON |
| <span>GitHub <span>Contributor</span></span> | 44 | 20 | SwiftyJSON |
| <span>Pros</span> | <span>Code Readability</span> | Functional Coding | SwiftyJSON |
| Cons | <span>Optional tree</span> | Complex Functional Syntax | Argo |

### Decision - 

Argo - ( TODO: ??? ) 

### Related frameworks - 

[jsonSwift](https://github.com/owensd/json-swift)

[Alamofire-SwiftJSON](https://github.com/SwiftyJSON/Alamofire-SwiftyJSON)

[JSONJoy](https://github.com/daltoniam/JSONJoy-Swift)

[JASON](https://github.com/delba/JASON)

### Info - 

[https://github.com/Wolg/awesome-swift#jsonxml-manipulation](https://github.com/Wolg/awesome-swift#jsonxml-manipulation)

[http://harlankellaway.com/blog/2015/07/05/swift-json-parsing-by-example/](http://harlankellaway.com/blog/2015/07/05/swift-json-parsing-by-example/)

[http://blog.scottlogic.com/2015/03/09/json-in-swift.html](http://blog.scottlogic.com/2015/03/09/json-in-swift.html)

## UI

### Frameworks - 

 Topics | Storyboard | XIB | Code | Result |
| 1 | Easy to create and use | *** | *** | * | SB & XIB |
| 2 | Easy to visualize flow | *** | ** | *  | SB |
| 3 | Chance of Code Conflict | High | High | Low | 

Code

 |
| 4 | Reusability | Low | Low | High | Code |
| 5 | Live Preview ( Size ) | High | High | Only for View not VC | SB & XIB |
| 6 | Live Preview of Table View Cell etc | *** | ** | * | SB |
| 7 | Modular ( Seperation ) | ** | *** | *** | Code & XIB |

### Decision - 

Mix approach of Storyboard, XIB and Code.

### Other Info - 

[http://www.raywenderlich.com/51992/storyboards-vs-nibs-vs-code-the-great-debate](http://www.raywenderlich.com/51992/storyboards-vs-nibs-vs-code-the-great-debate)

[http://www.toptal.com/ios/ios-user-interfaces-storyboards-vs-nibs-vs-custom-code](http://www.toptal.com/ios/ios-user-interfaces-storyboards-vs-nibs-vs-custom-code)

## Networking

### Frameworks - 

 Topics | [AFNetworking](https://github.com/AFNetworking/AFNetworking) | [Alamofire](https://github.com/Alamofire/Alamofire) | Winner |
| 1. | <span>GitHub</span> <span>Rating</span> | 20k | 10k | <span>AFNetworking</span> |
| 2. | <span>GitHub</span> <span>Contributor</span> | 250 | 65 | <span>AFNetworking</span> |
| 3. | Future Development | Not sure | YES | Alamofire |
| 4. | Base Language | ObjC | Swift | <span>Alamofire</span> |

### Decision - 

AFNetworking ( for now ) due to issue in Alamofire Security ( TODO: ??? )

