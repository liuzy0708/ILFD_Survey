# Awesome_incremental_learning_fault_diagnosis

A curated **awesome list** of papers on **Incremental Learning-Enabled Fault Diagnosis (ILFD)** / **Incremental Fault Diagnosis** for dynamic industrial systems.

> **Source taxonomy & paper pool**: the list is organized following the taxonomy and the paper pool in  
> **Zeyi Liu, Xiao He, Biao Huang, Donghua Zhou**, *Incremental Learning-Enabled Fault Diagnosis of Dynamic Systems: A Comprehensive Review*, **IEEE Transactions on Cybernetics**, 2025.  
> DOI: `10.1109/TCYB.2025.3586643`


---

## Taxonomy / 分类框架

This repo categorizes ILFD papers along **two primary dimensions**:

1) **Update deployment time**
- **Incremental Online Learning**: update the diagnostic model *during* online operation.
- **Incremental Offline Learning**: update the model offline (task-level / batch-level), then deploy when conditions are met.

2) **What changes**
- **Fault Distribution Drifts**: data distribution shifts due to condition/environment changes, degradation, etc.
- **Novel Fault Modes**: new/unseen fault types emerge during deployment.

---

## Paper List / 论文列表

> Only three fields are listed per paper: **Paper title**, **Venue (journal/conference)**, **Year**.

### Incremental Online Learning — Fault Distribution Drifts
| Paper | Venue | Year |
|---|---|---:|
| Board-level functional fault diagnosis using multikernel support vector machines and incremental learning | IEEE Trans. Comput.-Aided Design Integr. Circuits Syst. | 2014 |
| Intelligent fault diagnosis of roller bearings with multivariable ensemble-based incremental support vector machine | Knowl.-Based Syst. | 2015 |
| Incremental supervised locally linear embedding for machinery fault diagnosis | Eng. Appl. Artif. Intell. | 2016 |
| Incremental fault diagnosis: Exploiting unlabelled data with semi-supervised ensemble learning | Proc. 13th IEEE Int. Conf. Electron. Meas. Instrum. (ICEMI) | 2017 |
| An online incremental support vector machine for fault diagnosis using vibration signature analysis | Proc. IEEE Int. Conf. Ind. Technol. (ICIT) | 2018 |
| Analytical incremental learning for power transformer fault diagnosis | Proc. 5th Int. Conf. Sci. Technol. (ICST) | 2019 |
| A fault diagnostic method for induction motors based on incremental learning in nonstationary environments | IEEE Access | 2019 |
| Incremental semi-supervised kernel PCA and mutual information based algorithm for fault diagnosis | IEEE Trans. Ind. Electron. | 2019 |
| A learning to learn method for bearing fault diagnosis under different working conditions | IEEE Trans. Instrum. Meas. | 2019 |
| Online semi-supervised broad learning system for fault diagnosis of rotating machinery | IEEE Trans. Ind. Informat. | 2021 |
| Application of incremental support vector regression based on optimal training subset and improved particle swarm optimization algorithm in real-time sensor fault diagnosis | Appl. Intell. | 2021 |
| Semisupervised incremental learning based on an ensemble of two channels for industrial process fault diagnosis | IEEE Trans. Ind. Informat. | 2022 |
| A multi-sensor fused incremental broad learning with DS theory for online fault diagnosis of rotating machinery | Adv. Eng. Inf. | 2024 |
| Adaptive online broad learning system for bearing fault diagnosis under time-varying working conditions | IEEE Trans. Ind. Informat. | 2024 |

### Incremental Online Learning — Novel Fault Modes
| Paper | Venue | Year |
|---|---|---:|
| Dynamic weighting ensembles for incremental learning and diagnosing new concept class faults in nuclear power systems | IEEE Trans. Nucl. Sci. | 2012 |
| Online fault diagnosis method based on incremental support vector data description and extreme learning machine with incremental output structure | Neurocomputing | 2014 |
| Incremental classiﬁers for data-driven fault diagnosis applied to automotive systems | IEEE Access | 2015 |
| Adaptive incremental ensemble of extreme learning machines for fault diagnosis in induction motors | Proc. Int. Joint Conf. Neural Netw. (IJCNN) | 2017 |
| Novel class-incremental fault detection and diagnosis scheme based on statistical analysis and cosine similarity | IFAC-PapersOnLine | 2019 |
| An incremental model transfer method for complex dynamic process fault diagnosis with verification delay | IEEE/CAA J. Automatica Sinica | 2019 |
| Online fault diagnosis method based on Bayesian incremental learning | Neurocomputing | 2020 |
| Class-incremental learning for fault diagnosis of intelligent machinery with unlabeled condition monitoring data | IEEE Trans. Ind. Informat. | 2020 |
| Deep semi-supervised class-incremental learning for fault diagnosis of rotating machines | IEEE Trans. Ind. Informat. | 2022 |
| Deep semi-supervised incremental learning for machinery fault diagnosis in nonstationary environments | IEEE Trans. Ind. Informat. | 2023 |
| A semi-supervised class incremental method for bearing fault diagnosis | Mech. Syst. Signal Process. | 2024 |

