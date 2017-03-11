# Reasons behind Angular2? 

Angular2 is not a usual language upgrade providing new features, fixes for the bugs in the previous version(like Angular 1.5 to 1.6) instead it's a complete re-write of the language from the ground.A complete re-write for the new version may not sounds good, but eventually that is the truth. Even the team knows that, re-write will create concerns on the stability of their language, upgradtion and adoption. But nothing stopped them from re-writting the language, as the reasons behind it more stronger. 

It was simply clever - building the "*The frame-work of the future*".

The word "*The frame-work of the future*" may not sounds good to every one as it really was. To get the details clearly we are going to havve a look back and walk around from "Angular1". When Angular1 was introduced in 2010, It address most of the web development issues of that time with his rich features and those made Angular a super heroic frame-work.when they built Angular1 mobile users very less and they were considered only the desktops, they shipped all the code in a single package. Importing 140k(approx size of angular1 mininfied file) size file is not a big deal when you are in desktop, because desktops will have enough memory with proper internet connection. 

But the web has been developed enormously in last 5 to 6 years and today the usage of mobile is very high, so when developing anything we have to keep eye on mobile also. In mobiles, memory is very limited, internet connectivity also poor.So importing each and every single bit is more important and also to provide better user experience we have to request resources on demand basis(Lazy- loading). As in Angularjs1 everything bundled in a single package, we have to download whole library whether its required for the application/not and we don't have frame-work support for loading resources on-demand(external plugins like "OCLazyLoad" supports lazy loading in angularjs).Today technology is further moving faster towards devices, Which doesn't have a browser like IoT's and BOTS.

In other view, if we see "Web component" is going to be the standard for future of the web development. Angularjs supports component based approach from 1.5, but it's not fully compiled with W3C guidelines for web components.


So the team decides to built a new version of framework with following things in mind
Code once, run any where - a framework that will run the code not only in desktop/mobile/browser instead it will run on devices, even which doesn't have browser. At the same time they taken all the good things from Angularjs1 and created a improved version of those(Dependency Injection, Services..) and they worked on all limitations of Angularjs1(like lazyloading, seprating packages and so on).
