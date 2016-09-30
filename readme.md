Lessophy
===================

My own collection of LESS mixins with truthful comments about browser support and property values.

## List of mixins

#### Common

* .calc-width (@fallbackWidth: 100px, @value: ~"100% - 50px")
* .calc-height (@fallbackHeight: 100px, @value: ~"100% - 50px")
* .min-height (@value: 0px)
* .max-height (@value: 0px)
* .min-width (@value: 0px)
* .max-width (@value: 0px)
* .box-sizing (@type: content-box)
* .box-shadow (@value: none)
* .background-clip (@value: border-box)
* .background-size (@value: auto)
* .background-gradient-horizontal (@fallback: #333333, @from: #3b5fc3, @to: rgba(37,37,37,0), @start: 0%, @end: 100%)
* .background-gradient-vertical (@fallback: #333333, @from: #3b5fc3, @to: rgba(59,95,195,0.5), @start: 0%, @end: 100%)
* .border-radius (@value: 0)
* .border-bottom-left-radius (@value: 0)
* .border-bottom-right-radius (@value: 0)
* .border-top-left-radius (@value: 0)
* .border-top-right-radius (@value: 0)
* .border-image (@value: ~"none 100% 1 0 stretch")
* .opacity (@opacity: 1)
* .user-select (@value: all)
* .appearence (@value: none)
* .selection (@backgroundColor: #ffffff, @fontColor: #111111)
* .placeholder-font (@fontColor: #111111, @fontSize: 16px, @fontName: sans-serif, @fontWeight: normal)
* .perspective (@value: none)
* .perspective-origin (@value: 50% 50%)
* .backface-visibility (@value: visible)
* .hyphens (@value: none)
* .disable-image-smoothing ()

#### Font

* .font-face (@fontName: sans-serif; @path: @fontsPath; @fontWeight: normal; @fontStyle: normal)
* .text-gradient (@from: #4d9de0, @to: #3dcd8d)
* .text-overflow (@value: clip)
* .text-overflow-ellipsis ()
* .text-antialias (true/false)
* .text-size-adjust (@value: 100%)

#### Transitions

* .transition (@value: none)
* .transition-timing-function (@value: ease)
* .transition-duration (@value: 0s)
* .transition-delay (@value: 0s)
* .transition-property (@value: all)

#### Animation

* .animation (@value: none)
* .animation-name (@value: none)
* .animation-timing-function (@value: ease)
* .animation-duration (@value: 0)
* .animation-delay (@value: 0s)
* .animation-direction (@value: normal)
* .animation-fill-mode (@value: none)
* .animation-iteration-count (@value: 1)
* .animation-play-state (@value: running)

#### Transforms

* .transform (@value: none)
* .transform-scale (@value: 1)
* .transform-scaleX (@value: 1)
* .transform-scaleY (@value: 1)
* .transform-scaleZ (@value: 1)
* .transform-scale3d (@sX: 1, @sY: 1, @sZ: 1)
* .transform-skew (@degX: 0, @degY: 0)
* .transform-skewX (@deg: 0)
* .transform-skewY (@deg: 0)
* .transform-rotate (@deg: 0)
* .transform-rotateX (@deg: 0)
* .transform-rotateY (@deg: 0)
* .transform-rotateZ (@deg: 0)
* .transform-rotate3d (@x: 0, @y: 0, @z: 0, @deg: 0)
* .translate (@x: 0, @y: 0)
* .translateX (@x: 0)
* .translateY (@y: 0)
* .translateZ (@z: 0)
* .translate3d (@x: 0, @y: 0, @z: 0)
* .transform-translateZ-rotateX (@translate: 0, @rotate: 0)
* .transform-translateZ-rotateY (@translate: 0, @rotate: 0)
* .transform-origin (@x: 50%, @y: 50%)
* .transform-style (@style: flat)

#### Flex

* .flex (@value: ~"0 1 auto")
* .flex-wrap (@value: wrap)
* .flex-justify (@value: flex-start)
* .flex-direction (@value: row)
* .flex-order (@value: 0)
* .flex-align-items (@value: stretch)
* .flex-align-self (@value: auto)
* .flex-grow (@value: 0)
* .flex-shrink (@value: 1)
* .flex-basis (@value: auto)

#### Filters

* .filter (@value: none)
* .filter-blur (@value: 0px)
* .filter-brightness (@value: 1)
* .filter-contrast (@value: 0%)
* .filter-grayscale (@value: 0%)
* .filter-hue-rotate (@value: 0deg)
* .filter-invert (@value: 0%)
* .filter-saturate (@value: 0)
* .filter-sepia (@value: 0%)
* .filter-drop-shadow (@value: 16px 16px 10px #000000)

#### Blocks

* .clearfix ()
* .center-block-h ()
* .center-block-h-v (@blockWidth: 300px, @blockHeight: 200px)
* .inline-block ()
* .flex-block ()