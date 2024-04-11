# Error vs Uncertainty

Those unversed with uncertainty often tend to think of uncertainty and errors interchangeably. However, they are not the same.
I came across the following definitions from the AIAA guidelines (AIAA G-007-1998):

*Uncertainty* is defined as:

 *A potential deficiency in any phase or activity of the modeling process due to lack of knowledge.* 

whereas *Error* is defined as:

*A recognizable deficiency in any phase or activity of modeling and simulation that is not due to lack of knowledge.* 

The key difference between uncertainty and error is the *lack of knowledge*.

The keyword in the definition of **uncertainty** is *potential*, indicating deficiencies may or may not exist. Lack of knowledge has primarily to do with a lack of knowledge about the physical processes that go into building the model. For example, uncertainty applies to describing deficiencies in turbulence modeling. There is a lot about turbulence modeling that is not understood. One approach for determining the level of uncertainty and its effect on one's analysis is to run a number of simulations with a variety of turbulence models and see how the modeling affects the results.

The definition of **error** implies that the deficiency is identifiable upon examination. Errors can also be classified as acknowledged or unacknowledged:

**Acknowledged errors** (examples include round-off error and discretization error) have procedures for identifying them and possibly removing them. Otherwise, they can remain in the code with their error estimated and listed.

**Unacknowledged errors** (examples include computer programming errors or usage errors) have no set procedures for finding them and may continue within the code or simulation.


