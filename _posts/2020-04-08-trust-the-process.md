---
layout: post
title: Trust the Process, Not the Data Debunking the Birth Weight Paradox
---

Paradoxes have always confused me...

The birth weight paradox is most easily explained in the context of an example using real data from the National Center for Health Statistics. It is well-understood that lower birth weights tend to coincide with a higher rate of infant mortality, which is made even higher when an infant is born to parents who smoke. This is shown in Figure 2 in Hernández-Díaz et al. (2006). However, if we only consider low birth weight (LBW) infants, the infant mortality rate is higher for non-smoker parents than for parents who smoke.


Figure 2 from Hernández-Díaz et al. (2006) — At higher birth weights, infants born to smokers have a higher mortality rate. However, at low birth weights (below ~2000 g), the opposite becomes true. This creates the “paradoxical” suggestion that smoking can decrease infant mortality for low birth weight infants.

Hernández-Díaz et al. (2006) investigated this phenomenon using causal diagrams to show that spurious associations can be made between smoking and infant mortality when conditioning on birth weight. They consider a series of progressively more complicated causal diagrams that use different aspects of expert knowledge and comparisons of expected relationships to reality to find the most realistic mechanism by which each variable affects each other variable.

The authors begin by considering a simple causal diagram in which parents who smoke affect the mortality rate of their infant through a lower infant birth weight. This is a structure called a chain, since it represents each event being caused by another in a chain.

Observationally, this would mean that when we look at infants of all birth weights, reality behaves as we expect it to: smokers have a higher infant mortality rate than non-smokers. Then, when we only look at infants with low birth weights, there should be independence between smoking and infant mortality. This is because we are conditioning on the center value of a chain, which breaks the dependence relation between the beginning and the end of the chain. However, this is not what we observe in the data. We still see an association between smoking and infant mortality, even though it’s not the association we expect. So, this model and the conditional behavior associated with it do not match the data.

The next causal diagram that the authors consider captures the situation in which smoking affects infant mortality through some other method than lowering an infant’s birth weight.


If this causal diagram represented reality, there is no causal relationship between low birth weight and infant mortality. So, fixing one of those variables should not affect the other. Therefore, we would see no change in the crude infant mortality rate ratio (which is just the mortality rate for maternal smokers divided by the mortality rate for maternal non-smokers) when we only consider low birth weight infants. This is not the case given the author’s observations: the crude mortality rate ratio was 1.55, and when they held birth weight constant and calculated the same ratio, they got 1.09. So, this causal diagram does not represent reality either.

Hernández-Díaz et al. (2006) combined the previous two causal diagrams into a more complete diagram that allows for maternal smoking to cause increased infant mortality through a lessened infant birth weight as well as some other mechanism.


This causal diagram is actually consistent with the data that Hernández-Díaz et al. (2006) observed, since it allows for multiple paths of association between smoking and mortality. However, this diagram is too simple. It also doesn’t account for any common causes between low birth weight and high rates of infant mortality besides smoking.

The next causal diagram that Hernández-Díaz et al. (2006) consider attempts to account for these common causes.


This is a more informed causal diagram than the previous one because it accounts for unmeasured common causes of low birth weight and increased infant mortality rates that might cause spurious associations to be measured between smoking and mortality if you only look at low birth weight infants. This then induces the “paradox” we observe through a selection bias that is more easily explained if we consider a slightly more simple causal diagram.


For this example, we can consider U to be birth defects, an unmeasured common cause of low birth weight and high infant mortality. According to this diagram, birth defects are the only cause of high infant mortality. Both maternal smoking and birth defects can cause a low birth weight, and those are the only two causes of low birth weight if this diagram represents reality. So, any infant who has a low birth weight whose parents did not smoke means that they must have a birth defect. This means that among low birth weight infants, the more likely the infant is to have parents who smoked, the less likely they are to have a higher rate of infant mortality (because they are less likely to have birth defects). Observationally, this matches what we observe in the data! This causal diagram is the closest to reality so far. However, this diagram does not have to include an association between smoking and infant mortality, which is not representative of reality. If we do not condition on birth weight, there seems to be a difference in mortality rate for infants born to smokers and non-smokers, as can be seen in Figure 2 of  Hernández-Díaz et al. (2006). So, if we add that association, the causal diagram should be more representative of reality.

Adding this association to make the causal diagram more representative of reality does not change the way that the “paradox” arises, however. When we condition on low birth weight, a variable that is an effect of our treatment variable (maternal smoking) and has a cause in common with the outcome (infant mortality), this selection bias arises.

The last causal diagram that Hernández-Díaz et al. (2006) consider is the closest to reality. They add in the potential for there to be multiple methods by which an infant has a low birth weight, and they also add that the method associated with birth defects is the only method associated with an increase in infant mortality.

This causal diagram could account for the observation that when looking only at low birth weights, there may be some subgroups who have a higher mortality rate because their low birth weight was caused by some unmeasured, more deadly cause than smoking. In that case, the “magnitude” of the association between U and mortality would be greater than the magnitude of the arrow between smoking and mortality.

So, this apparent “paradox” that we intuitively know should not be true isn’t actually true. That’s good! However, Hernández-Díaz et al. (2006) explain that this kind of selection bias can arise with any set of variables that have the same causal diagram structure. They use the example of three associated variables: alcoholism, elevated levels of liver enzymes, and mortality. Liver enzymes can be caused by two main causes, alcoholism and liver cancer. If a doctor were to measure elevated liver enzymes in a patient, the patient would clearly have a better prognosis if they were an alcoholic than if they had liver cancer, since liver cancer has a stronger association with mortality. However, no doctor would prescribe alcoholism as treatment if a patient had elevated liver enzymes with some unknown cause. Similarly, it is not logical or ethical to prescribe cigarettes to an expectant mother if their child is suspected to have a low birth weight just because there is less of an association with increased infant mortality for maternal smokers with low birth weight babies.

Hernández-Díaz et al. (2006) conclude their analysis by explaining that a thorough causal network construction is necessary to be able to make any sound conclusions and interventions through causal analysis. Expert knowledge is crucial in conducting studies. However, the resolution of the birth weight “paradox” tells us that as students, our gut instincts about the integrity of a seemingly paradoxical result are often more accurate to reality than the result may be. If we don’t make informed choices about the steps of our analysis, we can’t trust the conclusions that might result from it.
