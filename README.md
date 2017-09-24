# BROJA-2PID: Bertschinger-Rauh-Olbrich-Jost-Ay (BROJA) bivariate Partial Information Decomposition

This Python module implements the Bertschinger-Rauh-Olbrich-Jost-Ay bivariate Partial Information Decomposition (N. Bertschinger, J. Rauh, E. Olbrich, J. Jost, N. Ay, *Quantifying Unique Information.* Entropy 2014, 16, 2161-2183; [doi:10.3390/e16042161](http://dx.doi.org/10.3390/e16042161).).

It uses the Exponential Cone Programming approach described in
* A. Makkeh, D.O. Theis, R. Vicente, *Bivariate Partial Information Decomposition: The Optimization Perspective* (to appear in Entropy, 2017),   
and
* Abdullah Makkeh's PhD thesis (forthcoming (2018))

The details of the implementation, user interface, and example code are described in
* A. Makkeh, D.O. Theis, R. Vicente, *BROJA-2PID: A cone programming based Partial Information Decomposition estimator*
(currently in preparation).

We ask that you give proper reference when using this software.
If you use it with only small modifications (note the Apache 2.0 license), use 
```
@Article{makkeh-theis-vicente:pidOpt:2017,
  author =       {Makkeh, Abdullah and Theis, Dirk Oliver and Vicente, Raul},
  title =        {BROJA-2PID: A cone programming based Partial Information Decomposition estimator},
  journal =      {jo},
  year =         2017,
  key =       {key},
  volume =    {vol},
  number =    {nr},
  pages =     {1--2}
}
```
If you make significant modifications but stick to the approach based on the same Exponential Cone Programming model, use
```
@Article{makkeh-theis-vicente:pidOpt:2017,
  author =       {Makkeh, Abdullah and Theis, Dirk Oliver and Vicente, Raul},
  title =        {Bivariate Partial Information Decomposition: The Optimization Perspective},
  journal =      {Entropy},
  year =         2017,
  key =       {key},
  volume =    {vol},
  number =    {nr},
  pages =     {1--2}
}
```
In addition, if you use another Exponential Cone Programming model, one that resembles one of the models in Makkeh's PhD thesis, please cite his thesis.
