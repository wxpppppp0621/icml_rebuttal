# Supplementary Material for ICML Submission #9278

This repository contains supplementary results for our ICML submission **#9278**, providing additional visual comparisons and qualitative results.

## **Contents**

* **compare.pdf**

  This document presents a visual comparison between our method and two baselines: *Holodeck* and *InstructScene*.

  We did not include visual comparisons with the following methods for the reasons below:
	* Chat2Layout: Not open-sourced
	* AnyHome: Partially released, but not fully open-sourced, making fair comparison difficult
	* LayoutGPT: Use a special prompt format that is inconsistent with the input used in other experiments

* **rgb_input_result.pdf**

  Contains additional qualitative results of our method given **RGB images as input**.

  Each example includes:

  * An input RGB image
  * The  corresponding 3D scene generated by our method

* **sketch_input_result.pdf**

  Contains additional qualitative results of our method given **hand-drawn sketches as input**.

  Each example includes:

  * An input sketch
  * The  corresponding 3D scene generated by our method

* **vs_holodeck.png**

  This image shows a table comparing the performance of our method against Holodeck in terms of three metrics: **OOB**, **ORI**, and **CLIP-Sim**. 
