# Rectangle Geometry

A rectangle can be represented with $2$ points: its top right corner and bottom left corner.
We'll label these points $tr$ (top right) and $bl$ (bottom left).In this module, we'll assume that increasing $x$ moves to the right
and increasing $y$ moves up.

## Finding area

The formula for finding the area of an individual rectangle is $w \cdot l$.

$\texttt{length}$ is the length of the vertical sides, and $\texttt{width}$ is the length of the horizontal sides.

$\texttt{width} = \texttt{tr}_x - \texttt{bl}_x$
$\texttt{length} = \texttt{tr}_y - \texttt{bl}_y$
$\texttt{area} = \texttt{width} \cdot \texttt{length}$

```
def area(bl_x: int, bl_y: int, tr_x: int, tr_y: int) -> int:
	length = tr_y - bl_y
	width = tr_x - bl_x
	return length * width
```

## Checking if two rectangles intersect

Given two rectangles $a$ and $b$, there are only two cases where they do not intersect:

$\texttt{tr}_{a_y}$ $\leq$ $\texttt{bl}_{b_y}$ or $\texttt{bl}_{a_y}$ $\geq$ $\texttt{tr}_{b_y}$.
$\texttt{bl}_{a_x}$ $\geq$ $\texttt{tr}_{b_x}$ or $\texttt{tr}_{a_x}$ $\leq$ $\texttt{bl}_{b_x}$.


In all other cases, the rectangles intersect.

Implementation

```
def intersect(s1, s2) -> bool:
	bl_a_x, bl_a_y, tr_a_x, tr_a_y = s1[0], s1[1], s1[2], s1[3]
	bl_b_x, bl_b_y, tr_b_x, tr_b_y = s2[0], s2[1], s2[2], s2[3]

	# no overlap
	if bl_a_x >= tr_b_x or tr_a_x <= bl_b_x or bl_a_y >= tr_b_y or tr_a_y <= bl_b_y:
		return False
	else:
		return True
```

## Finding area of intersection

We'll assume that the shape formed by the intersection of two rectangles is itself a rectangle.

First, we'll find this rectangle's length and width.
$\texttt{width} = \min(\texttt{tr}_{a_x}, \texttt{tr}_{b_x}) - \max(\texttt{bl}_{a_x}, \texttt{bl}_{b_x})$.
$\texttt{length} = \min(\texttt{tr}_{a_y}, \texttt{tr}_{b_y}) - \max(\texttt{bl}_{a_y}, \texttt{bl}_{b_y})$.

If either of these values are negative, the rectangles do not intersect.
If they are zero, the rectangles intersect at a single point.
Multiply the length and width to find the overlapping area.


```
def inter_area(s1, s2) -> int:
	bl_a_x, bl_a_y, tr_a_x, tr_a_y = s1[0], s1[1], s1[2], s1[3]
	bl_b_x, bl_b_y, tr_b_x, tr_b_y = s2[0], s2[1], s2[2], s2[3]

	return (min(tr_a_x, tr_b_x) - max(bl_a_x, bl_b_x)) * (
		min(tr_a_y, tr_b_y) - max(bl_a_y, bl_b_y)
	)
```
