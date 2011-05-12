### Xcode templates for Mobile Couchbase (iOS)

These templates allow you to quickly get started integrating CouchDB into your next iOS applicaiton.

### Current Status

This is the first release of the template.  It is intended as developer preview.  Your Xcode MAY crash as a result of this template. 

### Getting Started

* Quit Xcode (maybe not required, but I would to be safe)

* mkdir -p ~/Library/Developer/Xcode/Templates/

* cd ~/Library/Developer/Xcode/Templates/

* git clone https://github.com/mschoch/iOS-Couchbase-Xcode-templates.git

* Launch Xcode

* Select File > New > New Project...

* You should see a Couchbase Application group on the left hand side, then select Couchbase Window-based Application

<img src="https://github.com/mschoch/iOS-Couchbase-Xcode-templates/raw/master/doc/resources/001.png" width="400"/>

* Name your project

<img src="https://github.com/mschoch/iOS-Couchbase-Xcode-templates/raw/master/doc/resources/002.png" width="400"/>

* Tell Xcode where to store the files

<img src="https://github.com/mschoch/iOS-Couchbase-Xcode-templates/raw/master/doc/resources/003.png" width="400"/>

* Now you should see a project that looks like this

<img src="https://github.com/mschoch/iOS-Couchbase-Xcode-templates/raw/master/doc/resources/004.png" width="400"/>

* If you select iPhone 4.3 Simulator and press the Run button you should see

<img src="https://github.com/mschoch/iOS-Couchbase-Xcode-templates/raw/master/doc/resources/005.png" width="400"/>

* In the console, you should see

<img src="https://github.com/mschoch/iOS-Couchbase-Xcode-templates/raw/master/doc/resources/006.png" width="400"/>

### Known Issues

* Linkage to libraries is a bit fragile, mainly do to lack of documentation around Xcode 4 project templates

### Future Plans

* Refactor the layout of files to make it easier to support multiple templates (take advantage of the inheritance model that these templates support)
* Add support for a few more types of templates (low priority, but should be straighforward to support all the defaults Apple ships with)
* Add proper support for linking to the libraries (need better documentation around Xcode 4 project template files, doesn't seem community has figured it all out yet, see THANKS below)
* Integrate this with main Mobile Couchbase repo
* Possibly create simple installer to streamline this further

### Thanks

This work was only possible because of the information I was able to find at these sites:

* http://blog.boreal-kiss.net/2011/03/11/a-minimal-project-template-for-xcode-4/
* http://snipt.net/yonishin/about-xcode-4-project-template
* https://github.com/cocos2d/cocos2d-iphone/tree/develop/templates/Xcode4_templates

And of course the Mobile Couchbase project https://github.com/couchbaselabs/iOS-Couchbase
