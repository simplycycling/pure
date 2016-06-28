# Pure - a "card" game for bored cyclists

Are you a roadie (road cyclist) who puts in long hours, and occasionally gets
bored? Do you not ride in a land of natural splendor? Need something to take
your mind off the pain in between intervals/sets? Need another way to compete
with your idiot buddies?

This is your lucky day. You get to help me finish off this stupid game that
I play.

Backstory - I ride a lot. Sometimes I get bored, when I'm riding a road that
I've ridden 80 zillion times before. So while I'm riding, I look for patterns
in the time field of my bike computer (Garmin 705), especially symmetry: 14:41, 1:00:01, things like that. And when I'd see these patterns, I'd make
  a sound in my head, kind of like a video game sound, like when Mario gets
  a mushroom, or something (I'm not a gamer, I don't know if Mario really gets
  mushrooms.).

So, rules...umm, yeah. I've come up with a few.

## Different hands

So a "hand" is when you have a number that matches some kind of pattern,
usually symmetry based, but it can also be patterns that you find appealing.

### Symmetry based hands

Maybe a better term would be "palindrome" based hands. This is just basically
any time that reads the same, whether read from the left or right:

- 1:00:01
- 3:33
- 44:44
- 2:07:02
You get the point. 

Zeros to the left (so long as there's not a positive integer on the other side)
are ignored, under the standard set of rules, as it's very limiting:

- 00:33:00

Basically, it only gives you one option every 11 minutes, and that's not much
fun.


### Non-palindrome based hands

This is pretty open to interpretation, using whatever patterns you like:

- 13:37
- 12:34
- 12:34:56 (if you ever get that, you win)

### Mirrored hands

This is not a very long list. On a bike computer, 5's and 2's look like
mirrored versions of themselves, so pretty much any combination of 5's and 2's
are valid, so long as they mirror each other:

- 55:22
- 25:52 (that's also a symmetry, or palindrome, or whatever)

Not valid - any mirrored hand that contains a non-mirrorable number:

- 35:23

However, 15:21 would work. Get it? Sure you do. It's not hard.

## So...how do I play?

Yeah, I'm still working that out. Maybe a score based system? I think that
makes the most sense.

So, symmetry/palindromes are worth the most, the higher the number, the higher
the score. Solid palindromes, 55:55, 44:44, 1:11:11, etc are worth the most,
with mixed values worth less. 10:01, 1:07:01, etc.

55:55 == 50 pts
44:44 == 40 pts
...
11:11 == 10 pts

Mixed values that start in the 50 minute range are worth 45, in the 40 minute
range 35, in the 10 minute range 5 points. 

Idea from Dave Bartel and Tom Ligman, who obviously can't do a pull request
- you start out the game as a Fred, and work your way up to Pro. It's going to
  take me a few minutes to work that out.

### Ok, but how do I actually GET a hand?

You get a hand when you actually see it. So if you look at your bike computer
at 22:23, you missed the solid, palindrome hand 22:22.

### Important, immutable rule

When you look at your bike computer, you can ONLY see the hand.

In other words, you don't get the hand, and as follows you don't get the
points, if it's 24:40, and you just watch your computer until it turns to
24:42, it doesn't count. If you look at it, and it's 24:42, and while you're
watching, it turns to 24:43, it doesn't count.

If you're wondering, that's called leaking, or a leaked hand. Leaked hands are
worth 0.

### Keeping score

Keep it in your head, dingbat. Math isn't hard.

## Why do you call it Pure?

That's kind of a long story. I'd look at my garmin and see that I was 3 seconds
away from a hand, and I'd look up, count to 3 in my head, then look back down
and get the hand. For some reason, I started valuing that less than if I looked
down at my Garmin and got a non-leaked hand, without having to look away and
count. And I started referring to that as a "pure" hand. 

Pure hands are the best hands. No difference in value, but if you find yourself
always counting your way into good hands, you might be a count doper!

## What a great game! But it doesn't sound complete - how do I contribute?

This is github - a collaborative platform. If you want to add rules, open
a github account, and then look up a couple of topics:

"How do I clone a git repository?"
"How do I contribute to a git repo?"
"How do I do a pull request?"

It's all pretty easy. And you can, of course, just fork it without actually
contributing to the original, or you can send your contribution my way (via
a pull request). Although I will reserve the right to not accept new rules or
contributions if I don't like them; however, I will explain why, if I do turn
down your PR.

