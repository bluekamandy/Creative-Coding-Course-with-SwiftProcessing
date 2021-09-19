# Creative Coding with Swift

Created by Prof. Masood Kamandy of Pasadena City College and the University of California Santa Barbara

## Introduction

Welcome to Creative Coding with Swift! This course is a free and open-source course developed by Masood Kamandy for students at Pasadena City College and the University of California Santa Barbara.

Creative Coding is a way of learning how to program by creating visual art with computer graphics. It's an umbrella term that encompasses many different approaches to using **code as a medium for art**. You'll hear words like **generative** and **procedural** a lot. One way of defining looking at it is that we will be making art by writing instructions for a computer to follow and sometimes we'll introduce randomness to make the outcomes varied and unknown.

There is a long history and many approaches to using code to create art. The goal of this course is to help you find your own approach and perspective through hands-on practice.

You can engage in creative coding through many different languages. There are creative coding frameworks written in Java, JavaScript, Python, C++, Rust, and Swift to name just a few. In this course we'll be using the Swift-flavored version of Processing called SwiftProcessing.

## Table of Contents

- [Hardware Requrements](#Hardware-Requrements)
- [Software Requirements](#Software-Requirements)
- [SwiftProcessing Templates and Framework Links](#SwiftProcessing-Templates-and-Framework-Links)
- [Textbooks](#Textbooks)
- [Recommended Resources](#Recommended-Resources)
  - [Code As Art Resources](#Code-As-Art-Resources)
  - [SwiftProcessing Resources](#SwiftProcessing-Resources)
  - [Swift Resources](#Swift-Resources)
  - [Processing Resources](#Processing-Resources)
- [Course Content Overview and Schedule](#Course-Content-Overview-and-Schedule)
  - [16-Week Course](#16-Week-Course)
  - [10-Week Course](#10-Week-Course)
- [Inclusion Statement](#Inclusion-Statement)
- [Code of Conduct](#Code-of-Conduct)
- [Course Grade Breakdown](#Course-Grade-Breakdown)
- [Acknowledgements](#Acknowledgements)
- [Corrections](#Corrections)
- [License](#License)

## Hardware Requrements

To develop code in this course you'll need a macOS computer that can run the latest version of Apple's Xcode development environment. The latest version of Xcode runs on macOS Big Sur, which has the following system requirements:

- MacBook (2015 or later)
- MacBook Air (2013 or later)
- MacBook Pro (Late 2013 or later)
- Mac mini (2014 or later)
- iMac (2014 or later)
- iMac Pro (2017 or later)
- Mac Pro (2013 or later)

([Source](https://support.apple.com/kb/sp833?locale=en_US))

[Table of Contents](#Table-of-Contents)

## Software Requirements

1. [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)

## SwiftProcessing Templates and Framework Links

For each assignment in this course, I recommend downloading a new **[Empty App Template](https://github.com/masoodkamandy/Swift-Processing-Template-w-Playground/archive/refs/heads/main.zip)** and renaming the outside folder to the title of your exercise or project for safe keeping. This template has everything you need to complete the course:

![A screenshot showing the user interface of Xcode. Within the navigation pane several files are outlined. First is the SwiftProcessing.playground file, which is an empty Playground for prototyping. Second is the Sketch.swift file which is for app development. Last is the Playgrounds folder which contains the SwiftProcessing Playground Textbook.](images/Template.png)

### Additional Download Links

1. [The SwiftProcessing Framework and Playground Textbook](https://github.com/jjkaufman/SwiftProcessing/archive/refs/heads/main.zip)
2. [The SwiftProcessing Empty Playground Template](https://github.com/masoodkamandy/Swift-Processing-Empty-Playground/archive/refs/heads/main.zip): This is good for basic prototyping in an empty playground.

[Table of Contents](#Table-of-Contents)

## Textbooks

- **The SwiftProcessing Playgrounds** (Free): These can be found in the SwiftProcessing package in the Playgrounds folder.
- [**Form+Code**](http://formandcode.com/)

[Table of Contents](#Table-of-Contents)

## Recommended Resources

### Code As Art Resources

- [Code as Creative Medium](https://mitpress.mit.edu/books/code-creative-medium)
- [Generative Design](http://www.generative-gestaltung.de/2/)
- [When the Machine Made Art](https://www.bloomsbury.com/us/when-the-machine-made-art-9781623562724)

### SwiftProcessing Resources

- SwiftProcessing Transition Guide (Coming Soon)
- [Join SwiftProcessing's Slack Channel](https://join.slack.com/t/swiftprocessing/shared_invite/zt-aegicvs3-LPD57XmUSB0k6uBS3aijRg)

### Swift Resources

- [The Swift Programming Language](https://docs.swift.org/swift-book/)
- [Hacking with Swift](https://www.hackingwithswift.com/)
- [Ray Wenderlich](https://www.raywenderlich.com/)

### Processing Resources

SwiftProcessing is fundamentally different from Processing and p5.js. That said, the communities and resources available for those platforms can be enormously helpful and once you learn the differences between Processing/p5.js and SwiftProcessing it can be easy to translate between the frameworks.

- [processing.org](https://processing.org/)
- [p5js.org](https://p5js.org/)
- [Processing: A Programming Handbook for Visual Designers and Artists](https://mitpress.mit.edu/books/processing-second-edition)
- [Getting Started with Processing](https://www.oreilly.com/library/view/make-getting-started/9781457187070/) / [Getting Started with p5.js](https://www.oreilly.com/library/view/make-getting-started/9781457186769/)
- [The Coding Train YouTube Channel](https://www.youtube.com/channel/UCvjgXvBlbQiydffZU7m1_aw)
- [The Nature of Code](https://natureofcode.com/)

[Table of Contents](#Table-of-Contents)

## Course Content Overview and Schedule

### 16-Week Course

| Week  # | Module | Content Covered                                              | Exercise                                                     | Project                     |
| ------- | ------ | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------- |
| 1       | Intro  | **Orientation**<br />Syllabus. Useful resources. Outcomes for the course. Strategies for success in this course. | -                                                            | -                           |
| 1, 2    | 1      | **Drawing with Code**<br />Coding without a computer. Drawing with basic shapes in Processing. | **Coding for Humans**                                        | **Drawing with Code**       |
| 3, 4    | 2      | **Color, Loops, and Animation**<br />Coordinate system. Digital color. Built-in functions. Animation. Variables. Basic arithmetic. For loops & conditional logic. Relational & logical operators. Arrays. | **For Loop & Repetition**                                    | **Animation & Interaction** |
| 5, 6    | 3      | **Motion, Collages, and Images**<br />Motion. Map and lerp. Random numbers. Sliders. | **Collage (Still)**                                          | **Mask**                    |
| 7, 8    | 4      | **Functions and Expanded Cinema**<br />Functions. Switches.  | **Collage (Animated)**<br /><br />**Typography with Functions** | **Expanded Cinema Part 1**  |
| 9, 10   | 5      | **Classes, Objects, and More Arrays**<br />Objects and classes. Arrays. | **Typography with Objects**                                  | **Expanded Cinema Part 2**  |
| 11, 12  | 6      | **Using Objects to Create a Game**<br />Breaking a game into its object oriented parts. | **Game Elements**                                            | **Game**                    |
| 13–16   | 7      | **Final Project**                                            | **Final Proposal**                                           | **Final Project**           |

[Table of Contents](#Table-of-Contents)

### 10-Week Course

| Week  # | Module | Content Covered                                              | Exercise                                                     | Project                    |
| ------- | ------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------- |
| 1       | Intro  | **Orientation**<br />Syllabus. Useful resources. Outcomes for the course. Strategies for success in this course. | -                                                            | -                          |
| 1       | 1      | **Drawing with Code**<br />Coding without a computer. Drawing with basic shapes in Processing. | **Coding for Humans**<br /><br />**Drawing with Code**       | None                       |
| 2       | 2      | **Color, Loops, and Animation**<br />Coordinate system. Digital color. Built-in functions. Animation. Variables. Basic arithmetic. For loops & conditional logic. Relational & logical operators. Arrays. | **Animation & Interaction**<br /><br />**For Loop & Repetition** | **Mask Part 1**            |
| 3       | 3      | **Motion, Collages, and Images**<br />Motion. Map and lerp. Random numbers. Sliders. | **Collage (Still)**                                          | **Mask Part 2**            |
| 4       | 4      | **Functions and Expanded Cinema**<br />Functions. Switches.  | **Collage (Animated)**<br /><br />**Typography with Functions** | **Expanded Cinema Part 1** |
| 5       | 5      | **Classes, Objects, and More Arrays**<br />Objects and classes. Arrays. | **Typography with Objects**                                  | **Expanded Cinema Part 2** |
| 6, 7    | 6      | **Using Objects to Create a Game**<br />Breaking a game into its object oriented parts. | **Game Elements**                                            | **Game**                   |
| 8–10    | 7      | **Final Project**                                            | **Final Proposal**                                           | **Final Project**          |

[Table of Contents](#Table-of-Contents)

## Inclusion Statement

We all benefit from being exposed to and understanding different perspectives. It improves everything we make and makes the world more livable when we understand that our perspective is just one of many. To that end, my classroom is one where there will be no discrimination on the basis of race, color, religion (creed), gender, gender expression, age, national origin (ancestry), disability, marital status, sexual orientation, or military status. We will assume no previous knowledge and that everyone is a beginner and create a community of support so that all of us can thrive.

[Table of Contents](#Table-of-Contents)

## Code of Conduct

In my classrooms I like to follow in the footsteps of the [p5.js's Community Statement and Code of Conduct](https://github.com/processing/p5.js/blob/main/CODE_OF_CONDUCT.md). This code of conduct sums up the values I try to adhere to in my classrooms and I expect students to stick to them too.

> - **Be mindful of your language.** Any of the following behavior is unacceptable:
>
>   - Offensive comments related to gender identity and expression, sexual orientation, race, ethnicity, language, neuro-type, size, ability,  class, religion, culture, subculture, political opinion, age, skill  level, occupation, or background
>   - Threats of violence
>   - Deliberate intimidation
>   - Sexually explicit or violent material that is not contextualized and preceded by a considerate warning
>   - Unwelcome sexual attention
>   - Stalking or following
>   - Or any other kinds of harassment
>
>   Use your best judgement. If it will possibly make others uncomfortable, do not post it.
>
> - **Be respectful.** Disagreement is not an opportunity to attack someone else's thoughts or opinions. Although views may differ,  remember to approach every situation with patience and care.
>
> - **Be considerate.** Think about how your contribution will affect others in the community.
>
> - **Be open minded.** Embrace new people and new ideas. Our community is continually evolving and we welcome positive change.

[Table of Contents](#Table-of-Contents)

## Course Grade Breakdown

| Category            | Weight |
| ------------------- | ------ |
| Projects            | 35%    |
| Exercises           | 20%    |
| In-Class Activities | 10%    |
| Final Project       | 35%    |

[Table of Contents](#Table-of-Contents)

## Acknowledgements

> "If I have seen further it is by standing on the shoulders of Giants." —Isaac Newton, 1676

Attribution is a challenge, so I've made every effort to give credit where credit is due, and every effort has been made to ensure that this course is as unique as possible within the context of the open-source community. If you have any concerns in this regard, please [contact me](mailto:masood@masoodkamandy.com).

This course was created using knowledge I've accrued through my experience from many, many teachers, mentors, friends, and other contacts who fed my excitement about art, design, photography, and code. Contained in all of these assignments, directly or indirectly, are their teachings, their support, or both, and for them I am grateful.

The single largest influence was having Casey Reas as a professor and mentor. Many of these assignments started out in his courses and served as the foundation of my own teaching career.

Others who I offer my gratitude to are Derek Milne, Ben Fry, Adam Ferriss, Chandler McWilliams, Daniel Temkin, Jon Kaufman, The Recurse Center, UCSB's Media Arts & Technology Dept., Pasadena City College, Christopher O'Leary, April Kawaoka, Silvia Rigon, Melanie Willhide, Zaki Kamandy, Brad Larsen, Lauren Lee McCarthy, Zöe Wood, Jennifer Jacobs, Penelope Umbrico, James Welling, Cathy Opie, Kathy Ryan, Stephen Frailey, Golan Levin, Daniel Shiffmann, George Legrady, Tobias Hollerer, and Keiko *the* Shiba Inu.

[Table of Contents](#Table-of-Contents)

## Corrections

Please submit any correctiosn to me at masood@masoodkamandy.com. Mistakes are a natural part of a large project like this and I'm always appreciative of suggestions for corrections.

[Table of Contents](#Table-of-Contents)

## License

The course content (assignments and other written material) is available as free and open source course under a [Creative Commons BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/). This means you may use the content of this course for non-commercial purposes with attribution and as long as any modifications you make are also made open source under this same license.

All code provided in this course is provided under a [GNU Lesser General Public Release (LGPL) 2.1](https://opensource.org/licenses/LGPL-2.1) license.

All artwork and images contained within this course are owned by their respective owners. If you'd like an image to be taken down, please write to me to request it be taken down at masood@masoodkamandy.com.

[Table of Contents](#Table-of-Contents)

[Next Section: Frequently Asked Questions](FAQ.md)

