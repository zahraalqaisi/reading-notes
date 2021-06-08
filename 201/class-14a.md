#  psychological safety

> ‘‘We’re living through a golden age of understanding personal productivity,’’ says Marshall Van Alstyne, a professor at Boston University who studies how people share information. ‘‘All of a sudden, we can pick apart the small choices that all of us make, decisions most of us don’t even notice, and figure out why some people are so much more effective than everyone else.’’

> Yet many of today’s most valuable firms have come to realize that analyzing and improving individual workers ­— a practice known as ‘‘employee performance optimization’’ — isn’t enough. As commerce becomes increasingly global and complex, the bulk of modern work is more and more team-based. One study, published in The Harvard Business Review last month, found that ‘‘the time spent by managers and employees in collaborative activities has ballooned by 50 percent or more’’ over the last two decades and that, at many companies, more than three-quarters of an employee’s day is spent communicating with colleagues.

### software engineers are encouraged to work together
- studies show that groups tend to innovate faster
- see mistakes more quickly and find better solutions to problems.
- Studies also show that people working in teams tend to achieve better results and report higher job satisfaction

***In a 2015 study, executives said that profitability increases when workers are persuaded to collaborate more.***

***The researchers eventually concluded that what distinguished the ‘‘good’’ teams from the dysfunctional groups was how teammates treated one another***

***The right norms, in other words, could raise a group’s collective intelligence, whereas the wrong norms could hobble a team, even if, individually, all the members were exceptionally bright.***


### two behaviors that all the good teams generally shared:

1. ‘‘equality in distribution of conversational turn-taking.’’

2. the good teams all had high ‘‘average social sensitivity’’ — a fancy way of saying they were skilled at intuiting how others felt based on their tone of voice, their expressions and other nonverbal cues.


# css transforms:

## transforms:

***The transform property comes in two different settings,***
- two-dimensional 
- three-dimensional.
> Each of these come with their own individual properties and values.

### 2D Transforms
> Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. We’ll start by discussing how to transform elements on a two-dimensional plane, and then work our way into three-dimensional transforms.

### 3D Transforms
> Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements. Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

## Transform Style

> On occasion three-dimensional transforms will be applied on an element that is nested within a parent element which is also being transformed. In this event, the nested, transformed elements will not appear in their own three-dimensional space. To allow nested elements to transform in their own three-dimensional plane use the transform-style property with the preserve-3d value.

> The transform-style property needs to be placed on the parent element, above any nested transforms. The preserve-3d value allows the transformed children elements to appear in their own three-dimensional plane while the flat value forces the transformed children elements to lie flat on the two-dimensional plane.

# Transitions & Animations:

## Transitions
***As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.***

***There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.***

## Shorthand Transitions
***Declaring every transition property individually can become quite intensive, especially with vendor prefixes. Fortunately there is a shorthand property, transition, capable of supporting all of these different properties and values. Using the transition value alone, you can set every transition value in the order of transition-property, transition-duration, transition-timing-function, and lastly transition-delay. Do not use commas with these values unless you are identifying numerous transitions.***


## Animations
***Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.***

# 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
1. Fade in:
**Fade in effects are coded in two steps:**
- first, you set the initial state;
- next, you set the change

2. Change color.

3. Grow & Shrink.

4. Rotate elements.

5. Square to circle. 

6. 3D shadow.

7. Swing.

8. Inset border.


