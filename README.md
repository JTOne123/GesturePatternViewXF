# GesturePatternViewXF
A Xamarin.Forms gesture pattern view.
This is an Android-like gesture pattern view you can use for logins.


### Setup
* Available on NuGet: https://www.nuget.org/packages/FaulandCc.XF.GesturePatternView [![NuGet](https://img.shields.io/nuget/v/FaulandCc.XF.GesturePatternView.svg?label=NuGet)](https://www.nuget.org/packages/FaulandCc.XF.GesturePatternView/)
* Install into your PCL project only.

**Platform Support**

* Xamarin.iOS, iOS 8+
* Xamarin.Android, API 15+
* Windows 10, UWP 10+


### Usage
Just add the *GesturePatternView* to your XAML.

#### Properties (all bindable)
* HorizontalTouchPoints = The number of horizontal touch points to create.
* VerticalTouchPoints = The number of vertical touch points to create.
* GesturePatternValue = The total value of the touched touch points.
* TouchPointColor = The color to use for untouched touch points.
* TouchPointHightlightTextColor = The color to use for touched touch points.
* TouchPointStrokeWidth = The stroke width of a touch point.
* TouchPointTouchedStrokeWidth = The stroke width of a touched touch point.
* TouchPointInnerCircleStrokeWidth = The stroke width of a touch point's inner circle.
* LineDrawingColor = The color to use for a drawing line.
* LineDrawingStrokeWidth = The stroke width of a drawing line.
* LineDrawnColorProperty = The color to use for a drawn line.
* LineDrawnStrokeWidth = The stroke width of a drawn line.
* Vibrate = Vibrate when touching a touch point.


#### Screenshot
![gesture pattern view](http://software.fauland.cc/wp-content/uploads/2017/10/xfgesturepatternview.png)

#### Contributions
Contributions are welcome! If you find a bug please report it and if you want a feature please report it.
If you want to contribute code please file an issue and create a branch off of the current dev branch and file a pull request.

#### License
Under MIT, see LICENSE file.

#### Note
This is my very first project here on GitHub including a NuGet package. I took the readme.md of James Montemagno's VibratePlugin as a template. Thank you!
