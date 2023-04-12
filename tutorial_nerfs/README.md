# Tutorial Materials for Neural Fields

Here are some materials for the tutorial on Neural Fields.

> Neural Fields (NerFs) are an emerging class of coordinate-based neural networks. There has been many developments in the last few years for applying NerFs to data like images. In this tutorial, I will introduce NerFs from the geoscience perspective and highlight some potential advantages to using these methods. I will demonstrate some concrete work on sea surface height interpolation and highlight some of the problems (and potential solutions) I faced when applying this class of methods to spatiotemporal data.


---

## Slides

Again, quite heavy. But the presentation can be found here:

[![Presentation](https://img.shields.io/badge/iCloud-3693F3?style=for-the-badge&logo=iCloud&logoColor=white)](https://www.icloud.com/keynote/0377aKbghKn7D54oJbJCLt2Cw#nerfs%5Fprezi)



---

## Code

The code is a bit heavy so I won't upload it to this repo. However, everything is open source and I'll work on reducing the data and pipeline over the next few weeks. This is all in preparation for a manuscript and upcoming presentations. 

---

### **Tutorial I**: Canonical Image Data

[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/jejjohnson/jejeqx/blob/master/notebooks/dev/nerfs/1.1_naive_nerfs.ipynb)

> In this notebook, we go step-by-step showcasing a simple NerF applied to the canonical image. I showcase why the standard NerF fails and which other methods do better.

---

### **Tutorial II**: Spatial Sea Surface Height Simulations

[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/jejjohnson/jejeqx/blob/master/notebooks/dev/nerfs/1.2_gradients.ipynb)

> In this notebook, I go over how the same models fair when applying to sea surface height simulations from NEMO. This data has different properties and we have physical understanding of the system - all through the lens of gradients.

---

### **Tutorial III**: Spatial-Temporal Sea Surface Height Simulations

[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/jejjohnson/jejeqx/blob/master/notebooks/dev/nerfs/1.3_spatiotemporal.ipynb)


> In this notebook, I up the intensity a bit and demonstrate how the NerFs fair for a year-long simulation of sea surface height from NEMO over the North Atlantic. We use the same metrics but modify them to account for the temporal dimension.

