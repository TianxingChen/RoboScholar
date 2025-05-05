<h1 align="center">
	Embodied AI Paper List @ <a href="https://lumina-embodied.ai/">Lumina EAI Community</a>
</h1>

**此仓库正在维修**

> Embodied AI（具身智能）入门的路径以及高质量信息的总结, 期望是按照路线走完后, 新手可以快速建立关于这个领域的认知, 希望能帮助到各位入门具身智能的朋友, 欢迎点Star、分享与提PR🌟~<br>【 <a href="https://github.com/tianxingchen/Embodied-AI-Guide">Embodied-AI-Guide</a>, Latest Update: May. 1, 2025 】<img alt="GitHub repo stars" src="https://img.shields.io/github/stars/TianxingChen/Embodied-AI-Guide"> ![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FTianxingChen%2FEmbodied-AI-Guide&label=Daily%20Visitors&labelColor=%232ccce4&countColor=%23d9e3f0)


> Embodied-AI-Guide项目很快将会以网页版wiki的形式上传到Lumina具身智能社区网站，敬请期待。如果你对合作构建Lumina具身社区感兴趣（目前更倾向于机构、社区间合作），欢迎邮件联系<a href="mailto:lumina.embodiedai@gmail.com">lumina.embodiedai@gmail.com</a>或联创微信<code>TianxingChen_2002</code>（请备注机构+姓名与来意）

**扫描右下图进入`Embodied-AI-Guide@Lumina社区`交流群**:

<table>
  <tr>
    <td>
      <img src="https://github.com/TianxingChen/Embodied-AI-Guide/blob/main/files/images/logo.png" alt="Task Descriptions">
    </td>
    <td>
      <img src="https://github.com/TianxingChen/Embodied-AI-Guide/blob/main/files/QR-Code.jpg" alt="Task Descriptions">
    </td>
  </tr>
</table>

## 0. Table of contents

1. Manipulation
   - Imitation Learning
      - Diffusion Policy & Diffuser
      - 
   - Humanoid
   - Dexterous Manipulation
2. LLM for Embodied AI
   - LLM Agent
3. Foundation Models for Embodied AI
   - Affordance
   - Correspondence
   - Tracking & Estimation
   - Generative Models
4. Reinforcement Learning
5. Motion Generation
6. Robot Hardware
7. Dataset & Benchmark



1. Diffusion Model for Planning, Policy, and RL
2. 3D-based Manipulation
3. 2D-based Manipulation
4. LLM for robotics
5. LLM Agent (Planning)
6. Generative Model for Embodied
7. Visual Feature: Correspondence, Affordance
8. Detection & Segmentation
9. Pose Estimation and Tracking
10. Humanoid
11. Dataset & Benchmark
12. Hardware
13. 2D to 3D Generation
14. Gaussion Splatting
15. Robotics for Medical
16. Companies

