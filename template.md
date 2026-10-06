Xindi Tao (date)

# Today's goal

1. I broke down our previous discussions into three projects. They are meant to be specific enough to turn into small
   research papers, or combined into a bigger one.
    1. Project 1: I can finish the first draft fast, but I don't have a conference/journal in mind (NICE?).
    2. Project 2: Aim for NICE 2027, deadline Nov 11th. Topic: Bio-Inspired Sensing $\rightarrow$ Event-Driven Sensing.
       Deadline approaching, this should be prioritized.
    3. Project 3: Aim for ECC 2027, deadline Oct 31st. Topic: Biological systems (?), Robust control (?).
2. I went deep into the first project: E coli motor movement. I wrote arguments for the Introduction (research gap,
   research question, significance), a working model (explained in Methods and tested in Results). I want to know
   whether I'm on the right track to turn this into a paper.
3. I pushed back writing the FYR supplements. I want to know where do I receive the decision to resubmit, and when to do
   so.

# Projects

- E coli flagella movement resembles a spike
- Spiking proprioception
- Spiking motor neuron activity

## Project name

### Introduction

#### Research question

#### Research gap

#### Importance

### Methods

#### Models

#### Assumptions

#### Analysis scheme

#### 🤔To be resolved

### Results

### Discussion

## 1. E coli

### Introduction

#### Research question

The question is whether E coli's motor signal resembles that of a spike.

#### Research gap

We ask this question because a spike is fundamental to living organism motion, both single cell (paramecium) and
multi-cellular. (Spikes are discrete signals over continuous time.) However, because the signals are of different
types (electrical vs chemical), it is difficult to compare the essence of the signals from E coli and a
neuron/paramecium.

Here, we categorize both into the class "event", and emphasize its property of 'start and finish' and maybe robustness.
We distinguish the two by comparing their time-scales and thresholds.

An event is a core concept to neuromorphic compute. We aim to add one more example to the 'event' concept, and emphasize
slow chemical signals, not just spikes, are events. In the future an event can be defined at faster/slower timescales,
composed of multiple events. All these events have patterns to them. We are looking for the patterns.

#### Importance

![ecoli_ramp_1d-duration=20-seed=7.png](../../2025-26/PythonProject/260907%20E_COLI/tu_paper/artifacts/ecoli_ramp_1d-duration%3D20-seed%3D7.png)
![ecoli_ramp_1d-duration=20-seed=7-x0=100.png](../../2025-26/PythonProject/260907%20E_COLI/tu_paper/artifacts/ecoli_ramp_1d-duration%3D20-seed%3D7-x0%3D100.png)

#### 🤔To be resolved

### Methods

#### Models available

Tu, ..., Berg, 2007: Maps Aspartate concentration to CheY-P (phosphorylated CheY) activity. But CheY-P to flagella
state (
CW, or
CCW) is missing.

Alon 2019: Used in 4G7. Cites (Tu 2007), but it is simplified.

Vladimirov, ..., Sourjik, 2008: Maps Aspartate concentration to CheY-P, then maps CheY-P to motor. But CheY-P is not
dynamical (not a state
variable) and is simplified. This simplification makes pulse response inaccurate in shape.

**Connection**: The authors know each other. Victor Sourjik and worked with Howard Berg. Uri Alon worked with Stanislas
Leibler. I infer their models are similar.

**Difference**: The three models have the same narrative: take in attractant concentration ([Asp]), output motor
activity or its indicator (CCW bias or CheY-P activity). All take into account the slow receptor adaptation, which is
good. (Vlad 2008) didn't care about turning CheY-P into a dynamic variable; it did so intentionally so that it can save
time running the simulation (thus the model name 'RapidCell') - I want CheY-P to be a state variable, apart from that
it's good.

(Vlad 2008) and (Tu 2007) have different equations and parameter values (TODO: compare in a chart). I gathered my
version based on the following: (1) use one paper for most of the model (Vlad 2008); (2) change equations only when it's
necessary; (3) use simple over complex equations.

#### My model

#### Analysis scheme

### Results

### Discussion

## 2. Spiking proprioception

### Introduction

#### Research question

#### Research gap

#### Importance

### Methods

#### Models

#### Assumptions

#### Analysis scheme

#### 🤔To be resolved

### Results

### Discussion

## 3. Spiking motor neuron activity

### Introduction

#### Research question

#### Research gap

#### Importance

### Methods

#### Models

#### Assumptions

#### Analysis scheme

#### 🤔To be resolved

### Results

### Discussion



