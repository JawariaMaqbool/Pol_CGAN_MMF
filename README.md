# Pol_CGAN_MMF
This Repository contains code and data links for the article 'Towards optimal multimode fiber imaging by leveraging input polarization and deep learning':https://www.sciencedirect.com/science/article/pii/S1068520024002414?dgcid=coauthor.
You can download data from Google Drive links. The train and test data are for only one polarization state and fiber position, where we got maximum SSIM on test data. MNIST's full data file contains labels.
The Jupyter Notebook contains the full-length code.
If you find this code and data helpful, please cite our paper :
@article{MAQBOOL2024103896,
title = {Towards optimal multimode fiber imaging by leveraging input polarization and deep learning},
journal = {Optical Fiber Technology},
volume = {87},
pages = {103896},
year = {2024},
issn = {1068-5200},
doi = {https://doi.org/10.1016/j.yofte.2024.103896},
url = {https://www.sciencedirect.com/science/article/pii/S1068520024002414},
author = {Jawaria Maqbool and Syed Talal Hasan and M. Imran Cheema},
keywords = {Multimode fibers, Input polarization, Deep learning, Imaging},
abstract = {Deep learning techniques provide a plausible route towards achieving practical imaging through multimode fibers. However, the results obtained by these methods are often influenced by various physical factors such as temperature, fiber length, external perturbations, and the polarization state of the input light. While previous studies have explored the impact of these factors on deep-learning-enabled multimode imaging, the effects of input polarization remain largely unexplored. Here, we experimentally demonstrate that the polarization state of light injected at the input of a multimode fiber significantly affects the fidelity of reconstructed images from speckle patterns. Certain polarization states produce high-quality images at fiber output, while some yield degraded results. To address this, we have developed a conditional generative adversarial network (CGAN) capable of regenerating images under various degrees of input light polarization. Our model stands out by achieving an SSIM score over 0.9 with a 50μm multimode fiber and demonstrating superior performance in both short training (1 h) and inference times (9.4 ms), unlike earlier research that primarily focused on multimode fibers larger than 50μm. Furthermore, our results demonstrate that the model can be trained to produce adequate imaging results for all input light polarization states, even with bends or twists in the fiber. We believe that our findings represent a significant step towards developing high-resolution and minimally invasive multimode fiber endoscopes.}
}
