
# Logboek – mHTT and CCT1 Colocalization Analysis Project

## 📧 Communication Carolina:

---

**From:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Date:** Tuesday, 22 April 2025 at 15:14

**To:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Subject:** Questions regarding interpretation of microscopy images

Dear Carolina,

As an Applied Artificial Intelligence student at the Amsterdam University of Applied Sciences, I am looking at methods for using computer vision techniques to assess the interaction between the CCT1 chaperone and mutant huntingtin species.

I am having some issues with the stained images that have been provided. It is not clear to me where the CCT1 chaperone and the mutant huntingtin species can be seen in images of their respective channels, and thus I cannot really interpret the colocalization visually. To use computer vision to analyze this overlap, I would need to be able to determine the colocalization (and whether there is any) myself.

I suggest we sit together for a quick meeting to discuss the images and look at how I can interpret the stained data.

Please let me know when you’d be available for this.

---

**From:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Date:** Wednesday, 23 April 2025 at 14:52

**To:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Subject:** Re: Questions regarding interpretation of microscopy images

Hello Noah,

Thanks for reaching out! Attached here is a document that I previously sent to Jesse with information about the images and channels.
Please have a look carefully and hopefully it can help you. If you still would like to discuss the images, let me know and we can plan a quick meeting asap.

Best,
Carolina

---

**From:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Date:** Wednesday, 23 April 2025 at 15:41

**To:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Cc:** Jesse Antonissen <j.b.antonissen@hva.nl>

**Subject:** Re: Questions regarding interpretation of microscopy images

Hi Carolina,

Thanks for the attachment, I will take this into consideration. I am afraid that my questions are a bit more fundamental, however.

Therefore, I would like to book a meeting to discuss this at your earliest convenience.

To give you an idea of the questions I am facing about the project, here are some I currently have:

> In the fluorescence images, every region of the cell is illuminated to some extent.  
> Does this uniform illumination indicate that mutant huntingtin (mHTT) truly resides throughout the entire cell?  
> Or is it an artifact of the visualization method—such that brightness simply reflects mHTT density rather than its absolute presence?  

> How would one normally determine colocalization?  
> Since I am having trouble visually identifying where the presence of CCT1 and mHTT is significant in the picture, I am worried about the effectiveness of applying such a model.  
> Particularly, the CCT1 channel is hard to interpret (since the mHTT seems to be less prevalent in the nucleus than in the cytoplasm, and seems to clump up together more than the CCT1).

I think these questions are relevant to realistically assess the usefulness of this project and, moreover, to align the biological basis and importance with my methodology and hyperparameter tweaking.

I want to stress that any algorithm will be a product of the biases and interpretations of its creator. Therefore, clearly defining terms such as *aggregate* and *colocalization* is very important to ensure alignment and effectiveness.

Thank you for your time. Let me know if you are available to discuss this sometime soon.

Best regards,  
Noah Wijnheijmer

---

**From:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Date:** Wednesday, 23 April 2025 at 16:13

**To:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Cc:** Jesse Antonissen <j.b.antonissen@hva.nl>

**Subject:** Re: Questions regarding interpretation of microscopy images

Hello Noah,

I can meet today at 4:30pm, if that works for you.

Best,  
Carolina

---

**From:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Date:** Wednesday, 23 April 2025 at 16:39

**To:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Subject:** Re: Questions regarding interpretation of microscopy images

Sorry for the late reply, that works out!

---

**From:** Noah Wijnheijmer

**Date:** Thursday, 24 April 2025 at 09:00

**To:** Carolina Konrdorfer Rangel

**Subject:** (Follow-up)

Ok,

I have sent you the link.


---

**From:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Date:** Wednesday, 14 May 2025 at 18:48

**To:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Subject:** Quick question about µm per z-slice

Hi Carolina,

If I want to visualize in 3D, for an accurate representation, I’d need the µm per z-slice used on the microscope. Can you send me this info for the conducted experiments if you have it? If you don’t have it let me know, then I’ll have to make some assumptions.

Best regards,  
Noah

---

**From:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Date:** Thursday, 15 May 2025 at 09:20

**To:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Subject:** Re: Quick question about µm per z-slice

Hello Noah,

The size per Z-slice in µm (voxel depth) is from 0.40 µm to 0.5 µm for most images of experiment E35. If you need all the images taken with the same depth, the images taken on 20241812 have 0.4 µm. For other dates and experiments, you can get this information by opening the .lif file on Fiji and clicking on Image → Properties.

Best,  
Carolina


## 📧 Email Chain: Necessity of Cell Segmentation for Colocalization

---

**From:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Date:** Monday, 12 May 2025 at 15:50

**To:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Subject:** Necessity of Cell Segmentation for Colocalization

Hi Carolina,

Quick question — as I explore the AI-based analysis of CCT1 and mHTT colocalization, I realize that a solution could technically be implemented without explicit cell segmentation. However, I’m wondering whether you think cell segmentation is essential for the biological goals of my initial project?

Would skipping segmentation significantly reduce the interpretability or value of the results in your view?

Best,  
Noah Wijnheijmer

---

**From:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Date:** Monday, 12 May 2025 at 17:05

**To:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Subject:** Re: Necessity of Cell Segmentation for Colocalization

Hello Noah,

