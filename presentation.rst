:skip-help: true
:css: static/bootstrap/css/bootstrap.min.css
:css: static/presentation.css

.. title:: Expectations in music

----

:class: main-step

Expectations in music
=====================

Tom Gurion - PhD MAT student

----

Papers
======

**Palmer & Krumhansl 1987** Independent Temporal and Pitch Structures in Determination of Musical Phrases

**Palmer & Krumhansl 1987** Pitch and temporal contributions to musical phrase perception: Effects of harmony, performance timing, and familiarity

**Parmentier et al. 2011** Why are auditory novels distracting? Contrasting the roles of novelty, violation of expectation and stimulus change

----

Context
=======

TODO

**Perceptual independence vs. perceptual interaction**

  If responses to two components have zero correlation across subjects and if responses to the combined components equal the sum of responses to the individual components (performance parity), then perceptual independence of the two individual components is assumed. Perceptual interaction of a unit or whole is defined operationally as the failure to attend selectively to individual parts.

  -- Palmer & Krumhansl 1987a

----

:class: main-step

Palmer & Krumhansl 1987
=======================

*Independent Temporal and Pitch Structures in Determination of Musical Phrases*

----

:data-y: r1500
:data-x: r0

Research questions
==================

- How does temporal and pitch elements contribute to the perception of a melody?
- Are temporal and pitch perceptual independent?

----

Experiment 1
============

**Stimuli**

.. image:: media/palmer1_exp1_stimuli.png

.. raw:: html

  <audio controls="controls">
    <source type="audio/mp3" src="media/bach_bwv865.mp3"></source>
  </audio>

----

**Independent variables:**

- Condition - temporal, pitch, or melody.
- Ending note - any note from the 2nd phrase.

**Dependent variable:**

- Judgment of "completeness" of the phrase on a scale of 1 to 7.

----

Results
=======

.. image:: media/palmer1_exp1_results.png

----

- Main effect for ending note.
- No main effect for condition.
- Significant interaction between ending note and condition.
- Significant correlation between melody and other conditions.
- No correlation between temporal and pitch conditions.
- No effect of musical background.
- Completeness judgment correlated with the predicted tonal stability of the last note (Krumhansl & Kessler 1982) for the melody and pitch conditions.

.. note::

  - Only musicians.
  - Last note influence is problematic.

----

**Surprisingly,**

the melodic rating profile can be linearly computed from the temporal and pitch profiles!

.. image:: media/palmer1_exp1_model.png

**Conclusion:** temporal and pitch components are perceptual independent!

----

Experiment 2
============

Addresses criticism on experiment 1 design:

- Temporal and pitch condition were not musical.
- The ending note contributed too much to the judgment.
- Order of conditions (melody first) affected judgment of other conditions.

----

**Stimuli**

.. image:: media/palmer1_exp2_stimuli.png

----

Results
=======

.. image:: media/palmer1_exp2_results.png

Results agree with experiment 1: same main effects and same model for deriving melody profile from other conditions.

----

:class: main-step
:data-x: 6400
:data-y: 0

Palmer & Krumhansl 1987
=======================

*Pitch and temporal contributions to musical phrase perception: Effects of harmony, performance timing, and familiarity*

----

:data-y: r1500
:data-x: r0

**Differences from previous study:**

- New musical excerpt (Mozart K. 331 piano sonata), now includes harmonic part.

.. image:: media/palmer2_excerpt.png

.. raw:: html

  <audio controls="controls">
    <source type="audio/mp3" src="media/mozart_k331.mp3"></source>
  </audio>

- Familiarity with the musical excerpt taken into account.
- Analysis of correlations with tonal predictions from Krumhansl & Kesler 1982.
- Analysis of correlations with metrical accent predictions from Lerdahl & Jackendoff 1983.
- Analysis of correlations with time-span (grouping) predictions from Lerdahl & Jackendoff.

----

Experiment 1 results
====================

In line with experiment 1 results from the previous study. In addition:

- For familiar listeners pitch and temporal conditions correlate.
- Tonal predictions are highly correlated with pitch and combined conditions.
- Metrical accent predictions are highly correlated with temporal and combined condition for unfamiliar listeners and with temporal condition for familiar listeners.
- Time-span (grouping) predictions are highly correlated with combined condition.

----

Experiment 2 results
====================

