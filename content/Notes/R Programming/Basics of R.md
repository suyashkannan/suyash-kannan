Basic calculator commands, +,-,/,* are possible (*must put multiply sign between numbers and variables*)
Syntax for logarithm commands:
- log10() for base 10
- log() for base e
- log(value, base) for arbitrary base
- exp() for e^()
Sequences and Basic Vectors:
- seq(starting no, ending no, common difference)
The value of $\pi$ is stored in the variable 'pi'
Assigning Variables:
- a <- value
- a = value
The Plot Command:
- Define a function y=f(x)
- Command - plot(x, y, type = l)
- Recalculation Error - If the function is defined first and the value of x is altered later, the variable y still holds the old data, and when plotting the lengths of the variables would be different and hence trigger an error. Must redefine the function y before plotting.
Length Function - length(variable) returns the length of the vector components.
- type parameter values
	- p - points
	- l - lines
	- b - both
	- c - lines part alone of b
	- o - overplotted
	- h - histogram
	- s - stair steps (first horizontal, then vertical)
	- S - other steps (first vertical, then horizontal)
	- n - no plot
- Annotation of Plots
	- main - title
	- sub - subtitle
	- xlab - label of x axis
	- ylab - label of y axis
	- asp - x/y aspect ratio
	- **Example:**
	- ![[Pasted image 20251006103245.png]] 
	- `x = seq(3,50,3)`
	- `y=exp(x)`
	- `plot(x,y,type="b",main="graph",xlab="x",ylab="y")`