# Recent Random Papers
* **[RSS 25]** Unified Video Action Model, [webpage](https://unified-video-action-model.github.io/)
* **[arXiv 25]** Taccel: Scaling Up Vision-based Tactile Robotics via High-performance GPU Simulation, [arXiv](https://arxiv.org/pdf/2504.12908)
* **[RSS 25]** Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation, [arXiv](https://reactive-diffusion-policy.github.io/)
* **[arXiv 24]** GRAPE: Generalizing Robot Policy via Preference Alignment, [arXiv](https://arxiv.org/abs/2411.19309)
* **[arXiv 25]** GROVE: A Generalized Reward for Learning Open-Vocabulary Physical Skill, [arXiv](https://arxiv.org/abs/2504.04191)
* **[arXiv 24]** Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers, [arXiv](https://arxiv.org/abs/2409.20537)
* **[arXiv 24]** CogACT: A Foundational Vision-Language-Action Model for Synergizing Cognition and Action in Robotic Manipulation, [arXiv](https://arxiv.org/abs/2411.19650)
* **[arXiv 25]** Gripper Keypose and Object Pointflow as Interfaces for Bimanual Robotic Manipulation, [arXiv](https://arxiv.org/abs/2504.17784)
* **[arXiv 25]** Taccel: Scaling Up Vision-based Tactile Robotics via High-performance GPU Simulation, [arXiv](https://arxiv.org/abs/2504.12908)
* **[arXiv 24]** HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation, [website](https://humanoid-bench.github.io/)

## 1. Diffusion Model for Planning, Policy, and RL
* **[arXiv]** Diffusion Models for Reinforcement Learning: A Survey, [arXiv](https://arxiv.org/abs/2311.01223)

* **[ICLR 23 (Top 5% Notable)]** Is Conditional Generative Modeling all you need for Decision-Making?, [website](https://anuragajay.github.io/decision-diffuser/)

* **[RSS 23]** Diffusion Policy: Visuomotor Policy Learning via Action Diffusion, [website](https://diffusion-policy.cs.columbia.edu/)

* **[ICML 22 (Long Talk)]** Planning with Diffusion for Flexible Behavior Synthesis, [website](https://diffusion-planning.github.io/mobile.html)

* **[ICML 23 Oral]** Adaptdiffuser: Diffusion models as adaptive self-evolving planners, [website](https://adaptdiffuser.github.io/)

* **[CVPR 24]** SkillDiffuser: Interpretable Hierarchical Planning via Skill Abstractions in Diffusion-Based Task Execution, [website](https://skilldiffuser.github.io/)

* **[arXiv]** Learning a Diffusion Model Policy From Reward via Q-Score Matching, [arXiv](https://arxiv.org/abs/2312.11752)

* **[CoRL 23]** ChainedDiffuser: Unifying Trajectory Diffusion and Keypose Prediction for Robotic Manipulation, [website](https://chained-diffuser.github.io/)

* **[CVPR 23]** Affordance Diffusion: Synthesizing Hand-Object Interactions, [website](https://judyye.github.io/affordiffusion-www/)

* **[arXiv]** DiffuserLite: Towards Real-time Diffusion Planning, [arXiv](https://arxiv.org/abs/2401.15443)

* **[arXiv]** 3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations, [website](https://3d-diffusion-policy.github.io/)

* **[arXiv]** 3D Diffuser Actor: Policy Diffusion with 3D Scene Representations, [website](https://3d-diffuser-actor.github.io/)

* **[arXiv]** SafeDiffuser: Safe Planning with Diffusion Probabilistic Models, [arXiv](https://safediffuser.github.io/safediffuser/)

* **[CVPR 24]** Hierarchical Diffusion Policy for Kinematics-Aware Multi-Task Robotic Manipulation, [arXiv](https://yusufma03.github.io/projects/hdp/)
  
* **[arXiv 24]** Render and Diffuse: Aligning Image and Action Spaces for Diffusion-based Behaviour Cloning, [arXiv](https://arxiv.org/abs/2405.18196)

* **[arXiv 24]** Surgical Robot Transformer: Imitation Learning for Surgical Tasks, [website](https://surgical-robot-transformer.github.io/)

* **[CoRL 24]** GenDP: 3D Semantic Fields for Category-Level Generalizable Diffusion Policy, [website](https://gendp-anon.github.io/)

## 2. 3D-based Manipulation

* **[RSS 24]** RVT-2: Learning Precise Manipulation from Few Examples [website](https://robotic-view-transformer-2.github.io/)

* **[arXiv 23]** D<sup>3</sup> Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation, [website](https://robopil.github.io/d3fields/)

* **[arXiv 24]** UniDoorManip: Learning Universal Door Manipulation Policy Over Large-scale and Diverse Door Manipulation Environments, [website](https://arxiv.org/pdf/2403.02604)

* **[CoRL 23 (Oral)]** GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields, [website](https://yanjieze.com/GNFactor/)

* **[ECCV 24]** ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation, [website](https://guanxinglu.github.io/ManiGaussian/)

* **[IROS 24]** RISE: 3D Perception Makes Real-World Robot Imitation Simple and Effective, [website](https://rise-policy.github.io/)

### Grasping
* GraspNet [website](https://graspnet.net/)：
  * **[TRO 23]** AnyGrasp: Robust and Efficient Grasp Perception in Spatial and Temporal Domains, [arXiv](https://arxiv.org/abs/2212.08333)
* **[arXiv 24]** ThinkGrasp: A Vision-Language System for Strategic Part Grasping in Clutter, [website](https://h-freax.github.io/thinkgrasp_page/)
* **[arXiv 24]** GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping, [website](https://mrsecant.github.io/GaussianGrasper/)

### Articulated Object
* **[CVPR 22 Oral]** Ditto: Building Digital Twins of Articulated Objects from Interaction, [website](https://ut-austin-rpl.github.io/Ditto/)
* **[ICRA 24]** RGBManip: Monocular Image-based Robotic Manipulation through Active Object Pose Estimation, [website](https://rgbmanip.github.io/)

## 3. 2D-based Manipulation
* **[NIPS 23]** MoVie: Visual Model-Based Policy Adaptation for View Generalization, [website](https://yangsizhe.github.io/MoVie/)

## 4. LLM for robotics (LLM Agent)
* **[arXiv 24]** OK-Robot: What Really Matters in Integrating Open-Knowledge Models for Robotics, [website](https://ok-robot.github.io)

* **[CoRL 23]** VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models, [website](https://voxposer.github.io)

* **[arXiv 23]** ChatGPT for Robotics: Design Principles and Model Abilities, [arXiv](https://arxiv.org/abs/2306.17582)

* **[arXiv 24]** Language-Guided Object-Centric Diffusion Policy for Collision-Aware Robotic Manipulation, [arXiv](https://arxiv.org/pdf/2407.00451)

* **[PMLR 23]** RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control, [website](https://robotics-transformer2.github.io/)

## 5. LLM Agnet (planning)
* **[NIPS 23]** Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning, [website](https://guansuns.github.io/pages/llm-dm/)

## 6. Generative Model for Embodied
* **[arXiv 24]** Generative Image as Action Models, [website](https://genima-robot.github.io/)

* **[arXiv 24]** Genie: Generative Interactive Environments, [website](https://sites.google.com/view/genie-24/home)

## 7. Visual Feature
### 7.1 Correspondence
* **[arXiv 23]** D<sup>3</sup> Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation, [website](https://robopil.github.io/d3fields/)

* **[CoRL 20]** Transporter Networks: Rearranging the Visual World for Robotic Manipulation, [website](https://transporternets.github.io)

* **[ICLR 24]** SparseDFF: Sparse-View Feature Distillation for One-Shot Dexterous Manipulation, [website](https://arxiv.org/abs/2310.16838)

* **[ICRA 24]** UniGarmentManip: A Unified Framework for Category-Level Garment Manipulation via Dense Visual Correspondence, [website](https://warshallrho.github.io/unigarmentmanip/)

* **[CoRL 2018]** Dense Object Nets: Learning Dense Visual Object Descriptors By and For Robotic Manipulation, [PDF](https://arxiv.org/pdf/1806.08756)

* **[arXiv 24]** Theia: Distilling Diverse Vision Foundation Models for Robot Learning, [website](https://theia.theaiinstitute.com/), [Github repo](https://github.com/bdaiinstitute/theia)

### 7.2 Affordance

* **[CoRL 22]** Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation, [website](https://peract.github.io/)

* **[arXiv 24]** Robo-ABC: Affordance Generalization Beyond Categories via Semantic Correspondence for Robot Manipulation, [arXiv](https://arxiv.org/abs/2401.07487)

* **[arXiv 24]** PreAfford: Universal Affordance-Based Pre-Grasping for Diverse Objects and Environments, [arXiv](https://air-discover.github.io/PreAfford/)

* **[ICLR 22]** VAT-Mart: Learning Visual Action Trajectory Proposals for Manipulating 3D ARTiculated Objects, [website](https://hyperplane-lab.github.io/vat-mart/)

* **[ICLR 23]** DualAfford: Learning Collaborative Visual Affordance for Dual-gripper Object Manipulation, [arXiv](https://arxiv.org/abs/2207.01971)

* **[CVPR 22]** Joint Hand Motion and Interaction Hotspots Prediction from Egocentric Videos, [website](https://stevenlsw.github.io/hoi-forecast/)

* **[ICCV 23]** AffordPose: A Large-scale Dataset of Hand-Object Interactions with Affordance-driven Hand Pose, [website](https://affordpose.github.io/)

## 8. Detection & Segmentation

* **[ECCV 24]** Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection, [Github repo](https://github.com/IDEA-Research/GroundingDINO?tab=readme-ov-file)

* **[arXiv 24]** Grounded SAM: Marrying Grounding DINO with Segment Anything & Stable Diffusion & Recognize Anything - Automatically Detect, Segment and Generate Anything, [Github repo](https://github.com/IDEA-Research/Grounded-Segment-Anything)

* **[ICCV 23]** DEVA: Tracking Anything with Decoupled Video Segmentation, [website](https://hkchengrex.com/Tracking-Anything-with-DEVA/)

* **[ECCV 22]** Mem: Long-Term Video Object Segmentation with an Atkinson-Shiffrin Memory Model, [website](hkchengrex.com/XMem/)

* **[ICCV 23]** VLPart: Going Denser with Open-Vocabulary Part Segmentation, [website](https://github.com/facebookresearch/VLPart)

* LangSAM [Github repo](https://github.com/luca-medeiros/lang-segment-anything), combining Grounding DINO and SAM
 

## 9. Pose Estimation and Tracking
* **[CVPR 24 (Highlight)]** FoundationPose: Unified 6D Pose Estimation and Tracking of Novel Objects, [website](https://nvlabs.github.io/FoundationPose/)

* **[CVPR 23 (Highlight)]** GAPartNet: Cross-Category Domain-Generalizable Object Perception and Manipulation via Generalizable and Actionable Parts, [website](https://pku-epic.github.io/GAPartNet/)

* **[arXiv 23]** GAMMA: Generalizable Articulation Modeling and Manipulation for Articulated Objects, [website](https://sites.google.com/view/gamma-articulation)

* **[arXiv 24]** ManiPose: A Comprehensive Benchmark for Pose-aware Object Manipulation in Robotics, [website](https://sites.google.com/view/manipose)

* **[ICCV 23]** AffordPose: A Large-scale Dataset of Hand-Object Interactions with Affordance-driven Hand Pose, [website](https://affordpose.github.io/)

* **[CVPR 23]** BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects, [website](https://bundlesdf.github.io/)

* **[arXiv 24]** WiLoR: End-to-end 3D hand localization and reconstruction in-the-wild, [website](https://rolpotamias.github.io/WiLoR/)

## 10. Humanoid
* **[arXiv 24]** HumanPlus: Humanoid Shadowing and Imitation from Humans, [website](https://humanoid-ai.github.io/)


## 11. Dataset & Benchmark
* **[arXiv 24]** Empowering Embodied Manipulation: A Bimanual-Mobile Robot Manipulation Dataset for Household Tasks, [website](https://embodiedrobot.github.io/), [zhihu](https://zhuanlan.zhihu.com/p/688624666?utm_medium=social&utm_psn=1756405102318243840&utm_source=wechat_sessiong)
* **[arXiv 24]** GRUtopia: Dream General Robots in a City at Scale, [Github Repo](https://github.com/OpenRobotLab/GRUtopia)
* **[ICLR 24]** AgentBoard: An Analytical Evaluation Board of Multi-Turn LLM Agents, [website](https://hkust-nlp.github.io/agentboard/)
* **[arXiv 24]** RoboCAS: A Benchmark for Robotic Manipulation in Complex Object Arrangement Scenarios, [Github repo](https://github.com/notFoundThisPerson/RoboCAS-v0)
* **[arXiv 24]** BiGym: A Demo-Driven Mobile Bi-Manual Manipulation Benchmark, [website](https://chernyadev.github.io/bigym/)
* **[arXiv 24]** Evaluating Real-World Robot Manipulation Policies in Simulation, [website](https://simpler-env.github.io/)
* **[arXiv 23]** Objaverse-XL: A Universe of 10M+ 3D Objects, [website](https://objaverse.allenai.org/)

## 12. Hardware
* **[arXiv 24]** DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation, [website](https://dex-cap.github.io/)

## 13. 2D to 3D Generation

* **[arXiv 24]** Unique3D: High-Quality and Efficient 3D Mesh Generation from a Single Image, [website](https://wukailu.github.io/Unique3D/)

## 14. Gaussian Splatting

* **[SIGGRAPH 24]** 2DGS: 2D Gaussian Splatting for Geometrically Accurate Radiance Fields, [website](https://surfsplatting.github.io/)

## 15. Robotics for Medical
* **[arXiv 24]** Surgical Robot Transformer: Imitation Learning for Surgical Tasks, [website](https://surgical-robot-transformer.github.io/)

## TO READ

* Where2Act: From Pixels to Actions for Articulated 3D Objects

* PreAfford: Universal Affordance-Based Pre-Grasping for Diverse Objects and Environments

* Decision Transformer: Reinforcement Learning via Sequence Modeling

* Toward General-Purpose Robots via Foundation Models: A Survey and Meta-Analysis

* AO-Grasp: Articulated Object Grasp Generation

* Human-to-Robot Imitation in the Wild

* RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots

* SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation https://sam-embodied.github.io/, ICML24

* https://progprompt.github.io/

* PerAct, Act3D

* https://groups.csail.mit.edu/vision/datasets/ADE20K/

* Probing the 3D Awareness of Visual Foundation Model: https://arxiv.org/pdf/2404.08636

* ManipVQA: Injecting Robotic Affordance and Physically Grounded Information into Multi-Modal Large Language Models

* CLIP: Zero-shot Jack of All Trades, [website](https://blog.kzakka.com/posts/clip/), [CLIP GradCAM CLIP_GradCAM_Visualization](https://colab.research.google.com/github/kevinzakka/clip_playground/blob/main/CLIP_GradCAM_Visualization.ipynb)

* Articulated Object Manipulation with Coarse-to-fine Affordance for Mitigating the Effect of Point Cloud Noise: https://arxiv.org/pdf/2402.18699

* 3D-VLA: A 3D Vision-Language-Action Generative World Model
* PDDLGym: Gym Environments from PDDL Problems: https://arxiv.org/abs/2002.06432
* https://github.com/zjunlp/LLMAgentPapers?tab=readme-ov-file
* https://github.com/zjunlp/Prompt4ReasoningPapers
* TravelPlanner: A Benchmark for Real-World Planning with Language Agents
* VisionLLM: https://arxiv.org/abs/2305.11175
* Ferret: Refer and Ground Anything Anywhere at Any Granularity: https://github.com/apple/ml-ferret
* LangSplat
* Embodied AI with Two Arms: Zero-shot Learning, Safety and Modularity
* SparseDFF
* ManiPose: A Comprehensive Benchmark for Pose-aware Object Manipulation in Robotics

1. **Stabilizing Transformers for Reinforcement Learning**
   - **Summary**: 本文提出了Gated Transformer-XL (GTrXL)，一种改进的Transformer架构，用于解决标准Transformer在强化学习中的优化难题。通过引入层归一化和门控机制，GTrXL在部分可观察性环境中取得了优于LSTM的性能。
   - [链接](https://arxiv.org/abs/1910.06764)

2. **CoBERL: Contrastive BERT for Reinforcement Learning**
   - **Summary**: 文章介绍了CoBERL，它结合了对比损失和Transformer架构，通过双向掩码预测和对比学习方法提高强化学习中的数据效率和性能。
   - [链接](https://arxiv.org/abs/2107.05431)

3. **Adaptive Transformers in RL**
   - **Summary**: 该研究探索了在强化学习中使用具有自适应注意力跨度的Transformer模型，发现这种方法能够提高模型在需要长期依赖的环境中的性能。
   - [链接](https://arxiv.org/abs/2004.03761)

4. **Efficient Transformers in Reinforcement Learning using Actor-Learner Distillation**
   - **Summary**: 本文提出了Actor-Learner Distillation (ALD)方法，通过从大型学习者模型向小型执行者模型进行知识蒸馏，以提高Transformer在强化学习中的样本效率。
   - [链接](https://arxiv.org/abs/2104.01655)

5. **Deep Transformer Q-Networks for Partially Observable Reinforcement Learning**
   - **Summary**: 介绍了Deep Transformer Q-Networks (DTQN)，这是一种新型的强化学习架构，使用Transformer的自注意力机制来处理部分可观察性任务，并在多个挑战性环境中展示了有效性。
   - [链接](https://arxiv.org/abs/2206.01078)

6. **CtrlFormer: Learning Transferable State Representation for Visual Control via Transformer**
   - **Summary**: CtrlFormer是一种新型的Transformer架构，专注于通过学习可迁移的状态表示来提高视觉控制任务的样本效率，特别强调了在跨任务迁移学习方面的优势。
   - [链接](https://arxiv.org/abs/2206.08883)
  
Sapiens: Foundation for Human Vision Models: https://about.meta.com/realitylabs/codecavatars/sapiens
General Flow as Foundation Affordance for Scalable Robot Learning https://general-flow.github.io/
