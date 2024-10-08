---
title: Research
nav:
  order: 1
  tooltip: Projects we are working on
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Neuroprosthetics offer a unique opportunity to study the neural mechanisms of learning in real-time, allowing us to manipulate and measure neural activity with unmatched precision. By identifying the specific neural circuits and mechanisms that underlie learned behavior, we gain valuable insights that can be used to develop more effective interventions for those with learning impairments, as well as enhance learning in healthy individuals.


{% include tags.html tags="publication, website" %}

{% include search-info.html %}

{% include section.html %}

# Featured

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

# Neuroprosthetic Learning
Learning is a complex cognitive process mediated by the coordinated activity of multiple brain areas and the recruitment of numerous neurons. Given this complexity, simplifying the neural circuitry under study can more effectively investigate the neural basis of learning. 

## What are the neural mechanisms underlying learning?
{% capture text %}
We aim to explore the fundamental learning principles in a reduced and experimenter-defined neuronal circuit. To achieve this goal, we will employ a neuroprosthetic paradigm to elicit specific behaviors in restrained or freely behaving rodents. We will then manipulate the neural substrate of these behaviors using electrical or optical stimulation, and characterize the functional response both at the neural and behavioral level.


We aim to better understand how the brain strengthens neural patterns and learns new skills, as well as how we can influence these processes with neuro-stimulation. By digging into these areas, our goal is to uncover the neural mechanisms behind learning and open up new possibilities for treating cognitive disorders with neurotechnology.

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/studying_learning.png"
  text=text
%}

## How does dopamine release lead to learning?
{% capture text %}
Dopamine acts as a reinforcer of preferred behavior. However, the neural mechanisms by which this occurs remain unclear. To investigate this, we employ photo-pharmacology techniques to manipulate dopamine receptors and/or employ optical stimulation within dopaminergic regions. Specifically, we explore the impact of dopamine signaling on neuroprosthetic learning by selectively activating or inhibiting specific dopamine receptors within cell-type specific neurons in the cortex and striatum. Through these experiments, we will uncover the underlying mechanisms by which dopamine reinforces neural patterns and how this reinforcement ultimately leads to learning.

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/dopamine.png"
  flip=true
  text=text
%}


# Improving neuroprosthetics

## Optimizing neuro-stimulation paradigms
{% capture text %}
To achieve real-time control over neural function, neuro-engineering solutions must evolve towards more effective bidirectional communication between biological and artificial systems when studying and perturbing neuronal circuits. However, identifying and selectively stimulating appropriate neurons or precise neurotransmitter signaling can be challenging in a constantly evolving network-wide activity.

The potential advantages of unsupervised learning algorithms for controlling the stimulation of single neurons or dopamine receptors have yet to be fully explored. To address this, we develop new experimental protocols utilizing closed-loop strategies, which can select and drive the most effective neuro-stimulation for studying, perturbing, and enhancing neural reinforcement.

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/optimizing_stim.png"
  text=text
%}

## Artificially assisting the neural mechanisms of learning
{% capture text %}
We recently implanted a basic neuroprosthetic skill using single-neuron targeted stimulation in the motor cortex. Now, we want to determine the rules and limitations of artificially implanted skills by studying the underlying physiological changes in neural reinforcement that drive this artificial learning. Furthermore, we will investigate how to assist the brain in solving more complex learning tasks by guiding perturbations over specific neuronal ensembles causally linked to behavior. 
Recently, cell-specific neuro-stimulation has emerged as a possible therapy for neurodegenerative diseases.  We use closed-loop neuroprosthetic paradigms combined with neuro-stimulation with single-cell resolution, photo-pharmacology, and animal models of cognitive dysfunction to test and prototype neurotechnology-based solutions for these disorders.

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/assisting_learning.png"
  flip=true
  text=text
%}




