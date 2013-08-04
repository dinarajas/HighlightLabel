HighlightLabel
==============

Now it's easy to highlight any text in your UILabel.

##Features

  * ARC enabled.
  * Supports from iOS 4.3.
  * Change the highlight color
  * Uses `NSAttributedString`. So no performance issues.

![HighlightLabel Screenshot](https://raw.github.com/dineshrajas/HighlightLabel/master/Screenshot1.png)

![HighlightLabel Screenshot](https://raw.github.com/dineshrajas/HighlightLabel/master/Screenshot2.png)

##Dependency

  * CoreText.Framework

##Installation

Add the `Classes` folder to your project. Add `CoreText` framework to your project. HighlightLabel uses ARC. 
If you have a project that doesn't use ARC, just add the `-fobjc-arc` compiler flag to the HighlightLabel files.

##Usage

###Basic Setup

In your viewController file:<br />

```objectivec
#import "HighlightLabel.h"

// _highlightLabel is an outlet for HighlightLabel
label.text = @"Lorem ipsum dolor sit er elit lamet, consectetaur cillium adipisicing pecu, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Nam liber te conscient to factor tum poen legum odioque civiuda.";
label.highlightText = @"Lorem ipsum dolor sit er elit lamet";
label.highlightColor = [UIColor yellowColor];
```

##Enhancement

For present, It won't support the `textAlignment` for `UILabel`. Hope I will update it soon.

##Contact

Please forward your queries to me<br />
dina.raja.s@gmail.com

Fork and contribute to this project if you can. Thank you.

