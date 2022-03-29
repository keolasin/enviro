# Lecture 6.1.2: Disability Adjusted Life Years (DALYs)

Burden of Disease Estimates

Patterns of health described by

- age
- sex
- region
- disease type

Health has long been evaluated by mortality based indicators both in the US and elsewhere.

- life expectancy
- all-cause and disease-specific mortality and infant mortality

Mortality based indicators used to be compared by region, country, and across countries. But, there's a problem:

- not useful to judge the health of a pop or the comparative impact of an intervention
- the contribution of chronic disease, injury, and disability to pop health goes unrecorded

## DALYs can address these problems

We want to know impact of non-fatal health conditions that make people sick but don't kill them. 
As well, this info can help inform policy and planning.

**Disability adjust life years** measure the gap between a pop's health and hypothetical ideal for health achievement.

3 major objectives:

1. to facilitate the inclusion of non-fatal health outcomes in debates on local or international health policy
2. to make recommendations that would improve health, mainly in developing countries
3. to quantify the burden of disease using a measure that could be used for cost-effectiveness analysis

### Principles

- everyone has the right to best life expectancy in the world
- the only differences in the rating of a death or disability should be due to age and sex, - not income, culture, location, social class

## How do we calculate DALYs?

**DALY = YLL + YLD**
YLL = years of life lost due to premature death
YLD = years lived with disability, due to nonfatal injury and illness

**YLL = N*L**

where N = number of deaths,
L = standard life expectancy at age of death, in years

**YLD = I*(DW)*L**
where I = number of incident cases,
DW = disability weight,
L = average duration of illness

### Years of life lost in DALYs

YLL is the number of years lost due to premature death
YLL accounts for deaths due to disease and injury
YLL varies by age and sex

### Disability weight in DALYs

based on:

- six different disability classes
- societal preferences of different health states

examples:

- migraine has low disability weight of 0.029, whereas severe COPD has DW of 0.530.
- blindness has a DW of 0.60

## Environmental burden of disease (EBD)

The assessment of EBD requires the following data:

- exposure assessment
- the distribution of risk factors exposure within the study pop
- the exposure-response relationship for the risk factor
- the DALYs lost to disease for the risk factor of interest

### Attributable risk/fraction

$Attributable Fraction (AF) = Sum of Pi * RRi - 1 / Sum of Pi* RRi$

where Pi = proportion of the pop at exposure category 'i', including the unexposed pop
RRi = relative risk at the exposure category 'i', compared to the reference level

### Determination of disease burden attributable to the risk

Dattrib = AF * (Dtotal)
where Dattrib = attributable disease burden
AF = attributable fraction
Dtotal = total disease burden in the pop

#### Example: Pneumonia (ALRI) attributable to household air pollution in India

1. Obtain exposure level data
   1. % of household using solid fuel
   2. example: 81% in India
   3. ventilation factor = 1
2. obtain disease burden data
   1. example: WHO disease burden data for India, 17.7 million DALYs lost from ALRI
3. the exposure-response relationship for the risk factor (ALRI)
   1. RR for ALRI from household air pollution exposure meta analysis = 2.3
4. Calculate the attributable fraction (AF)
   1. AF = (0.81 * 2.3 + 0.19*1) - 1)) / (0.81 * 2.3 + 0.19 * 1) = 0.51
5. Calcualte the attributable burden (AB)
   1. AB = AF * current disease level
   2. AB = 0.51 * 17.7 million DALYs lost
   3. AB ~= 9 million DALYs lost