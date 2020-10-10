## SwiftUI Shapes
Collection of custom shapes

## Regular Polygons
<center>
<img src="Resources/regularRectangles.png"/>
</center>

```swift
Pentagon()
Hexagon()
RegularPolygon(sides: 32)
```

## Lines and Curves
<center>
<img src="Resources/lines.png"/>
</center>

```swift
QuadCurve(unitPoints: [
    UnitPoint(x: 0.1, y: 0.1),
    UnitPoint(x: 0.5, y: 0.9),
    UnitPoint(x: 0.9, y: 0.1)
])
.stroke(Color.blue, style: .init(lineWidth: 2, lineCap: .round))
.frame(height: 200)
```

## Patterns
<center>
<img src="Resources/patterns.png"/>
</center>

```swift
GridPattern(horizontalLines: 20, verticalLines: 40)
    .stroke(Color.white.opacity(0.3), style: .init(lineWidth: 1, lineCap: .round))
    .frame(height: 200)
    .background(Color.blue)
    .padding()
```

## How to use

Add this swift package to your project
```
git@github.com:swift-extensions/swiftui-shapes.git
```

For more examples open `/Examples/ShapesExamples.xcodeproj`

## Roadmap 
- Rounded regular polygons

## Code Contributions
Feel free to contribute via fork/pull request to master branch. If you want to request a feature or report a bug please start a new issue.

## Coffee Contributions
If you find this project useful please consider becoming my GitHub sponsor.
