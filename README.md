# LiquidLoaderSwiftUI

A SwiftUI wrapper around [LiquidLoader](https://github.com/yoavlt/LiquidLoader)


## Get

### For Xcode Projects

File > Swift Packages > Add Package Dependency: https://github.com/MahdiBND/LiquidLoaderSwiftUI

## GrowLine
![GrowLine](https://github.com/yoavlt/LiquidLoader/blob/master/Demo/grow-line.gif?raw=true)

## Usage

First import `LoadingView`

Embed your view content in a `ZStack` with the Loader as the last element.

```swift
ZStack {

	ScrollView {
		//...
	}
	
	Loading(background: .green, tint: .cyan)
}
```

## Credits

* [**Takuma Yoshida**](https://github.com/yoavlt) - *Initial work*
