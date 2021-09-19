[Previous Section: Reading](1_READING.md)

# Module 4: Exercise 1

## Collage (Animated)

![Lorna Mills](images/Lorna_Mills.gif)

Artwork by [Lorna Mills](http://www.digitalmediatree.com/sallymckay/LornaMillsImageDump/).

## Instructions

Modify your collage from Module 3 to include smooth animated motion.

Develop a **clear idea** about how motion is utilized before writing the code. There are **three basic types of motion** you'll want to think about: **linear**, **random**,  **circular**. If you can think of other types of motion, you are welcome to expand on those three ideas. Remove the feature that generates a new collage each second  and integrate your new motion at 60 frames per second (delete  `frameRate(1)` from the code).

**Add a substantial comment at the top of the code that explains your idea for the workshop and what kind of compositional strategies you used.**

## Example Motion Code

**Note:** The code below are complete Playgrounds. You may remove the `PlaygroundSupport` and the `PlaygroundPage` calls if you want to use them in an app.

### Linear Motion

```swift
import SwiftProcessing
import PlaygroundSupport
import UIKit

class MySketch: Sketch, SketchDelegate {
    
    var count = 0.0
    
    func setup() {
        stroke(255)
        strokeWeight(1)
        fill(0, 0)
    }
    
    func draw() {
        background(0)
        // millis() is the number of milliseconds that have passed since the Sketch started.
        
        // % is the modulus operator. It sets a maximum limit to the count variable. Once it gets to 300, it starts over.
        count = (millis() / 100) % 300
        line(100, 100, 400, 400)
        rectMode(.center)
        rect(100 + count, 100 + count, 20, 20)
    }
}

PlaygroundPage.current.needsIndefiniteExecution = true
PlaygroundPage.current.setLiveView(MySketch())
```

### Random Motion

```swift
import SwiftProcessing
import PlaygroundSupport
import UIKit

class MySketch: Sketch, SketchDelegate {
    
    var randomX = 0.0
    var randomY = 0.0
    
    func setup() {
        background(0)
        strokeWeight(1)
        rectMode(.center)
    }
    
    func draw() {
        // Draw semi-transparent "background"
        background(0,25)
        
        // random values for rectangle position
        randomX = random(width)
        randomY = random(height)
        
        // rectangles
        noFill()
        stroke(255)
        rect(randomX, randomY, 25, 25)
    }
}

PlaygroundPage.current.needsIndefiniteExecution = true
PlaygroundPage.current.setLiveView(MySketch())

```

### Circular Motion

```swift
import SwiftProcessing
import PlaygroundSupport
import UIKit

class MySketch: Sketch, SketchDelegate {
    
    var constant = 250;
    var angle = 0.05;
    var scalar = 100;
    var speed = 0.025;
    
    func setup() {
        noFill()
        stroke(255)
    }
    
    func draw() {
        background(0)
        
        var x = constant + sin(angle) * scalar
        var y = constant + cos(angle) * scalar
        
        ellipse(x, y, 25, 25)
        ellipse(250, 250, 200, 200)
        
        angle = angle + speed
    }
}
```

## Student Examples

The following are student examples used with permission:

Coming soon.

## Rubric

| Criteria                                                     | Points |
| ------------------------------------------------------------ | ------ |
| Your collage creates itself from a pool of 10 images (at least). | 5 pts  |
| The `random()` function is used.                             | 5 pts  |
| Collage has a clear compositional logic.Code has a clear, descriptive header. Images are not just random on the canvas. | 5 pts  |
| `frameRate(1)` has been deleted and the different types of motion have been incorporated. | 5 pts  |
| Code is helpfully commented for your future self.            | 5 pts  |

[Next Section: Exercise 2](3_EXERCISE.md)