I think cell segmentation would be of great value but this is what Noah Le Roy is working on… so maybe you could speak to him and use what he is developing in your project? It makes no sense that all of you have to do the same task 3 times… If that is not done yet, I would focus on the colocalization which is the main goal of your project. Later on we could think on how to combine the cell segmentation with that.

Best,  
Carolina


# 📧 Email Chain: Request for Annotated Example Images of Colocalization

---

**From:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Date:** Thursday, 24 April 2025 at 16:01

**To:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Subject:** Request for Annotated Example Images of Colocalization

Dear Carolina,

Thank you again for the call yesterday.

I would greatly appreciate it if you could share a few annotated example images in which you have manually identified colocalization between Huntington and CCT1. This would help me understand what to look for, particularly since the CCT1 channel appears quite diffuse in the images I’ve seen—making it difficult to distinguish true signal from noise.

Once I have a clearer reference, I’ll develop an algorithm to automatically detect colocalization in these images. I’ll then apply it to a broader set of data and share the results with you to ensure alignment.

Best regards,  
Noah Wijnheijmer

---

**From:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Date:** Thursday, 24 April 2025 at 17:20

**To:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Subject:** Re: Request for Annotated Example Images of Colocalization

Hello Noah,

On these slides I have some annotation of different aggregates and colocalization. I hope it helps. And otherwise let me know and I can annotate more images next week.

Best,  
Carolina


# 📧 Email Chain: Manual Colocalization Video Review

---

**From:** Noah Wijnheijmer <noah.wijnheijmer@hva.nl>

**Date:** Monday, 12 May 2025 at 11:51

**To:** Carolina Konrdorfer Rangel <c.konrdorferrangel-2@prinsesmaximacentrum.nl>

**Subject:** Manual Colocalization Video Review

Hi Carolina,

I made a video of what a manual colocalization in Fiji might look like. Can you maybe review this briefly and let me know if this makes sense? If this is not really in line with the methodus operandi used within the field, let me know.

*Image Screen Recording 2025-05-12 at 11.51.35.mov*
https://icthva-my.sharepoint.com/personal/noah_wijnheijmer_hva_nl/_layouts/15/stream.aspx?id=%2Fpersonal%2Fnoah%5Fwijnheijmer%5Fhva%5Fnl%2FDocuments%2FAttachments%2FScreen%20Recording%202025%2D05%2D12%20at%2011%2E51%2E35%2Emov&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6e9230f7%2D4b89%2D4e76%2Dab1b%2D5ef1958ff720 

Thanks in advance, and have a great day.

Best regards,  
Noah Wijnheijmer





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
- Constructed a happy flow and error flow from image loading to colocalization export.
- Experimented the capabilities currently available on FIJI and made flows for the manual mathod. Also recorded a video displaying the manual colocalization analysis to send to Carolina for validation. (https://icthva-my.sharepoint.com/personal/noah_wijnheijmer_hva_nl/_layouts/15/stream.aspx?id=%2Fpersonal%2Fnoah%5Fwijnheijmer%5Fhva%5Fnl%2FDocuments%2FAttachments%2FScreen%20Recording%202025%2D05%2D12%20at%2011%2E51%2E35%2Emov&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6e9230f7%2D4b89%2D4e76%2Dab1b%2D5ef1958ff720)
- ✅ *Outcome*: Conceptual prototype aligned with user needs and dataset constraints.

## Week of May 5–9, 2025
**Focus**: Pipeline Implementation — Phase I  
- Developed the initial thresholding and morphological filtering pipeline for aggregates.  
- Integrated basic colocalization metrics: Pearson’s and Manders’ coefficients.  
- Defined structural vs. intensity-based colocalization metrics (e.g., Dice coefficient).
- experimented with 3D visualization setup using Napari
- ✅ *Outcome*: Initial python-based colocalization pipeline operational with visual outputs.

## Week of May 12–16, 2025
**Focus**: Prototype + Feedback Integration  
- Finalized GUI prototype screens and walkthrough logic.  
- Used CellposeSAM for initial segmentation masks of cells.  
- Conducted internal review presentation (May 14).  
- Embedded feedback from Carolina and peers into next iterations.  
- ✅ *Outcome*: Prototype demonstrated; presentation validated current trajectory.

## Week of May 19–23, 2025
**Focus**: AI Integration and Final Analysis  
- Intensive programming and evaluation of multiple nnU-Net model variants.  
- Tested nnU-Net for segmenting mHTT and CCT1 across 3D stacks.  
- Validated spatial colocalization using segmentation-based Dice analysis.  
- Integrated Cellpose (for cells) + nnU-Net (for aggregates) for full analysis per z-slice.  
- ✅ *Outcome*: Fully functioning POC AI-driven colocalization pipeline with results.

## Deliverables Over Time
| Date        | Milestone                                  | Notes |
|-------------|--------------------------------------------|-------|
| Mar 22      | Plan of Action completed                   | Included theoretical framing |
| Apr 25      | Lif-to-TIFF issue resolved                 | Enabled 3D fidelity |
| Apr 30      | Functional requirements finalized          | MoSCoW priorities logged |
| May 2       | First version of colocalization pipeline   | Thresholding + correlation metrics and 3D visualization setup  |
| May 12      | GUI prototype made using SpotitPy                    | Multi-step input + channel selection |
| May 14–15   | Internal presentation + workshop           | Feedback loop with experts |
| May 21      | AI-based segmentation proof of concept       | 3D output and metrics |
