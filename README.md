# my2-Prasadam
# Manuja Prasadam
###### Maldives

Maldives have stunning islands,mesmerizing beaches,and turquoise waters.The Maldives is known for its **crystal-clear waters**, white sandy beaches, and **beautiful coral reefs**. The islands are surrounded by turquoise lagoons and offer incredible views of the Indian Ocean.So, i like the maldives.

---

## Ordered List
1.Taking Pictures<br>
2.Swimming<br>
3.Enjoying the view<br>
4.Tasting new food items<br>

## Unordered List
* Fish Curry
* Saagu
* Samosa

link to MyStats: [MyStats](MyStats.md)

---

## Sports

I love to play the below sports. I would like to recommend these sports to someone to play. The below table shows the information about the most interesting games.


| Sport Name | Reason to recommend | Time Duration |
| --- |  ---  |  ---  |
|Cricket | learning to cope with win and lose | 55 hours |
|Baseball |  it builds strength in arms and legs | 28 hours |
|TENNIS | maintaining health, fitness, strength and agility | 35 hours |
|Golf | It's fun and rewarding! | 7 hour |

---

## Pithy Quotes 

> “It's always darkest before you're blinded by the light.” *josh stern*

> “The best kind of praise is intelligent praise.” *Rachel Heffington*

---

## Code Fencing 

> What's the difference between SCSS and Sass? <https://stackoverflow.com/questions/5654447/whats-the-difference-between-scss-and-sass>


@function is-number($value) {
  @return type-of($value) == 'number';
}
 
@function is-time($value) {
  @return is-number($value) and index('ms' 's', unit($value)) != null;
}
 
@function is-duration($value) {
  @return is-time($value);
}
 
@function is-angle($value) {
  @return is-number($value) and index('deg' 'rad' 'grad' 'turn', unit($value)) != null;
}
 
@function is-frequency($value) {
  @return is-number($value) and index('Hz' 'kHz', unit($value)) != null;
}
 
@function is-integer($value) {
  @return is-number($value) and round($value) == $value;
}
 
@function is-relative-length($value) {
  @return is-number($value) and index('em' 'ex' 'ch' 'rem' 'vw' 'vh' 'vmin' 'vmax', unit($value)) != null;
}
 
@function is-absolute-length($value) {
  @return is-number($value) and index('cm' 'mm' 'in' 'px' 'pt' 'pc', unit($value)) != null;
}
 
@function is-percentage($value) {
  @return is-number($value) and unit($value) == '%';
}
 
@function is-length($value) {
  @return is-relative-length($value) or is-absolute-length($value);
}
 
@function is-resolution($value) {
  @return is-number($value) and index('dpi' 'dpcm' 'dppx', unit($value)) != null;
}
 
@function is-position($value) {
  @return is-length($value) or is-percentage($value) or index('top' 'right' 'bottom' 'left' 'center', $value) != null;
}


Link to the code snippet <https://css-tricks.com/snippets/sass/advanced-type-checking/>



