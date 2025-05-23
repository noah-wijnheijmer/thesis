
# Weekly Log – mHTT and CCT1 Colocalization Analysis Project

## Week of March 18–22, 2025
**Focus**: Plan of Action  
- Developed the Plan of Action, integrating earlier weeks of theoretical research.  
- Defined a clear research question and formulated sub-problems: segmentation, colocalization, and nuclear localization.  
- Made an effort to filter essential from non-essential content for clarity and focus.  
- ✅ *Outcome*: Coherent and targeted research plan established.

## Week of March 25–29, 2025
**Focus**: Orientation & Experimental Setup  
- Participated in a lab-specific assignment.  
- Set up file loading pipeline for `.lif` microscopy images.  
- Explored channel configurations across datasets.  
- ✅ *Outcome*: Dataset characteristics were mapped and aligned with project goals.

## Week of April 21–25, 2025
**Focus**: Initial Segmentation & Thesis Writing  
- Completed the Introduction and Background sections of the thesis.  
- Resolved .lif z-slice ordering error (conversion to .tiff).  
- Confirmed with Carolina that 3D data should be preserved for accuracy.  
- ✅ *Outcome*: Background fully drafted; foundational image-handling bug resolved.

## Week of April 28 – May 2, 2025
**Focus**: Requirements Engineering & Conceptual Design  
- Defined and prioritized system requirements using the MoSCoW method.  
- Designed first version of the Value Proposition Canvas.  
- Constructed a “Happy Flow” user journey from image loading to colocalization export.  
- ✅ *Outcome*: Conceptual prototype aligned with user needs and dataset constraints.

## Week of May 5–9, 2025
**Focus**: Pipeline Implementation — Phase I  
- Developed the initial thresholding and morphological filtering pipeline for aggregates.  
- Integrated basic colocalization metrics: Pearson’s and Manders’ coefficients.  
- Defined structural vs. intensity-based colocalization metrics (e.g., Dice coefficient).  
- ✅ *Outcome*: Python-based colocalization pipeline operational with visual outputs.

## Week of May 12–16, 2025
**Focus**: Prototype + Feedback Integration  
- Finalized GUI prototype screens and walkthrough logic.  
- Used Cellpose for initial segmentation masks of cells.  
- Conducted internal review presentation (May 14) and expert workshop (May 15).  
- Embedded feedback from Carolina and peers into next iterations.  
- ✅ *Outcome*: Prototype demonstrated; presentation validated current trajectory.

## Week of May 19–23, 2025
**Focus**: AI Integration and Final Analysis  
- Intensive programming and evaluation of multiple nnU-Net model variants.  
- Trained and deployed nnU-Net for segmenting mHTT and CCT1 across 3D stacks.  
- Validated spatial colocalization using segmentation-based Dice analysis.  
- Integrated Cellpose (for cells) + nnU-Net (for aggregates) for full analysis per z-slice.  
- ✅ *Outcome*: Fully functioning AI-driven colocalization pipeline with robust results.

## Deliverables Over Time
| Date        | Milestone                                  | Notes |
|-------------|--------------------------------------------|-------|
| Mar 22      | Plan of Action completed                   | Included theoretical framing |
| Apr 25      | Lif-to-TIFF issue resolved                 | Enabled 3D fidelity |
| Apr 30      | Functional requirements finalized          | MoSCoW priorities logged |
| May 2       | First version of colocalization pipeline   | Thresholding + correlation metrics |
| May 12      | GUI prototype finalized                    | Multi-step input + channel selection |
| May 14–15   | Internal presentation + workshop           | Feedback loop with experts |
| May 21      | Final AI-based segmentation deployed       | Full 3D output with validation |
