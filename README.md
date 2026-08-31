# Additive-Manufacturing-Decision-Tree

An industrial decision-tree framework designed to classify part designs and manufacturing strategies into distinct categories based on geometrical and processing boundaries.

> 📖 **Theoretical Foundation:** This classification framework is based on the concepts, arguments, and conclusions developed in the published book: **[Hybrid Additive Manufacturing Debate](https://doi.org/10.31224/7951)**.


## 📊 The Framework Flowchart
![Additive-Manufacturing-Decision-Tree](My-Second-Board.png)

## 🔍 How it Works

It relies on twin-boundary framework for additive manufacturing (AM), given in the aforementioned book. It has the following two boundaries:

### Boundary 1 (B1):
_A complex shape is preferred. A shape is complex if it has at least one microfeature and an overhang_.
### Boundary 2 (B2): 
 _Pre-processing, interlayer processing, and post-processing are not meant to change size and shape. If they change, the resulting process is hybrid AM_.
 

## 🔍 Explanation of Steps given in Flowchart

* **Reason 7** A complex shape is preferred in AM only when it is not sustainable and cost-effective to be made in conventional manufacturing.
* **Step **

### 2. B2: Manufacturing Strategy (Pure vs. Hybrid AM)
Once AM is deemed necessary, this section classifies the production method into **Pure AM** or **Hybrid AM** based on:
* **Substrate removal** requirements.
* **Interlayer processing** and its effect on part size/shape.
* **Post-processing** impacts and whether these steps are driven by strategy or AM limitations.

## 🚀 Usage & Citation
Use this decision tree during the early stages of **Design for Additive Manufacturing (DfAM)** to evaluate production feasibility and optimize manufacturing workflows.

If you use this framework or flowchart in your research, please reference the original text:
* **Book:** *Hybrid Additive Manufacturing Debate* 
* **Link:** [Access the publication here](https://doi.org/10.31224/7951)
