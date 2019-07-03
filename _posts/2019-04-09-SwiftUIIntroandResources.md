---
layout: post
title: iOS - SwiftUI
subtitle: Intro and Resouces
show-avatar: false
---
## SwiftUI
In the recent WWDC19 apple introduced a new and very modern approach of building UIs in the apple ecosystem which could drastically change the way in which UI development is done in both iOS and macOS along with tvOS and watchOS and the new iPadOS!.Together with the Project Catalyst(Marzipan),which helps in porting iPad applications to macOS applications with little effort,SwiftUI is really a game changer.

It could make creating UI in apple ecosystem a lot more easier, structural and declarative. It introduced a new *View* Protocol which helps in implementing new controls or components. The new approach adopts *protocol oriented programming* and *value semantics* which is the most recommended way of data and state management by apple engineers.Now all your view are value types and thus state management becomes a lot more easier.Basically SwiftUI embraces the React and Flutter way of creating UIs and is a good sign of apple trying to create a better platform for developers and being in sync all other general developments in the industry.

Practically speaking SwiftUI makes the UI code of your application significantly smaller ,interactive and fun to develop. It also brings the storyboard vs programmatically create  UI debate to an end.I t might also make the UIKit(iOS),AppKit(macOS),UIKit for mac(introduced for supporting Project Catalyst) obsolete in the near future.But in the short term SwiftUI won't completely replace legacy methods since it supports only from iOS 13 and latest macOS 10.15.

The possibilities and advantages of SwiftUI is really astounding as I have seen a lot of wide application ideas from the iOS community within the short term SwiftUI was announced. It includes 

 - Faster development of  UI , smaller,more structured, readable,easy to use UI code.
 - Better animations,which are easy to implement
 - Better coupling of animations
 - Animations can automatically sync up with gestures which makes UI more fluid
 - Reuse of same code across multiple apple platforms
 - Custom compenents are easier to create and reuse and share among developers.
 - Also the underlying platform of SwiftUI :DSL(Domain specific languages) opens up a lot of possibilities ,I have seen libraries which could use swift to generate html code etc
 - Another interesting idea,I had seen was *network based UI code*,which is a very huge possibility and maybe controversial at it maybe can bypass apple review.
 - Previews in Xcode,which brings together stroryboard like approach and code based approach,brings an interactive and real time visual two base binding between code and UI preview. 
