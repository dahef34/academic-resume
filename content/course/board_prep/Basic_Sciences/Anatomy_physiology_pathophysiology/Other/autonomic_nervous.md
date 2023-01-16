---
title: Autonomic nervous system
date: '2022-12-02'
type: book
weight: 1106
commentable: true
---

# Autonomic Nervous System


## Function

The ANS provides the body with control over vasculature, secretions, sweat glands, gastrointestinal motility, and temperature.  Depending on the source, it has 2-3 primary divisions being: sympathetic nervous system, parasympathetic nervous system, and (sometimes) the enteric nervous system.  The enteric nervous system is sometimes considered part of the ANS, but for the purposes of this review, I will not discuss it separatey.

## Sympathetic Nervous System

This is known as the "fight or flight" system.  These nerve fibers originate from thoracolumbar region in the spinal cord (T2-L3).  From the spinal cord, these nerves travel to a ganglion usually in the paravertebral region to synapse with a postganglionic nerve that travels to the final destination in the body.  The exception to this rule is the adrenal glands.

{{% callout note %}}
1.  Preganglionic fiber  --->  Acetylcholine
2.  Postganglionic fiber --->  Norepinephrine
{{% /callout %}}

{{% callout warning %}}
Postganglionic fibers that innervate sweat glands use Acetylcholine
{{% /callout %}}

{{< figure src="ans_innervation.png" caption="Wikimedia Commons https://commons.wikimedia.org/wiki/File:Blausen_0838_Sympathetic_Innervation.png" alt="Blausen 0838 Sympathetic Innervation" numbered="true" >}}


{{% callout warning %}}
SNS innervation of the adrenal glands bypasses the ganglion and directly synapses with the adrenal glands!
{{% /callout %}}



All other nerves in the SNS follow the short-long idiom.  Specific actions of the SNS include:
- Inhibit bowel movements and urination
- Increast heart rate and contractility
- Increase systemic vascular resistance
- Dilates pupils
- Dilates bronchioles
- Stimulates glucose release



{{< figure src="ans_effects.jpg" caption="ANS Effects" numbered="true" >}}


## Parasympathetic Nervous System

The parasympathetic nervous system is sometimes known as the "rest and digest" or "feed and breed" system.  It is responsible for: 
- Sexual Arousal
- Lacrimation
- Salivation
- Urination
- Defecation
- Digestion

{{< figure src="ans_para.jpg" caption="Wikimedia Commons https://upload.wikimedia.org/wikipedia/commons/f/f3/1503_Connections_of_the_Parasympathetic_Nervous_System.jpg" alt="Open Stax College" numbered="true" >}}

The vagus nerve (CN X) gives rise to over 75% of parasympathetic nerves.  These nerves travel directly to the target organ and as such have controlled and discrete responses.


## Adrenergic neurotransmitter synthesis

### Norepinephrine
Synthesis of norepinephrine requires 3 different conversions occuring in the cytoplasm of postganglionic SNS fibers.  Dopaming enters synaptic vesicles where it is converted into norepinephrine.

{{< figure src="adrenergic_synthesis.svg" caption="Wikimedia Commons https://commons.wikimedia.org/wiki/File:Catecholamines_biosynthesis.svg" alt="NEUROtiker" numbered="true" >}}

{{% callout info %}}
Exocytosis of norepinephrine is aided by Ca²⁺
{{% /callout %}}

Termination of action occurs by:
1. Reuptake (80%)
2. Diffusion from receptor
3. Metabolism (MAO & COMT)

### Common Receptors

```mermaid
classDiagram
    Adrenoreceptor --|> α1
    Adrenoreceptor --|> α2
    Adrenoreceptor --|> β1
    Adrenoreceptor --|> β2
    class α1{
      Vasoconstriction
      Increased peripheral resistance
      Increased Blood Pressure
      Mydriasis
      Difficult Urination
    }
    class α2{
      Inhibits NE release
      Inhibits insulin release
    }
    class β1{
      Tachycardia
      Lypolysis
      Increased Myocardial contractility
    }
    class β2{
      Vasodilation
      Bronchodilation
      Glycogenolysis
      Glucagon release
      Uterine relaxation
    }
```

```mermaid
graph TD
    A[Parasympathetic Preganglion]
    A --> |Acetylcholine| C[N1]
    A --> |Acetylcholine| D[M]

    E[Sympathetic Preganglion] -->|Acetylcholine| F{N1 Postganglion}
    F --> |Norepinephrine| G[α]
    F --> |Norepinephrine| H[β]
    F --> |Norepinephrine| I[D]

```