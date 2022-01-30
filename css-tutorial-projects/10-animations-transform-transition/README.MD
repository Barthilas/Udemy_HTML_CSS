animation change over time with more control
transform: translate, rotate, scale, skew()

translateX(50%) goes from parent width, move element by (x, y)
scale (x, y) increase/decrease size
rotate(degrees) preferred
rotateX(90), rotate(y) disappears..
380 degrees = 20 degrees (should be obvious, 380%360=20)

skewX/Y,Z but just use skew, "zekřivení"

transition change over time
transition-property: background, border-radius...
transition-duration: 4s, 2s ..
transition-delay: 2s

shorthand
    //property //duration //delay
transition: background 2s 1s | repeat
transition: all
transition-timing-function: ease (default) {slow start- fast - slow end},
 linear (same speed whole duration),
  ease in (slow start),
   ease-out (slow end),
    ease-in-out (slow start fast, slow end)

transition vs animation = animation has more options
transition from start state to end state 0 to 100%
animations 0 1% 2% ... 100% multiple states

animation-name: move
animation-duration: 10s
animation-iteration-count: 3
@keyframes move {
    0% {

    }...
    100% {

    }
}

animation: move 5s infinite;

animation-fill-mode: what happens with elements once the animation ends.
backwards (default), forward (keep state)