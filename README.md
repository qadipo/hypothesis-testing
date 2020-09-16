# Using the whole population vs Using a sample to Test Hypothesis

The main aim of this work is to demonstrate how a hypothesis on a population can be confirmed or be rejected using a **sample data**. It is not in all cases that entire population data will be available to us thus warranting the need of using a representative data. This will be demonstrated though using the entire population data ~~The data under consideration is not massive to instill fear over your computing resources and so can be easily be handled by your computer~~ then the same shall be repeated using a sample **as a proof of concept.**

## Background of the data under consideration
Autolib was a an electric cab company that operated in France under three flavours ~~yes, operated, it has since gone under, I dont know where though~~. One of its flavour was the Bluecar which was a cab sharing service provider.

**Supposing** there was a general feeling in the management that Postal code area 75015 had the an averagely the same numbers of Bluecar cabs taken as Postal code area 75017, how would we deal with such a claim?

Possible approaches:
  1. Working with the whole population data. Calculating the average rate for cabs taken for each areas then infer from the results if the claim is TRUE. *Remember that this is only possible if the data is readily available and not massive*
  2. Taking a sample from the two postal code areas and then performing statistical tests ~~z-test, t-test, and many others~~ to confirm whether the claim is so. And so with this we would then formulate a **null hypothesis** and the **alternate hypothesis** and then work towards accepting one of the two. Our hypotheses will be as follows:
      Null Hypothesis: Same number of cars are taken from Postal Area 75015 and Postal Area 75017 during the weekday
        **H0: µ1 = µ2**

      Alternate Hypothesis: More cars are taken from postal area 75015 than from postal area 75017 during the weekday
        **H1: µ1 > µ2**

##**Prerequisite**
    1. Suitable editor
    2. The following libraries: numpy, pandas, matplotlib, seaborn, scipy, statsmodel (all are python libraries)

## Contributor
(c) Qadipo

License : Open Database License
