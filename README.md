# Fitting-excitatory-and-inhibitory-currents

This program proposes a way to fit a compound current (recorded in whole cell voltage clamp) and to disentangle the excitatory and the inhibitory components of it.

Order in which you should run the scripts:

- "Fit excitatory current". This script will fit a simulated excitatory current, generated with "Simulate E current". You'll get accurate values that you'll later use
to constrain the fit for the compound current problem.

- "Fit inhibitory current". This script will fit a simulated inhibitory current, generated with "Simulate I current". You'll get accurate values that you'll later use
to constrain the fit for the compound current problem.

- "Fit compound current". This script will try to fit a simulated compound current, generated with "Simulate compound current". It'll use 
information from the previous two fits to be as accurate as possible.
