# HSI-FrFRWKV: Fractional Fourier RWKV for Cross-scene Coastal Wetland Mapping on Hyperspectral Images

Wen-Shuai Hu, Guo-Liang Ren, Heng-Chao Li*, Xudong Zhao, Weiwei Sun, and Ran Tao

Paper web page: [HSI-FrFRWKV: Fractional Fourier RWKV for Cross-scene Coastal Wetland Mapping on Hyperspectral Images](https://ieeexplore.ieee.org/document/11657448).
___________

# Abstract:

Coastal wetlands have irreplaceable value in global ecological balance and biodiversity conservation, and hyperspectral images (HSIs) provide supports for their fine mapping and protection measure formulation. Due to the dynamic changes of wetlands, existing cross-domain classification methods usually ignored frequency and phase information of HSIs to struggle to cope with domain shifts caused by sensors, lighting, and phase changes, and transformer-based methods usually have the quadratic complexity. As such, Receptance Weighted Key Value (RWKV) with the linear complexity and parallel processing advantages is introduced to propose the first Fractional Fourier transform (FrFT) RWKV model for cross-domain wetland mapping of HSIs, namely (HSI-FrFRWKV). Firstly, an FrFT-RWKV block is designed, with heterogeneous token shift and FrFT-WKV attention mechanisms as its cores for multi-scale local context and global dependency learning. A hierarchical FrFT-RWKV network (FRNet) is then built to extract amplitude-phase modulated spatial-spectral features that have not been fully explored. Moreover, to better focus on frequency and structure information of HSIs, a parameter-free amplitude-phase learning method in the optimal domain between space and frequency domains (FAP loss) is designed as a consistency constraint, ensuring clarity and structure of predictions in FRNet. Finally, a bi-classifier adversarial network and a replay-based self-distillation learning method are devised to improve training stability for cross-domain wetland mapping. A public cross-domain classification dataset and two wetland mapping datasets are adopted, whose experimental results demonstrate that the proposed HSI-FrFRWKV outperform other state-of-the-art methods. Our source code will be available at https://github.com/WenshuaiHu/HSI-FrFRWKV.

Citation
---------------------
**Please kindly cite the papers if this code is useful and helpful for your research.**

Wen-Shuai Hu, Guo-Liang Ren, Heng-Chao Li*, Xudong Zhao, Weiwei Sun, and Ran Tao, "HSI-FrFRWKV: Fractional Fourier RWKV for Cross-scene Coastal Wetland Mapping on Hyperspectral Images," IEEE Transactions on Geoscience and Remote Sensing, to be pubished, 2026. doi: 10.1109/TGRS.2026.3724234.  <br>

@ARTICLE{11657448, <br>
  author={Hu, Wen-Shuai and Ren, Guo-Liang and Li, Heng-Chao and Zhao, Xudong and Sun, Weiwei and Tao, Ran}, <br>
  journal={IEEE Transactions on Geoscience and Remote Sensing},  <br>
  title={HSI-FrFRWKV: Fractional Fourier RWKV for Cross-scene Coastal Wetland Mapping on Hyperspectral Images},  <br>
  year={2026}, <br>
  volume={64}, <br>
  number={}, <br>
  pages={1-1}, <br>
  doi={10.1109/TGRS.2026.3724234}}

# Requirements
Ubuntu 22.04.5 LTS <br>
CUDA Version: 11.7 <br>
Pytorch Version: 2.0 <br>
Python Version: 3.10 <br>

# Note
System-specific notes
---------------------
Please refer to the file `requirements.txt` for the running environment of this code.

Contact Information:
--------------------

Wen-Shuai Hu: wshuswjtu@163.com<br>
He is currently a Lecturer with the School of Information Science and Technology, Southwest Jiaotong University, Chengdu, China. 
