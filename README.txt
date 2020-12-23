The purpose of this tool is to generate graphs to help people understand the point of max utility and Hick's and Slutsky's subsitution methods. This is not meant for usage on any form of graded work such as homework, projects, examinations, etc. Anyone who uses this tool is 100% responsible for their usage of it and should abide all local codes and laws.

Tolerance
- How close you want the answer to
- Smaller the number, the more accurate it'll be and the longer it'll take
- 1e-15 is what I recommend, 1e-6 is default

Evaluations
- How many max iterations the program will do
- Bigger the number, the more iterations can be done, might lead to longer load times
- Can be anything from 1 to as much as you want

p1
- Price of Good 1
- Needs to be a number

p2
- Price of Good 2
- Needs to be a number

m
- Income
- Needs to be a number

factor
- Use if m is over 10,000; otherwise keep at 1
- Mainly used if there's too many possible solutions due to large income

p1new
- If the good of price 1 changes
- Use p1 if good of price 1 does not change
- Use a positive number if price of good 1 changes

p2new
- Same as p1new, except it's p2 or a positive number

Utility Function
- use x and y for good 1 and good 2 respectively
- Examples
	- min(2*x,3*y)
	- max(2*x,3*y)
	- 2*x - 3*y
	- 2*x^(1/2)*y^(1/4)
	- log(x) + 3*y

Extra Indifference Curves
- Helps visualize one indifference curve above and below the original function
- True means on, False means Off

Subsitution Method
- If you want to see the Hick's or Slutsky's Subsitution effect
- None - does not calculate nor display the two methods, but the new budget line is still shown
- Hick's - Displays Hick's method and calculates the respective subsitution and income effect
- Slutsky - Display's Slutsky's method and calculates the respective effects
- Hick's and Slutsky - Displays both methods on the graph, but does not calculate the effects