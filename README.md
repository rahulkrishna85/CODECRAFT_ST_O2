# CODECRAFT_ST_O2
CROSSBROWSER TESTING
Application Under Test
*NAME:SHOPLANE-BY_LASSIE
*URL:https://shoplane-by-lassie.netlify.app/
*TEST TYPE:Manual Cross Browser Testing
-----

#Test Environment
### Browsers
-Chrome(Latest)
-FireFox(Latest)
-Edge(latst)
-Safari(Latest)

### Devices
-Desktop(window/macOS)
-Tablet(ipad)
-Mobile(Android/ios)

### Test Scope
-UI layout consistency
-Broken Links
-Functional behaviour
-Responsiveness

--------------------------------
### LAYOUT & UI ISSUES ###
   BROWSER / DEVICES  |       ISSUE                    |  STATUS  |
Chrome(desktop)         No issue                          pass
Firefox(Desktop)        Minor Front Rendering issue       fail 
Safari(desktop)         Header padding issue              fail
Tablet(ios)             Footer overlapping content        fail
Mobile(android/ios)     Slight spacing issue              pass

** ISSUE DETAILS**
-product cards appear slightly misaligned in safari.
-Font weight varies slightly in fire fox

--------------------------------

### BROKEN LINKS ###
   PAGE     |  STATUS  |
Header links   Working
Footer links   Working
Product links  Working

** RESULT**
No broken links detected.

--------------------------------

### FUNCTIONAL BEHAVIOUR ###
   FEATURE          |  RESULT  |
   Navigation links   pass
   Product click      pass
   image slider       pass
   cart button        pass

   ** Observation **
   All interactive elements work consistently across browsers.
   
--------------------------------
### RESPOSIVENESS(DEVICE TESTING) ###
DEVICE       |  RESULT  |
Desktop         pass
Tablet          pass
Mobile          minor issue

** Issue Details**
-On mobile view,some product images appear slightly compressed

--------------------------------

## FINDINGS
During cross_browser and cross_device testing,following issue were found:
-Minor front rendering difference in ** firefox**
-Slight spacing issue in product cards on ** safari(tab/mobile)
-product image looks slight compressed on ** mobile devices **

## No broken links or major functional issues were found.


