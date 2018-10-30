# Results for spatially homogeneous test cases

## TC1.1-1.4: fixed temperature bath

This bath is proposed for the evaluation of chemical reaction rates, in which separate mode temperatures (translational, rotational, and vibrational) are set, with Maxwell-Boltzmann state distributions enforced at the prescribed temperatures.

- In the DSMC method, a fixed-temperature bath can be modeled as a spatially uniform box with specular walls where the gas translational, rotational, and vibrational temperatures are all kept at their prescribed values. The chemical reaction rates should be calculated even though no internal energy transfer or chemical reactions should be allowed (i.e. the reaction events are counted but not modeled).

- For continuum CFD, such a bath reduces to the calculation of chemical reaction rates determined as functions of total or translation-rotational and vibrational temperatures.

- In the QCT framework, the methodology described in Ref. [10] may be used to evaluate the reaction rates. In that work, a large number of representative collisions between given species in an ensemble of particles characterized by one or more temperatures is used to calculate the rate.
