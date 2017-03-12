# Motivations of Angular2? 

Angular2 is not a usual language upgrade providing new features, fixes for the bugs in the previous version(like Angular 1.5 to 1.6) instead it's a complete re-write of the language from the ground.So, you might be wondering: Why make such a big jump to 2.0 and why so many breaking changes?.We will take a few moments to talk about some of the high level motivations for the changes.

## *Performance*
AngularJS was first created, almost six years ago,It was more targeted for designers to quickly build persistent html forms. But over time it has changed to accommodate a variety of scenarios and developers have picked it up and used it to build more and more complex applications. The Angular 1.x team has worked over the years to make incremental changes to the design, allowing it to continue to be relevant as the needs of modern web applications have changed. However, there are hard limits on the improvements that can be made, due to the original design. In order to fix those problems, new strategies are needed.

## *Mobile*
When Angular1 was introduced in 2010, It address most of the web development issues of that time with his rich features and those made Angular a super heroic frame-work. In 2010, the usage of mobile was very less and so they considered only the desktops for designing the language and shipped the whole source in a single package, As importing 140k(approx size of angular1 mininfied file) size file is not a big deal when you are in desktop, because desktops will have enough memory with proper internet connection. But in mobiles, memory is very limited and internet connectivity also poor.So for supports mobiles the frame-work needs to be more efficient and has to load resources on-demand for better user experiences. Due to the frame design there is no built-in support of on-demand(lasy load) resource load in Angularjs,(external plugins like "OCLazyLoad" supports lazy loading in angularjs with some limitations).Today technology is further moving faster towards devices which doesn't have a browser, Like IoT's and BOTS.

## *Changes in Web*
In the last five years, the web has changed significantly. For example, five years ago it was almost impossible to build a proper cross-browser site without help from something like jQuery. However, today's browsers are not only more consistent in their DOM implementations, but these implementations are faster and offer new features for application frameworks like service workers, support to ES6 features.

### *Web Components*
Web components are current trend and future of the web development,The term Web Components usually refers to a collection of four related W3C specifications:

**Custom Elements** - Enables the extension of HTML through custom tags.

**HTML Imports** - Enables packaging of various resources (HTML, CSS, JS, etc.).

**Template Element** - Enables the inclusion of inert HTML in a document.

**Shadow DOM** - Enables encapsulation of DOM and CSS.

By combining these four capabilities web developers can create declarative components (Custom Elements) which are fully encapsulated (Shadow DOM). These components can describe their own views (Template Element) with behaviours and can be easily packaged for distribution to other developers (HTML Imports). Angularjs supports component based approach from 1.5, but it's not fully compiled with W3C guidelines for web components.

## *More open*
The features in angular like "Dependency Injection" are very great and common for any web framework/libraries, but If you want to these Angularjs features alone with any other frame-works, it's possible.

## *Ease of Learn*
Due to the extensive features and different style of syntax Angularjs is not easy to learn. E.g. "ng-click =(...)" instead of native click event bind syntax "click = (...)". Similar to this developer has to remember many custom directives and syntax 
which specific to angular for developing apps.

All the above things are pushed the team to write the language from scratch. 