In line with experiment 2 results from the previous study. In addition:

- Tonal predictions are highly correlated only with pitch condition for familiar listeners.
- Metrical predictions are highly correlated with temporal and combined conditions.
- Time-span predictions are highly correlated with combined condition.

Minor difference:

- Temporal condition response is now correlated with pitch condition response

----

Experiments 3 & 4
=================

Same as experiments 1 & 2 but with live performance durations. Generally, got the same results. Correlations with predictions varied.

----

Conclusions (both studies)
==========================

TODO first study conclusions.

As in Palmer & Krumhansl 1987a, with minor addition: "the relationship between pitch and temporal components differed with familiarity with the music... When one component was presented without the other, listeners familiar with the excerpt reported imagery for the missing component and tended to have higher correlations between pitch and temporal ratings than did listeners unfamiliar with the excerpt".

----

Criticism
=========

No explanations why correlations with predictions got different significance between experiments.

About stats: the authors conclude that all experiments support the same general ideas. If they were collapsing the data across experiments they will get much less significance between predictions and data, but the significant correlations will be more reliable. In general, it look like they measure significance of each correlation by it own, without balancing the measurements.

This study is more complicated than 1987a and therefore introduce more issue. Thereby, 1987a looks nicer, but maybe it's just the simplicity. Overall, 1987b have no major added value.

----

Discussion
==========

----

.. Back to horizontal baseline

:class: main-step
:data-x: 8000
:data-y: 0

Parmentier et al. 2011
======================

*Why are auditory novels distracting? Contrasting the roles of novelty, violation of expectation and stimulus change*

----

:data-y: r1500
:data-x: r0

Research questions
==================

- What do we perceive as a novel sound?
- Contrasting 3 hypotheses for novelty perception.

----

1. The base-rate probability hypothesis
=======================================

  The repeated presentation of the standard sound results in the building up of a neural model with which incoming stimuli are compared.

  A rare event, by clashing with the memory trace of a frequent one, triggers the orientation of attention towards novelty.

Implies that there are no local effects.

----

2. The expectation hypothesis
=============================

  A sound should distract participants (...) whenever it violates the participant's expectation, irrespective of whether that sound is frequent or not.

  The cognitive system uses its incidental knowledge of conditional probabilities to predict future events.

Implies that expectations **do** take local events into account.

----

3. The local perceptual change hypothesis
=========================================

  Distraction should be observed whenever change occurs from one trial to the next, irrespective of the sounds involved, and regardless of their base-rate probability and predictability.

----

Experiment
==========

**Method**

- Presenting a standard (sine wave, 75% of the occurrences) or novel (white noise) sound.
- Visually presenting a number.
- Participants decide if the number is odd or even, as fast as possible.

----

**Novel sounds distribution**

8 out of 9 novel sounds were presented as consecutive pairs, creating 6 stimuli conditions.

.. image:: media/parmentier_stimuli.png

----

.. class:: table table-striped thead-inverse

  +----------------+----------+---------------------+-----------+-----------------------+
  |Preceding sounds|Next sound|Base-rate probability|Expectation|Local perceptual change|
  |                |          |prediction           |prediction |prediction             |
  +================+==========+=====================+===========+=======================+
  |SS              |S         |.75                  |.81        |1                      |
  +----------------+----------+---------------------+-----------+-----------------------+
  |SS              |N         |.25                  |.19        |0                      |
  +----------------+----------+---------------------+-----------+-----------------------+
  |SN              |S         |**.75**              |**.20**    |0                      |
  +----------------+----------+---------------------+-----------+-----------------------+
  |SN              |N         |**.25**              |**.80**    |1                      |
  +----------------+----------+---------------------+-----------+-----------------------+
  |NN              |S         |.75                  |.1         |0                      |
  +----------------+----------+---------------------+-----------+-----------------------+

----

Results
=======

.. image:: media/parmentier_results.png

**The model**

A linear model of 4 parameters: the mean response time per participant, and the "distraction" for each theory (a stimuli get the value of 0 if it is predicted by the theory and 1 otherwise). The base-rate theory is insignificant for the model!

----

Criticism
=========

- The analysis use only correct responses for the digit parity test. What about incorrect responses?
- Why the expectation hypothesis "remembers" two preceding events? What about the first order?
- The model of choice. Why not linear regression of prediction profiles?

----

Discussion
==========
