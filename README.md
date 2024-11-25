**zerosUaz** _is a MATLAB function designed to compute the complex zeros of the parabolic cylinder function U(a,z)_.

_This is a Matlab implementation of the algorithm described in the paper "A numerical algorithm for computing the zeros of parabolic cylinder functions in the complex plane", by T.M. Dunster, A. Gil, D. Ruiz-Antolin, J. Segura_

Function Signature

### **[zzero, ierr] = zerosUaz(a,z)**

Inputs:

        a: parameter of the function U(a,z). 
           Admissible values of a in the algorithm
           are real values with |a|>0.2

        L: Length of the interval that determines the 
           spatial domain for locating the complex zeros. 

Outputs

        zzero: array with the computed zeros.

        ierr: Error flag indicating the success or issues in computation:

             0: Computation successful.

             1: Computation failed due to one or more input values being out of bounds.
