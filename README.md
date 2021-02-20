# animated_text

A simple text appearance with animation which increases user experience.


## Using

[Example](https://github.com/abdullahriaz95/Flutter-ParticleBackground/blob/master/example/example_app.dart)

To use this package, add a dependency to your `pubspec.yaml` as:

    dev_dependencies:  
      flutter_test:  
        sdk: flutter
      animated_text: ^0.0.1


## How to Use

Simply just use the `AnimatedText()` widget. Some of the examples are given below.

### Example 1
Simply use **AnimatedText()** with a number of parameters defined below.

    AnimatedText(
        text: 'Easy and Healthy',
        textStyle: GoogleFonts.workSans(
            fontWeight: FontWeight.w800,
            fontSize: 32,
            color: Color(0xFFFB3F01),
        ),
        durationBetweenLetters: Duration(milliseconds: 70),
        letterExpandingDuration: Duration(milliseconds: 500),
    ),
 
   
## Parameters

 1. text - simple String that you want to animated and show   
 2. textStyle - TextStyle that you want your text to apply
 3. durationBetweenLetters - Duration between two consecutive letters appear with 
 4. letterExpandingDuration - Expanding animation Duration of a each letter

## Showcase

<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/3ke4eysuUTo" width="400" height="600" frameborder="0" allowfullscreen="true"> </iframe>
</figure>

