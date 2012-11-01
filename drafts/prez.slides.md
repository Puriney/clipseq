Directly Identify RNA-RBP Interactions in Genome-wide Scale
============================================================

HITS-CLIP

- - -

HITS-CLIP (or CLIP-seq)
=============

**HIT**hroughput **S**equencing of RNAs isolated by **C**rosslinking **I**mmuno**P**recipitation

- - -

Boring Definition

- - -

Well, for short

- - -

CLIP-seq = Chip-seq
====================

but, RNA version :P

- - -

CLIP-seq = CLIP + Sequencing
==============================

- - -

Standard CLIP-seq Pipeline
------------------------------

<img src="images/CLIP-seq.png" >

UV-Crosslink -> IP -> Purify -> Sequencing

- - -

Why CLIP?
==========

- - -

Identify candidate target RNA
------------------------------

- RIP-Chip, indirect or non-phisiological interactions

- UV-Crosslink and IP, Direct interactions

- - -

What Will CLIP-seq Date Offer? 
==============================

- - -

Precise Binding Position
=========================

Besides candidate target RNA motif

<img src="images/candidate-motif.jpg">

Robert B. Darnell, etc. CLIP identifies Nova-Regulated RNA networks in the brain. Science. 2003. 

- - -

Potentially recuited to machinery
=======================================

<img src="images/potentially_recuited_to_machinery.jpg">

Tag detected + Significant difference between Ctrl/Knock-out: 

It is indicated that NOVA is recuited to influence splicing. 

Robert B. Darnell, etc. CLIP identifies Nova-Regulated RNA networks in the brain. Science. 2003. 

- - -

CLIP Update
============

- iCLIP

- PAR-CLIP

- - -

individual-nucleotide resolution CLIP
=====================================

- - -

<video width="600" controls="controls">
	<source src="http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3169244/bin/jove-50-2638.mov" type="video/mov">
	Your Browser Does not support Html5, please update your browser. 
</video>

iCLIP - Transcriptome-wide Mapping of Protein-RNA Interactions with Individual Nucleotide Resolution. J Vis Exp. 2011. 

- - -

<img src="images/iCLIP_pipeline.jpg">

- - -

Classic CLIP:
-------------

- cDNAs truncate prematurely at the crosslinked nucleotide
- Truncated cDNAs are lost during the standard CLIP library preparation protocol

iCLIP:

More efficient intramolecular cDNA circularization 

- - -

Photoactivatable-Ribonucleoside-Enhanced Crosslinking and Immunoprecipitation
===============================================================================

- - -

<video width="600" controls="controls">
	<source src="http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3156069/bin/jove-41-2034.mp4" type="video/mp4">
	Your Browser Does not support Html5, please update your browser.
</video>

PAR-CliP - A Method to Identify Transcriptome-wide the Binding Sites of RNA Binding Proteins, J Vis Exp. 2010.

- - -

Classic CLIP:
------------------

- Low efficiency of UV 254 nm RNA-protein crosslinking
- Difficult to separate UV-crosslinked target RNA segments from background non-crosslinked RNA fragments also present in the sample

PAR-CLIP:
-----------

Rely on 4-thiouridine (4-SU) and 6-thioguanosine (6-SG)

- UV 365 nm induces efficient crosslinking of photoreactive nucleoside-labeled cellular RNAs to interacting RBPs
- 4-SU: T->C transitions
- 6-SG: G->A mutations. The presense of the changes can be assessed during bioinformatic analysis, and make it possible to seperate them from the background of sequences derived from abundant cellular RNAs.

- - -

Summary
========

- HITS-CLIP (or CLIP-seq)
- Exact binding position
- Direct interaction, candiate target RNA
- iCLIP and PAR-CLIP

- - -

<img src="images/logo-bonnie-basepairing.jpg">

Check source code at: [https://github.com/Puriney/clipseq](https://github.com/Puriney/clipseq)




















