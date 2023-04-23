---
title: Research
nav:
  order: 1
  tooltip: Projects we are working on
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Neuroprosthetics provide a unique opportunity to investigate the neural mechanisms of learning by enabling us to manipulate and measure neural activity in real-time. By modulating neural activity and providing sensory feedback, we gain insights into the specific neural circuits and mechanisms that underlie the acquisition and refinement of learned behavior. This information can be used to develop more effective interventions for individuals with learning impairments, as well as to enhance learning in healthy individuals.


{% include tags.html tags="publication, website" %}

{% include search-info.html %}

{% include section.html %}

# Featured

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

# Neuroprosthetic Learning
Learning is a complex cognitive process that is mediated by the coordinated activity of multiple brain areas and the recruitment of numerous neurons. Given this complexity, it is advantageous to simplify the neural circuitry under study in order to more effectively investigate the neural basis of learning. 

## What are the neural mechanisms underlying learning?
{% capture text %}
We aim to explore the fundamental principles underlying learning in a reduced and experimenter-defined neuronal circuit. To achieve this goal, we will employ a neuroprosthetic paradigm to elicit specific behaviors in restrained or freely behaving rodents. We will then manipulate the neural substrate of these behaviors using electrical or optical stimulation, and characterize the functional response both at the neural and behavioral level.

Our overarching objective is to gain a deeper understanding of how the brain reinforces neural patterns and acquires new cognitive skills, and how these processes can be modulated through neuro-stimulation. Through this investigation, we hope to shed light on the neural mechanisms underlying learning and pave the way for the development of novel therapeutic interventions for cognitive disorders.

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/neuroprosthetic_task.png"
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
To achieve real-time control over neural function, it is essential for neuro-engineering solutions to evolve towards more effective bi-directional communication between biological and artificial systems when studying and perturbing neuronal circuits. However, the identification and selective stimulation of appropriate neurons or precise neurotransmitter signaling can be challenging in a constantly evolving network-wide activity.

The potential advantages of unsupervised learning algorithms for controlling the stimulation of single neurons or dopamine receptors have yet to be fully explored. To address this, we develop new experimental protocols utilizing closed-loop strategies, which can select and drive the most effective neuro-stimulation for studying, perturbing, and enhancing neural reinforcement.

{%
  include button.html
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/optimizing.png"
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
  image="images/bmi_bwg_3_a_small.png"
  flip=true
  text=text
%}




