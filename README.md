# Multi_line_fitting
**Multi-Line Fitting Problem:**
Sometimes it is hard to fit points well using just one line. 
Instead, it is more natural to fit the points with multiple lines. 
It is not always simple, however, to know how many lines are the best choice beforehand. 
On the other hand, if there is no restriction on how many lines can be used, it would become trivial to fit the points perfectly: just have a different line pass through each pair of consecutive points in P. 
But that would make the problem meaningless. 
The problem is essentially a “modeling” problem: we want to model a set of “observed points” using a simple yet accurate model, and in this case, the model is a set of lines, each for a different interval of x. 
If too many lines are used, the model would not be “simple” any more. 
Thus, intuitively, we would like a problem formulation that requires us to fit the points well, using as few lines as possible.

**Solution**
Intution is based on the rod cutting problem
