# TDEmetric
MAF metrics for TDEs.

---

**TDEmetric** finds the detectabilty of one fast and faint event (TDEfaintfast_z0.1.dat) for a given opsim.

**TDEpopulationMetric** uses as input a list of TDEs (iPTF16fnl.dat and PS1-10jh.dat files) and calculates their detectability for a given opsim.

---

Both metrics contain two sets of requirements for detectability:
   - TDE_color / TDE_pop_color: requirements for detection are such that we monitor the color of the event through some phases of the light curve, but we do not particularly care in which filter the event is observed.
   - TDE_color+u / TDE_pop_color+u : requirements for detection are such that we monitor the color of the event through some phases of the light curve, and we require at least 1 u-r pair of observations around peak of the light curve (t_peak \pm 5 days) and at least 1 u-r pair in two weeks after (t_peak + 5 days).

---

###### Contributors: [Xiaolong Li](https://github.com/xiaolng) and [Katja Bricman](https://github.com/Bricmank)
