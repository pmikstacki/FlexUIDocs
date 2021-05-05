### Animation Module Overview

Flex UI comes with 2 UI animation solutions, reworked to fit well into the whole framework. Bugfixes and the license of these solutions (MIT <3 ) allows us to tightly integrate it into Flex UI

* [Timeline](Timeline/Timeline.md)

    Timeline Animation is based on [UI Playables](https://github.com/Haruma-K/UnityUIPlayables). It Allows to make complex animations or cutscenes. It's superior to using Animation Clips and State Machine, because it doesn't render UI every frame and it removes the hurdles of working with mecanim for ui animations (Unity - Why did you not make this the default! )

We integrated it with [UI ShapeKit]("/Modules/ProceduralShapes/ProceduralShapes.md")

<img title="" src="file:///C:/Users/mixerek/AppData/Roaming/marktext/images/2021-05-05-23-38-52-image.png" alt="" width="340">

* [Tweening](Tweening/Tweening.md) 
  
  Tweening pipeline allows you to have more fine control. It is used as a utility for the  [Animation Pipeline](Pipeline/AnimationPipeline.md)
  
  It is based on [Platinio Tween](https://github.com/platinio/PlatinioTween)