### Incremental Offline Learning — Fault Distribution Drifts
| Paper | Venue | Year |
|---|---|---:|
| A data-driven incremental learning method for fault diagnosis in power transformers | IEEE Trans. Power Del. | 2018 |
| Fault detection and identification methodology under an incremental learning framework applied to industrial machinery | IEEE Access | 2018 |
| Dynamic deep learning algorithm based on incremental compensation for intelligent fault diagnosis | Int. J. Comput. Intell. Syst. | 2018 |
| Fault diagnosis of TE process based on incremental learning | Proc. 39th Chin. Control Conf. (CCC) | 2020 |
| Fault diagnosis based on deep learning under incremental learning framework for industrial process | IEEE Access | 2021 |
| Bearing fault diagnosis via incremental learning and lightweight model: A new strategy to deal with varying working conditions | Machines | 2022 |
| Task-incremental broad learning system for multi-condition fault diagnosis | Knowl.-Based Syst. | 2022 |
| A deep learning-based incremental fault diagnosis framework for rotating machinery | IEEE Trans. Ind. Informat. | 2022 |
| An incremental learning method for bearing fault diagnosis under variable working conditions | IEEE Trans. Ind. Informat. | 2024 |
| Multiscale incremental learning network for bearing fault diagnosis under varying working conditions | Mech. Syst. Signal Process. | 2024 |
| A novel domain incremental learning method for bearing fault diagnosis based on F&K | IEEE Trans. Ind. Informat. | 2025 |
| Transformer incremental fault diagnosis method using lossless estimation and balanced training | IEEE Trans. Power Del. | 2025 |

### Incremental Offline Learning — Novel Fault Modes
| Paper | Venue | Year |
|---|---|---:|
| Deep learning with emerging new labels for fault diagnosis | IEEE Access | 2018 |
| A deep-neural-network-based fault diagnosis for chemical processes with multiple faults | IEEE Trans. Ind. Informat. | 2019 |
| A new deep transfer learning approach for fault diagnosis based on an innovative gating mechanism | IEEE Trans. Ind. Informat. | 2022 |
| An imbalance modified convolutional neural network with incremental learning for chemical fault diagnosis | IEEE Trans. Ind. Informat. | 2022 |
| Bearing fault diagnosis using incremental learning and a deep multi-scale feature fusion network | IEEE Trans. Ind. Informat. | 2023 |
| A deep learning-based incremental fault diagnosis framework for chemical processes | Chemom. Intell. Lab. Syst. | 2023 |
| Fault diagnosis for power converters based on deep learning with incremental ability | IEEE Trans. Instrum. Meas. | 2023 |
| A new feature boosting based continual learning method for bearing fault diagnosis with incremental fault types | Adv. Eng. Inform. | 2024 |
| Cable fault diagnosis with generalization capability using incremental learning | Electr. Power Syst. Res. | 2025 |

---

## Contributing / 贡献指南

PRs are welcome.

### Add a new paper / 添加论文
1. Put the paper into the correct category:
   - **Incremental Online Learning / Incremental Offline Learning**
   - **Fault Distribution Drifts / Novel Fault Modes**
2. Add one row to the corresponding table in `README.md` with **only**:
   - `Paper | Venue | Year`
3. Keep the venue naming consistent (prefer IEEE-style abbreviations or the official venue name).


## Citation / 引用

If you find the taxonomy useful, please cite the survey that provides the classification and Table II paper pool:

```bibtex
@article{liu2025ilfd,
  title={Incremental Learning-Enabled Fault Diagnosis of Dynamic Systems: A Comprehensive Review},
  author={Liu, Zeyi and He, Xiao and Huang, Biao and Zhou, Donghua},
  journal={IEEE Transactions on Cybernetics},
  year={2025},
  doi={10.1109/TCYB.2025.3586643}
}

