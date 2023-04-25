# thesis-masc

## On the design of Stable, High Performance Sigma Delta Modulators

My Master of Applied Science thesis at UBC, in the Electrical and Computer Engineering Department (Biomedical Engineering).

## Abstract

The sigma delta architecture of analog-to-digital (A/D) converters is especially applicable to digitizing most bio-signals. High order single-bit sigma delta modulators provide high resolution and linearity with low circuit complexity but require careful design to avoid unstable states. Many existing methods of designing these systems have few degrees of freedom, rely extensively on simulations, and do not provide guarantees about stability. The problem of designing sigma delta modulators with high performance and a clear indicator of the performance versus stability is addressed in this dissertation. This is done by developing a model of the sigma delta modulator that more accurately represents the system including robustness against the nonlinearities due to the quantizer element. After introducing many stability criteria from literature, those most suited to design are identified and the model adjusted to allow these criteria to be applied. High performance is maintained by using the generalized Kalman-Yakubovic-Popov (GKYP) lemma to maximize noise rejection in the signal band using a semidefinite programming (SDP) framework that also permits the use of H∞, H2, and l1 norm-based stability constraints on the system. Several designs using this framework are presented and their relative merits discussed. Examples include an aggressive noise shaping design to compete with existing methods on the basis of performance and designs with guaranteed stability for a range of input signals. The performance-stability trade-off for the different stability constraints using this work is examined and motivated by simulation results.

> Hannigan, B. C. (2018). On the Design of Stable, High Performance Sigma Delta Modulators [University of British Columbia]. https://open.library.ubc.ca/cIRcle/collections/ubctheses/24/items/1.0375830
