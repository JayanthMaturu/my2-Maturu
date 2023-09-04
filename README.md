# Jayanth Maturu
### Manali
The famed **Hadimba Temple**, the scenic Rohtang Pass, the snow-covered **Solang Valley**, and Manali's exquisite food scene are just a few of the attractions that make this mountain destination so well-known.<br>
For those with a sense of adventure, Manali offers a variety of activities, including **paragliding**, river rafting, mountain biking, rock climbing, and trekking.

Memorable Activities & Food
---

1. River Rafting
2. Trekking
3. paragliding

* Kesar
* Chana Madra
* Aktori

**[Goto MyStats](MyStats.md)**

Physical Activity (Sports)
---

Sports are the best source of physical activities. Most of the sports include volunutary body movement.All activities, regardless of intensity or time of day or night, can be considered physical activity. Exercise and unplanned activities that are a part of daily life are included.Below is the table containing some good sports.

| Sport | why to play | hours per week |
| --- | --- | ---: |
| Badminton | Involves all body movement | 7 |
| Cricket | Burns lot of calories in body | 5 |
| Foot Ball| Is good for musclular movement | 5 |
| Cycling | Refreshing  | 6 |
| Table Tennis | Tactic play  | 6 |

Quotes
---
>Try to learn something about everything and everything about something- *Thomas Huxley*

>You cant't defend. You can't prevent. the only thing you can do is detect and respond.- *Bruce Schneier*

Code Fencing
---
>I'm trying to implement a SASS function that will convert pixels to ems for our application and running into trouble.My issue is that it only works if I have the .k-grid-header class and I don't really understand why. I would think the second class that calls the function would be enough to set the size. - [StackOverflow](https://stackoverflow.com/questions/53871707/sass-function-to-convert-px-to-em) <br>

Source-code for the approach- [Source Code](https://css-tricks.com/snippets/sass/px-to-em-functions/)
~~~
@function calc-em($target-px, $context) {
  @return ($target-px / $context) * 1em;
}

// and modified to accept a base context variable

$browser-context: 16;

@function em($pixels, $context: $browser-context) {
  @return ($pixels / $context) * 1em;
}
~~~