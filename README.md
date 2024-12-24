<p align="center">
  <h1 align="center">A Collection of Video Generation Studies</h1>

This GitHub repository summarizes papers and resources related to the video generation task. 

If you have any suggestions about this repository, please feel free to [start a new issue](https://github.com/AlonzoLeeeooo/awesome-video-generation/issues/new) or [pull requests](https://github.com/AlonzoLeeeooo/awesome-video-generation/pulls).

Recent news of this GitHub repo are listed as follows.

🔥 [Nov. 19th] We have released our latest paper titled ["StableV2V: Stablizing Shape Consistency in Video-to-Video Editing"](https://arxiv.org/abs/2411.11045), with the correponding [code](https://github.com/AlonzoLeeeooo/StableV2V), [model weights](https://huggingface.co/AlonzoLeeeooo/StableV2V), and [a testing benchmark `DAVIS-Edit`](https://huggingface.co/datasets/AlonzoLeeeooo/DAVIS-Edit) open-sourced. Feel free to check them out from the links!
<details> <summary> Click to see more information. </summary>

- [Jun. 17th] All **NeurIPS 2023** papers and references are updated.
- [Apr. 26th] Update a new direction: [Personalized Video Generation](#personalized-video-generation).
- [Mar. 28th] The official **AAAI 2024** paper list are released! Official version of PDFs and BibTeX references are updated accordingly.
</details>

<!-- omit in toc -->
# <span id="contents">Contents</span>
- [To-Do Lists](#to-do-lists)
- [Products](#products)
- [Papers](#papers)
  - [Survey Papers](#survey-papers)
  - [Text-to-Video Generation](#text-to-video-generation)
    - [Year 2024](#text-year-2024)
    - [Year 2023](#text-year-2023)
    - [Year 2022](#text-year-2022)
    - [Year 2021](#text-year-2021)
  - [Image-to-Video Generation](#image-to-video-generation)
    - [Year 2024](#image-year-2024)
    - [Year 2023](#image-year-2023)
    - [Year 2022](#image-year-2022)
  - [Personalized Video Generation](#personalized-video-generation)
    - [Year 2024](#personalized-year-2024)
    - [Year 2023](#personalized-year-2023)
  - [Video Editing](#video-editing)
    - [Year 2023](#editing-year-2023)
  - [Audio-to-Video Generation](#audio-to-video-generation)
    - [Year 2024](#audio-year-2024)
    - [Year 2023](#audio-year-2023)
- [Datasets](#datasets)
- [Q&A](#qa)
- [References](#references)
- [Star History](#star-history)

<!-- omit in toc -->
# To-Do Lists
- Latest Papers
  - [ ] Update NeurIPS 2024 Papers
  - [x] Update ECCV 2024 Papers
  - [x] Update CVPR 2024 Papers
    - [x] Update PDFs and References of ⚠️ Papers
    - [ ] Update Published Versions of References
  - [x] Update AAAI 2024 Papers
    - [x] Update PDFs and References of ⚠️ Papers
    - [x] Update Published Versions of References
  - [x] Update ICLR 2024 Papers
  - [x] Update NeurIPS 2023 Papers
- Previously Published Papers
  - [x] Update Previous CVPR papers
  - [x] Update Previous ICCV papers
  - [x] Update Previous ECCV papers
  - [x] Update Previous NeurIPS papers
  - [x] Update Previous ICLR papers
  - [x] Update Previous AAAI papers
  - [x] Update Previous ACM MM papers
- Regular Maintenance of Preprint arXiv Papers and Missed Papers

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Products

|Name|Organization|Year|Research Paper|Website|Specialties|
|-|-|-|-|-|-|
|Sora|OpenAI|2024|[link](https://www.midjourney.com/home)|[link](https://openai.com/sora)|-|
|Lumiere|Google|2024|[link](https://arxiv.org/abs/2401.12945)|[link](https://lumiere-video.github.io/)|-|
|VideoPoet|Google|2023|-|[link](https://sites.research.google/videopoet/)|-|
|W.A.I.T|Google|2023|[link](https://arxiv.org/pdf/2312.06662.pdf)|[link](https://walt-video-diffusion.github.io/)|-|
|Gen-2|Runaway|2023|-|[link](https://research.runwayml.com/gen2)|-|
|Gen-1|Runaway|2023|-|[link](https://research.runwayml.com/gen1)|-|
|Animate Anyone|Alibaba|2023|[link](https://arxiv.org/pdf/2311.17117.pdf)|[link](https://humanaigc.github.io/animate-anyone/)|-|
|Outfit Anyone|Alibaba|2023|-|[link](https://outfitanyone.app/)|-|
|Stable Video|StabilityAI|2023|[link](https://arxiv.org/pdf/2311.15127.pdf)|[link](https://www.stablevideo.com/)|-|
|Pixeling|HiDream.ai|2023|-|[link](https://hidreamai.com/#/)|-|
|DomoAI|DomoAI|2023|-|[link](https://domoai.app/)|-|
|Emu|Meta|2023|[link](https://arxiv.org/abs/2311.10709)|[link](https://emu-video.metademolab.com/)|-|
|Genmo|Genmo|2023|-|[link](https://www.genmo.ai/)|-|
|NeverEnds|NeverEnds|2023|-|[link](https://neverends.life/)|-|
|Moonvalley|Moonvalley|2023|-|[link](https://moonvalley.ai/)|-|
|Morph Studio|Morph|2023|-|[link](https://www.morphstudio.com/)|-|
|Pika|Pika|2023|-|[link](https://pika.art/)|-|
|PixelDance|ByteDance|2023|[link](https://arxiv.org/abs/2311.10982)|[link](https://makepixelsdance.github.io/)|-|


[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Papers

<!-- omit in toc -->
## Survey Papers
- <span id="survey-year-2023">**Year 2024**</span>
- **arXiv**
  - Video Diffusion Models: A Survey [[Paper]](https://arxiv.org/pdf/2405.03150.pdf)
- <span id="survey-year-2023">**Year 2023**</span>
- **arXiv**
  - A Survey on Video Diffusion Models [[Paper]](https://arxiv.org/pdf/2310.10647.pdf)

<!-- omit in toc -->
## Text-to-Video Generation
- <span id="text-year-2024">**Year 2024**</span>
  - **CVPR**
    - ***Vlogger:*** Make Your Dream A Vlog [[Paper]](https://arxiv.org/pdf/2401.09414.pdf) [[Code]](https://github.com/Vchitect/Vlogger)
    - ***Make Pixels Dance:*** High-Dynamic Video Generation [[Paper]](https://arxiv.org/pdf/2311.10982.pdf) [[Project]](https://makepixelsdance.github.io/) [[Demo]](https://makepixelsdance.github.io/demo.html)
    - ***VGen:*** Hierarchical Spatio-temporal Decoupling for Text-to-Video Generation [[Paper]](https://arxiv.org/pdf/2312.04483) [[Code]](https://github.com/ali-vilab/VGen) [[Project]](https://higen-t2v.github.io/)
    - ***GenTron:*** Delving Deep into Diffusion Transformers for Image and Video Generation [[Paper]](https://arxiv.org/pdf/2312.04557) [[Project]](https://www.shoufachen.com/gentron_website/)
    - ***SimDA:*** Simple Diffusion Adapter for Efficient Video Generation [[Paper]](https://arxiv.org/pdf/2308.09710.pdf) [[Code]](https://github.com/ChenHsing/SimDA) [[Project]](https://chenhsing.github.io/SimDA/)
    - ***MicroCinema:*** A Divide-and-Conquer Approach for Text-to-Video Generation [[Paper]](https://arxiv.org/pdf/2311.18829) [[Project]](https://wangyanhui666.github.io/MicroCinema.github.io/) [[Video]](https://youtube.com/shorts/H7O-Ku_lqPA)
    - ***Generative Rendering:*** Controllable 4D-Guided Video Generation with 2D Diffusion Models [[Paper]](https://arxiv.org/pdf/2312.01409) [[Project]](https://primecai.github.io/generative_rendering/)
    - ***PEEKABOO:*** Interactive Video Generation via Masked-Diffusion [[Paper]](https://arxiv.org/pdf/2312.07509) [[Code]](https://github.com/microsoft/Peekaboo) [[Project]](https://jinga-lala.github.io/projects/Peekaboo/) [[Demo]](https://huggingface.co/spaces/anshuln/peekaboo-demo)
    - ***EvalCrafter:*** Benchmarking and Evaluating Large Video Generation Models [[Paper]](https://arxiv.org/pdf/2310.11440) [[Code]](https://github.com/EvalCrafter/EvalCrafter) [[Project]](https://evalcrafter.github.io/)
    - A Recipe for Scaling up Text-to-Video Generation with Text-free Videos [[Paper]](https://arxiv.org/pdf/2312.15770) [[Code]](https://github.com/damo-vilab/i2vgen-xl) [[Project]](https://tf-t2v.github.io/)
    - ***BIVDiff:*** A Training-free Framework for General-Purpose Video Synthesis via Bridging Image and Video Diffusion Models [[Paper]](https://arxiv.org/pdf/2312.02813) [[Project]](https://bivdiff.github.io/)
    - ***Mind the Time:*** Scaled Spatiotemporal Transformers for Text-to-Video Synthesis [[Paper]](https://arxiv.org/pdf/2402.14797) [[Project]](https://snap-research.github.io/snapvideo/video_ldm.html)
    - ***Animate Anyone:*** Consistent and Controllable Image-to-video Synthesis for Character Animation [[Paper]](https://arxiv.org/pdf/2311.17117.pdf) [[Code]](https://github.com/HumanAIGC/AnimateAnyone) [[Project]](https://humanaigc.github.io/animate-anyone/)
    - ***MotionDirector:*** Motion Customization of Text-to-Video Diffusion Models [[Paper]](https://arxiv.org/pdf/2310.08465) [[Code]](https://github.com/showlab/MotionDirector)
    - Hierarchical Patch-wise Diffusion Models for High-Resolution Video Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Skorokhodov_Hierarchical_Patch_Diffusion_Models_for_High-Resolution_Video_Generation_CVPR_2024_paper.pdf) [[Project]](https://snap-research.github.io/hpdm/)
    - ***DiffPerformer:*** Iterative Learning of Consistent Latent Guidance for Diffusion-based Human Video Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_DiffPerformer_Iterative_Learning_of_Consistent_Latent_Guidance_for_Diffusion-based_Human_CVPR_2024_paper.pdf) [[Code]](https://github.com/aipixel/)
    - Grid Diffusion Models for Text-to-Video Generation [[Paper]](https://arxiv.org/pdf/2404.00234.pdf) [[Code]](https://github.com/taegyeong-lee/Grid-Diffusion-Models-for-Text-to-Video-Generation) [[Video]](https://taegyeong-lee.github.io/text2video)
  - **ECCV**
    - ***Emu Video:*** Factorizing Text-to-Video Generation by Explicit Image Conditioning [[Paper]](https://arxiv.org/pdf/2311.10709.pdf) [[Project]](https://ai.meta.com/blog/emu-text-to-video-generation-image-editing-research/)
    - ***W.A.L.T.:*** Photorealistic Video Generation with Diffusion Models [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10270.pdf) [[Project]](https://walt-video-diffusion.github.io/)
    - ***MoVideo:*** Motion-Aware Video Generation with Diffusion Models [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06030.pdf)
    - ***DrivingDiffusion:*** Layout-Guided Multi-View Driving Scenarios Video Generation with Latent Diffusion Model [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10097.pdf) [[Code]](https://github.com/shalfun/DrivingDiffusion) [[Project]](https://drivingdiffusion.github.io/)
    - ***MagDiff:*** Multi-Alignment Diffusion for High-Fidelity Video Generation and Editing [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02738.pdf)
    - ***HARIVO:*** Harnessing Text-to-Image Models for Video Generation [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06938.pdf) [[Project]](https://kwonminki.github.io/HARIVO/)
    - ***MEVG:*** Multi-event Video Generation with Text-to-Video Models [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06012.pdf) [[Project]](https://kuai-lab.github.io/eccv2024mevg/)
    - ***DeCo:*** Decoupled Human-Centered Diffusion Video Editing with Motion Consistency [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06071.pdf)
    - SAVE: Protagonist Diversification with Structure Agnostic Video Editing
  - **ICLR**
    - ***VDT:*** General-purpose Video Diffusion Transformers via Mask Modeling [[Paper]](https://arxiv.org/pdf/2305.13311.pdf) [[Code]](https://github.com/RERV/VDT) [[Project]](https://vdt-2023.github.io/)
    - ***VersVideo:*** Leveraging Enhanced Temporal Diffusion Models for Versatile Video Generation [[Paper]](https://openreview.net/pdf?id=K9sVJ17zvB)
  - **AAAI**
    - ***Follow Your Pose:*** Pose-Guided Text-to-Video Generation using Pose-Free Videos [[Paper]](https://arxiv.org/pdf/2304.01186) [[Code]](https://github.com/mayuelala/FollowYourPose) [[Project]](https://follow-your-pose.github.io/)
    - ***E2HQV:*** High-Quality Video Generation from Event Camera via Theory-Inspired Model-Aided Deep Learning [[Paper]](https://arxiv.org/pdf/2401.08117)
    - ***ConditionVideo:*** Training-Free Condition-Guided Text-to-Video Generation [[Paper]](https://arxiv.org/pdf/2310.07697) [[Code]](https://github.com/pengbo807/ConditionVideo) [[Project]](https://pengbo807.github.io/conditionvideo-website/)
    - ***F3-Pruning:*** A Training-Free and Generalized Pruning Strategy towards Faster and Finer Text to-Video Synthesis [[Paper]](https://arxiv.org/pdf/2312.03459)
  - **arXiv**  
    - ***Lumiere:*** A Space-Time Diffusion Model for Video Generation [[Paper]](https://arxiv.org/pdf/2401.12945.pdf) [[Project]](https://lumiere-video.github.io/)
    - ***Boximator:*** Generating Rich and Controllable Motions for Video Synthesis [[Paper]](https://arxiv.org/pdf/2402.01566.pdf) [[Project]](https://boximator.github.io/) [[Video]](https://www.youtube.com/watch?v=reto_TYsYyQ)
    - World Model on Million-Length Video And Language With RingAttention [[Paper]](https://arxiv.org/abs/2402.08268) [[Code]](https://github.com/LargeWorldModel/LWM) [[Project]](https://largeworldmodel.github.io/)
    - ***Direct-a-Video:*** Customized Video Generation with User-Directed Camera Movement and Object Motion [[Paper]](https://arxiv.org/pdf/2402.03162.pdf) [[Project]](https://direct-a-video.github.io/)
    - ***WorldDreamer:*** Towards General World Models for Video Generation via Predicting Masked Tokens [[Paper]](https://arxiv.org/pdf/2401.09985) [[Code]](https://github.com/JeffWang987/WorldDreamer) [[Project]](https://world-dreamer.github.io/)
    - ***MagicVideo-V2:*** Multi-Stage High-Aesthetic Video Generation [[Paper]](https://arxiv.org/pdf/2401.04468.pdf) [[Project]](https://magicvideov2.github.io/)
    - ***Latte:*** Latent Diffusion Transformer for Video Generation [[Paper]](https://arxiv.org/pdf/2401.03048) [[Code]](https://github.com/Vchitect/Latte) [[Project]](https://maxin-cn.github.io/latte_project)
    - ***Mora:*** Enabling Generalist Video Generation via A Multi-Agent Framework [[Paper]](https://arxiv.org/pdf/2403.13248) [[Code]](https://github.com/lichao-sun/Mora)
    - ***StreamingT2V:*** Consistent, Dynamic, and Extendable Long Video Generation from Text [[Paper]](https://arxiv.org/pdf/2403.14773) [[Code]](https://github.com/Picsart-AI-Research/StreamingT2V) [[Project]](https://streamingt2v.github.io/) [[Video]](https://twitter.com/i/status/1770909673463390414)
    - ***VIDiff:*** Translating Videos via Multi-Modal Instructions with Diffusion Models [[Paper]](https://arxiv.org/pdf/2311.18837)
    - ***StoryDiffusion:*** Consistent Self-Attention for Long-Range Image and Video Generation [[Paper]](https://arxiv.org/pdf/2405.01434) [[Code]](https://github.com/HVision-NKU/StoryDiffusion) [[Project]](https://storydiffusion.github.io/) [[Demo]](https://huggingface.co/spaces/YupengZhou/StoryDiffusion)
    - ***Ctrl-Adapter:*** An Efficient and Versatile Framework for Adapting Diverse Controls to Any Diffusion Model [[Paper]](https://arxiv.org/pdf/2404.09967) [[Code]](https://github.com/HL-hanlin/Ctrl-Adapter) [[Project]](https://ctrl-adapter.github.io/)
    - ***ControlNeXt:*** Powerful and Efficient Control for Image and Video Generation [[Paper]](https://arxiv.org/pdf/2408.06070) [[Code]](https://github.com/dvlab-research/ControlNeXt) [[Project]](https://pbihao.github.io/projects/controlnext/index.html)
    - ***FancyVideo:*** Towards Dynamic and Consistent Video Generation via Cross-frame Textual Guidance [[Paper]](https://arxiv.org/pdf/2408.08189v1) [[Project]](https://fancyvideo.github.io/)
    - ***Factorized-Dreamer:*** Training A High-Quality Video Generator with Limited and Low-Quality Data [[Paper]](https://arxiv.org/pdf/2408.10119v1) [[Code]](https://github.com/yangxy/Factorized-Dreamer/)
    - Fine-gained Zero-shot Video Sampling [[Paper]](https://arxiv.org/pdf/2407.21475) [[Project]](https://densechen.github.io/zss/)
    - Training-free Long Video Generation with Chain of Diffusion Model Experts [[Paper]](https://www.arxiv.org/pdf/2408.13423)
    - ***ReconX:*** Reconstruct Any Scene from Sparse Views with Video Diffusion Model [[Paper]](https://arxiv.org/pdf/2408.16767) [[Code]](https://github.com/liuff19/ReconX) [[Project]](https://liuff19.github.io/ReconX/) [[Video]](https://www.youtube.com/watch?v=UuL2nP5rJcI)
    - ConFiner: Training-free Long Video Generation with Chain of Diffusion Model Experts [[Paper]](https://arxiv.org/pdf/2408.13423) [[Code]](https://github.com/Confiner2025/Confiner2025)
    - ***3DTrajMaster:*** Mastering 3D Trajectory for Multi-Entity Motion in Video Generation [[Paper]](https://arxiv.org/pdf/2412.07759) [[Code]](https://github.com/KwaiVGI/3DTrajMaster) [[Project]](https://fuxiao0719.github.io/projects/3dtrajmaster/)
  - **Others**
    - ***Sora:*** Video Generation Models as World Simulators [[Paper]](https://openai.com/research/video-generation-models-as-world-simulators)
- <span id="text-year-2023">**Year 2023**</span>
  - **CVPR**
    - ***Align your Latents:*** High-resolution Video Synthesis with Latent Diffusion Models [[Paper]](https://arxiv.org/pdf/2304.08818.pdf) [[Project]](https://research.nvidia.com/labs/toronto-ai/VideoLDM/) [[Reproduced code]](https://github.com/srpkdyy/VideoLDM)
    - ***Text2Video-Zero:*** Text-to-image Diffusion Models are Zero-shot Video Generators [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Khachatryan_Text2Video-Zero_Text-to-Image_Diffusion_Models_are_Zero-Shot_Video_Generators_ICCV_2023_paper.pdf) [[Code]](https://github.com/Picsart-AI-Research/Text2Video-Zero) [[Demo]](https://huggingface.co/spaces/PAIR/Text2Video-Zero) [[Project]](https://text2video-zero.github.io/) 
    - Video Probabilistic Diffusion Models in Projected Latent Space [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yu_Video_Probabilistic_Diffusion_Models_in_Projected_Latent_Space_CVPR_2023_paper.pdf) [[Code]](https://github.com/sihyun-yu/PVDM)
  - **ICCV**
    - Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ge_Preserve_Your_Own_Correlation_A_Noise_Prior_for_Video_Diffusion_ICCV_2023_paper.pdf) [[Project]](https://research.nvidia.com/labs/dir/pyoco/)
    - ***Gen-1:*** Structure and Content-guided Video Synthesis with Diffusion Models [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Esser_Structure_and_Content-Guided_Video_Synthesis_with_Diffusion_Models_ICCV_2023_paper.pdf) [[Project]](https://research.runwayml.com/gen1)
  - **NeurIPS**
    - Video Diffusion Models [[Paper]](https://arxiv.org/pdf/2204.03458.pdf) [[Project]](https://video-diffusion.github.io/)
    - Learning Universal Policies via Text-Guided Video Generation [[Paper]](https://papers.nips.cc/paper_files/paper/2023/file/1d5b9233ad716a43be5c0d3023cb82d0-Paper-Conference.pdf) [[Project]](https://universal-policy.github.io/unipi/) [[Code]](https://github.com/flow-diffusion/AVDC)
    - ***VideoComposer:*** Compositional Video Synthesis with Motion Controllability [[Paper]](https://arxiv.org/pdf/2306.02018.pdf) [[Code]](https://github.com/ali-vilab/videocomposer) [[Project]](https://videocomposer.github.io/)
  - **ICLR**
    - ***CogVideo:*** Large-scale Pretraining for Text-to-video Generation via Transformers [[Paper]](https://openreview.net/pdf?id=rB6TpjAuSRy) [[Code]](https://github.com/THUDM/CogVideo) [[Demo]](https://models.aminer.cn/cogvideo/)
    - ***Make-A-Video:*** Text-to-video Generation without Text-video Data [[Paper]](https://arxiv.org/pdf/2209.14792.pdf) [[Project]](https://makeavideo.studio/) [[Reproduced code]](https://github.com/lucidrains/make-a-video-pytorch)
    - ***Phenaki:*** Variable Length Video Generation From Open Domain Textual Description [[Paper]](https://openreview.net/pdf/fe8e106a2746992c9c2e658bdc8cb9c89cc5a39a.pdf) [[Reproduced Code]](https://github.com/lucidrains/phenaki-pytorch)
  - **arXiv**
    - ***Control-A-Video:*** Controllable Text-to-video Generation with Diffusion Models [[Paper]](https://arxiv.org/pdf/2305.13840.pdf) [[Code]](https://github.com/Weifeng-Chen/control-a-video) [[Demo]](https://huggingface.co/spaces/wf-genius/Control-A-Video) [[Project]](https://arxiv.org/pdf/2305.13840.pdf)
    - ***ControlVideo:*** Training-free Controllable Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2305.13077.pdf) [[Code]](https://github.com/YBYBZhang/ControlVideo)
    - ***Imagen Video:*** High Definition Video Generation with Diffusion Models [[Paper]](https://arxiv.org/pdf/2210.02303.pdf) 
    - ***Latent-Shift:*** Latent Diffusion with Temporal Shift for Efficient Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2304.08477.pdf) [[Project]](https://latent-shift.github.io/)
    - ***LAVIE:*** High-quality Video Generation with Cascaded Latent Diffusion Models [[Paper]](https://arxiv.org/pdf/2309.15103.pdf) [[Code]](https://github.com/Vchitect/LaVie) [[Project]](https://vchitect.github.io/LaVie-project/)
    - ***Show-1:*** Marrying Pixel and Latent Diffusion Models for Text-to-video Generation [[Paper]](https://showlab.github.io/Show-1/assets/Show-1.pdf) [[Code]](https://github.com/showlab/Show-1) [[Project]](https://showlab.github.io/Show-1/)
    - ***Stable Video Diffusion:*** Scaling Latent Video Diffusion Models to Large Datasets [[Paper]](https://arxiv.org/pdf/2311.15127.pdf) [[Code]](https://github.com/Stability-AI/generative-models) [[Project]](https://stability.ai/news/stable-video-diffusion-open-ai-video-model)
    - ***VideoFactory:*** Swap Attention in Spatiotemporal Diffusions for Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2305.10874.pdf) [[Dataset]](https://github.com/daooshee/HD-VG-130M)
    - ***VideoGen:*** A Reference-guided Latent Diffusion Approach for High Definition Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2309.00398.pdf) [[Code]](https://videogen.github.io/VideoGen/)
    - ***InstructVideo:*** Instructing Video Diffusion Models with Human Feedback [[Paper]](https://arxiv.org/pdf/2312.12490.pdf) [[Code]](https://github.com/ali-vilab/i2vgen-xl/blob/main/doc/InstructVideo.md) [[Project]](https://arxiv.org/pdf/2312.12490.pdf)
    - ***SEINE:*** Short-to-Long Video Diffusion Model for Generative Transition and Prediction [[Paper]](https://arxiv.org/pdf/2310.20700.pdf) [[Code]](https://github.com/Vchitect/SEINE) [[Project]](https://vchitect.github.io/SEINE-project/)
    - ***VideoLCM:*** Video Latent Consistency Model [[Paper]](https://arxiv.org/pdf/2312.09109.pdf)
    - ModelScope Text-to-Video Technical Report [[Paper]](https://arxiv.org/pdf/2308.06571.pdf) [[Code]](https://github.com/ExponentialML/Text-To-Video-Finetuning)
    - ***LAMP:*** Learn A Motion Pattern for Few-Shot-Based Video Generation [[Paper]](https://arxiv.org/pdf/2310.10769) [[Code]](https://rq-wu.github.io/projects/LAMP) [[Project]](https://rq-wu.github.io/projects/LAMP)
    - ***STG:*** Spatiotemporal Skip Guidance for Enhanced Video Diffusion Sampling [[Paper]](https://arxiv.org/pdf/2411.18664) [[Code]](https://github.com/junhahyung/STGuidance) [[Project]](https://junhahyung.github.io/STGuidance/)
    - ***Motion-Zero:*** Zero-Shot Moving Object Control Framework for Diffusion-Based Video Generation [[Paper]](https://arxiv.org/pdf/2401.10150) [[Project]](https://litaoguo.github.io/MotionZero.github.io/)
- <span id="text-year-2022">**Year 2022**</span>
  - **CVPR**    
    - ***Show Me What and Tell Me How:*** Video Synthesis via Multimodal Conditioning [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Han_Show_Me_What_and_Tell_Me_How_Video_Synthesis_via_CVPR_2022_paper.pdf) [[Code]](https://github.com/snap-research/MMVID) [[Dataset]](https://github.com/snap-research/MMVID/blob/main/mm_vox_celeb/README.md)
- <span id="text-year-2021">**Year 2021**</span>
  - **arXiv**
      -  ***VideoGPT:*** Video Generation using VQ-VAE and Transformers [[Paper]](https://arxiv.org/pdf/2104.10157.pdf) [[Code]](https://github.com/wilson1yan/VideoGPT) [[Project]](https://wilson1yan.github.io/videogpt/index.html)
      -  ***MagicVideo:*** Efficient Video Generation With Latent Diffusion Models [[Paper]](https://arxiv.org/pdf/2211.11018)
      -  ***EasyAnimate:*** A High-Performance Long Video Generation Method based on Transformer Architecture [[Paper]](https://arxiv.org/pdf/2405.18991) [[Code]](https://arxiv.org/pdf/2405.18991)
[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Image-to-Video Generation
- <span id="image-year-2024">**Year 2024**</span>
  - **CVPR**
    - ***VideoBooth:*** Diffusion-based Video Generation with Image Prompts [[Paper]](https://arxiv.org/pdf/2312.00777) [[Code]](https://github.com/Vchitect/VideoBooth) [[Project]](https://vchitect.github.io/VideoBooth-project/) [[Video]](https://www.youtube.com/watch?v=10DxH1JETzI)
  - **ECCV**
    - Rethinking Image-to-Video Adaptation: An Object-centric Perspective [[Paper]](http://arxiv.org/pdf/2407.06871v1)
    - ***PhysGen:*** Rigid-Body Physics-Grounded Image-to-Video Generation [[Paper]](https://arxiv.org/pdf/2409.18964) [[Code]](https://github.com/stevenlsw/physgen) [[Project]](https://stevenlsw.github.io/physgen/)
    - ***MOFA-Video:*** Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model [[Paper]](https://arxiv.org/pdf/2405.20222) [[Code]](https://github.com/MyNiuuu/MOFA-Video) [[Project]](https://myniuuu.github.io/MOFA_Video/)
  - **AAAI**
    - Decouple Content and Motion for Conditional Image-to-Video Generation [[Paper]](https://arxiv.org/pdf/2311.14294)
  - **arXiv**
    -  ***ConsistI2V:*** Enhancing Visual Consistency for Image-to-Video Generation [[Paper]](https://arxiv.org/pdf/2402.04324.pdf) [[Code]](https://github.com/TIGER-AI-Lab/ConsistI2V) [[Project]](https://tiger-ai-lab.github.io/ConsistI2V/)
    - ***I2V-Adapter:*** A General Image-to-Video Adapter for Diffusion Models [[Paper]](https://arxiv.org/pdf/2312.16693.pdf) [[Code]](https://github.com/I2V-Adapter/I2V-Adapter-repo)
    - ***Follow-Your-Click:*** Open-domain Regional Image Animation via Short Prompts [[Paper]](https://arxiv.org/pdf/2403.08268) [[Code]](https://github.com/mayuelala/FollowYourClick) [[Project]](https://follow-your-click.github.io/)
    - ***AtomoVideo:*** High Fidelity Image-to-Video Generation [[Paper]](https://arxiv.org/pdf/2403.01800.pdf) [[Project]](https://atomo-video.github.io/) [[Video]](https://www.youtube.com/embed/36JIlk-U-vQ)
    - ***Pix2Gif:*** Motion-Guided Diffusion for GIF Generation [[Paper]](https://arxiv.org/pdf/2403.04634) [[Code]](https://hiteshk03.github.io/Pix2Gif/) [[Project]](https://hiteshk03.github.io/Pix2Gif/)
    - ***ID-Animator:*** Zero-Shot Identity-Preserving Human Video Generation [[Paper]](https://arxiv.org/pdf/2404.15275.pdf) [[Code]](https://id-animator.github.io/) [[Project]](https://id-animator.github.io/)
    - Tuning-Free Noise Rectification for High Fidelity Image-to-Video Generation [[Paper]](https://arxiv.org/pdf/2403.02827) [[Project]](https://noise-rectification.github.io/)
    - ***MegActor-Σ:*** Unlocking Flexible Mixed-Modal Control in Portrait Animation with Diffusion Transformer [[Paper]](https://arxiv.org/abs/2408.14975) [[Code]](https://github.com/megvii-research/megactor)
    - ***LeviTor:*** 3D Trajectory Oriented Image-to-Video Synthesis [[Paper]](https://arxiv.org/pdf/2412.15214) [[Code]](https://github.com/qiuyu96/LeviTor) [[Project]](https://ppetrichor.github.io/levitor.github.io/) [[Demo]](https://huggingface.co/hlwang06/LeviTor/tree/main)

- <span id="image-year-2023">**Year 2023**</span>
  - **CVPR**
    - Conditional Image-to-Video Generation with Latent Flow Diffusion Models [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Ni_Conditional_Image-to-Video_Generation_With_Latent_Flow_Diffusion_Models_CVPR_2023_paper.pdf) [[Code]](https://github.com/nihaomiao/CVPR23_LFDM)
  - **arXiv**
    - ***I2VGen-XL:*** High-quality Image-to-video Synthesis via Cascaded Diffusion Models [[Paper]](https://arxiv.org/pdf/2311.04145.pdf) [[Code]](https://github.com/ali-vilab/i2vgen-xl) [[Project]](https://i2vgen-xl.github.io/)
    - ***DreamVideo:*** High-Fidelity Image-to-Video Generation with Image Retention and Text Guidance [[Paper]](https://arxiv.org/pdf/2312.03018) [[Code]](https://github.com/anonymous0769/DreamVideo) [[Project]](https://anonymous0769.github.io/DreamVideo/)
    - ***DynamiCrafter:*** Animating Open-domain Images with Video Diffusion Priors [[Paper]](https://arxiv.org/pdf/2310.12190) [[Project]](https://doubiiu.github.io/projects/DynamiCrafter/) [[Code]](https://github.com/Doubiiu/DynamiCrafter) [[Video]](https://www.youtube.com/watch?v=0NfmIsNAg-g) [[Demo]](https://huggingface.co/spaces/Doubiiu/DynamiCrafter)
    - ***AnimateDiff:*** Animate Your Personalized Text-to-image Diffusion Models without Specific Tuning [[Paper]](https://openreview.net/pdf?id=Fx2SbBgcte) [[Project]](https://animatediff.github.io/)
- <span id="image-year-2022">**Year 2022**</span>
  - **CVPR**    
    - ***Make It Move:*** Controllable Image-to-Video Generation with Text Descriptions [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_Make_It_Move_Controllable_Image-to-Video_Generation_With_Text_Descriptions_CVPR_2022_paper.pdf) [[Code]](https://github.com/Youncy-Hu/MAGE)
- <span id="image-year-2021">**Year 2021**</span>
  - **ICCV**
    - ***Click to Move:*** Controlling Video Generation with Sparse Motion [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ardino_Click_To_Move_Controlling_Video_Generation_With_Sparse_Motion_ICCV_2021_paper.pdf) [[Code]](https://github.com/PierfrancescoArdino/C2M)


[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Audio-to-Video Generation
- <span id="audio-year-2024">**Year 2024**</span>  
  - **AAAI**
    - Diverse and Aligned Audio-to-Video Generation 
  via Text-to-Video Model Adaptation [[Paper]](https://arxiv.org/pdf/2309.16429) [[Code]](https://github.com/guyyariv/TempoTokens)
- <span id="audio-year-2023">**Year 2023**</span>
  - **CVPR**
    - ***MM-Diffusion:*** Learning Multi-Modal Diffusion Models for Joint Audio and Video Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Ruan_MM-Diffusion_Learning_Multi-Modal_Diffusion_Models_for_Joint_Audio_and_Video_CVPR_2023_paper.pdf) [[Code]](https://github.com/researchmm/MM-Diffusion)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Personalized Video Generation
- <span id="personalized-year-2024">**Year 2024**</span>
  - **CVPR**
    - High-fidelity Person-centric Subject-to-Image Synthesis [[Paper]](https://arxiv.org/pdf/2311.10329) [[Code]](https://github.com/CodeGoat24/Face-diffuser)
  - **ECCV**
    - ***PoseCrafter:*** One-Shot Personalized Video Synthesis Following Flexible Pose Control [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06050.pdf) [[Project]](https://ml-gsai.github.io/PoseCrafter-demo/)
  - **arXiv**
    - ***Magic-Me:*** Identity-Specific Video Customized Diffusion [[Paper]](https://arxiv.org/pdf/2402.09368) [[Code]](https://github.com/Zhen-Dong/Magic-Me) [[Project]](https://magic-me-webpage.github.io/) [[Demo]](https://huggingface.co/spaces/visionMaze/Magic-Me)
    - ***ReVideo:*** Remake a Video with Motion and Content Control [[Paper]](https://arxiv.org/pdf/2405.13865) [[Code]](https://github.com/MC-E/ReVideo) [[Project]](https://mc-e.github.io/project/ReVideo/)
- <span id="personalized-year-2023">**Year 2023**</span>
  - **arXiv**
    - ***FastComposer:*** Tuning-Free Multi-Subject Image Generation with Localized Attention [[Paper]](https://arxiv.org/pdf/2305.10431) [[Code]](https://github.com/mit-han-lab/fastcomposer?tab=readme-ov-file) [[Demo]](https://fastcomposer.hanlab.ai/)
    - ***Make-Your-Video:*** Customized Video Generation Using Textual and Structural Guidance [[Paper]](https://arxiv.org/pdf/2306.00943) [[Project]](https://doubiiu.github.io/projects/Make-Your-Video/)
    - ***DreamVideo-2:*** Zero-Shot Subject-Driven Video Customization with Precise Motion Control [[Paper]](https://arxiv.org/pdf/2410.13830) [[Project]](https://dreamvideo2.github.io/)

[<u><small><🎯Back to Top></small></u>](#contents)


<!-- omit in toc -->
## Video Editing
- <span id="editing-year-2024">**Year 2024**</span>
  - **CVPR**
    - ***VMC:*** Video Motion Customization using Temporal Attention Adaption for Text-to-Video Diffusion Models [[Paper]](https://arxiv.org/pdf/2312.00845) [[Code]](https://github.com/HyeonHo99/Video-Motion-Customization) [[Project]](https://video-motion-customization.github.io/)
    - ***Fairy:*** Fast Parallellized Instruction-Guided Video-to-Video Synthesis [[Paper]](https://arxiv.org/pdf/2312.13834) [[Project]](https://fairy-video2video.github.io/)
    - ***CCEdit:*** Creative and Controllable Video Editing via Diffusion Models [[Paper]](https://arxiv.org/pdf/2309.16496) [[Code]](https://github.com/RuoyuFeng/CCEdit) [[Project]](https://ruoyufeng.github.io/CCEdit.github.io/) [[Video]](https://www.youtube.com/watch?v=UQw4jq-igN4)
    - ***DynVideo-E:*** Harnessing Dynamic NeRF for Large-Scale Motion- and View-Change Human-Centric Video Editing [[Paper]](https://arxiv.org/pdf/2310.10624) [[Project]](https://showlab.github.io/DynVideo-E/) [[Video]](https://www.youtube.com/watch?v=xiRH4Q6B3Yk)
    - ***Video-P2P:*** Video Editing with Cross-attention Control [[Paper]](https://arxiv.org/pdf/2303.04761) [[Code]](https://github.com/dvlab-research/Video-P2P) [[Project]](https://video-p2p.github.io/)
    - A Video is Worth 256 Bases: Spatial-Temporal Expectation-Maximization Inversion for Zero-Shot Video Editing [[Paper]](https://arxiv.org/pdf/2312.05856) [[Code]](https://github.com/STEM-Inv/stem-inv) [[Project]](https://stem-inv.github.io/page/)
    - ***MaskINT:*** Video Editing via Interpolative Non-autoregressive Masked Transformers [[Paper]](https://arxiv.org/pdf/2312.12468) [[Code]](https://maskint.github.io/) [[Project]](https://maskint.github.io/)
    - ***VidToMe:*** Video Token Merging for Zero-Shot Video Editing [[Paper]](https://arxiv.org/pdf/2312.10656) [[Code]](https://github.com/lixirui142/VidToMe) [[Project]](https://vidtome-diffusion.github.io/) [[Video]](https://youtu.be/cZPtwcRepNY)
    - Towards Language-Driven Video Inpainting via Multimodal Large Language Models [[Paper]](https://arxiv.org/pdf/2401.10226.pdf) [[Code]](https://github.com/jianzongwu/Language-Driven-Video-Inpainting) [[Project]](https://jianzongwu.github.io/projects/rovi/) [[Dataset]](https://huggingface.co/datasets/jianzongwu/rovi)
    - ***AVID:*** Any-Length Video Inpainting with Diffusion Model [[Paper]](https://arxiv.org/pdf/2312.03816.pdf) [[Code]](https://zhang-zx.github.io/AVID/) [[Project]](https://zhang-zx.github.io/AVID/)
    - ***CAMEL:*** CAusal Motion Enhancement tailored for Lifting Text-driven Video Editing [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_CAMEL_CAusal_Motion_Enhancement_Tailored_for_Lifting_Text-driven_Video_Editing_CVPR_2024_paper.pdf) [[Code]](https://github.com/zhangguiwei610/CAMEL)
    - Space-Time Diffusion Features for Zero-Shot Text-Driven Motion Transfer [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Yatim_Space-Time_Diffusion_Features_for_Zero-Shot_Text-Driven_Motion_Transfer_CVPR_2024_paper.pdf) [[Code]](https://github.com/diffusion-motion-transfer/diffusion-motion-transfer) [[Project]](https://diffusion-motion-transfer.github.io/)
    - ***FRESCO:*** Spatial-Temporal Correspondence for Zero-Shot Video Translation [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_FRESCO_Spatial-Temporal_Correspondence_for_Zero-Shot_Video_Translation_CVPR_2024_paper.pdf) [[Code]](https://github.com/williamyang1991/FRESCO) [[Project]](https://www.mmlab-ntu.com/project/fresco/)
    - ***MotionEditor:*** Editing Video Motion via Content-Aware Diffusion [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Tu_MotionEditor_Editing_Video_Motion_via_Content-Aware_Diffusion_CVPR_2024_paper.pdf) [[Code]](https://github.com/Francis-Rings/MotionEditor) [[Project]](https://francis-rings.github.io/MotionEditor/)
  - **ECCV**
    - ***DragVideo:*** Interactive Drag-style Video Editing [[Paper]](https://arxiv.org/pdf/2312.02216)
    - Video Editing via Factorized Diffusion Distillation [[Paper]](https://arxiv.org/pdf/2403.09334)
    - ***OCD:*** Object-Centric Diffusion for Efficient Video Editing [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07396.pdf) [[Project]](https://qualcomm-ai-research.github.io/object-centric-diffusion/)
    - ***DreamMotion:*** Space-Time Self-Similarity Score Distillation for Zero-Shot Video Editing [[Paper]](https://arxiv.org/pdf/2403.12002) [[Project]](https://hyeonho99.github.io/dreammotion/)
    - ***WAVE:*** Warping DDIM Inversion Features for Zero-shot Text-to-Video Editing [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09682.pdf) [[Project]](https://ree1s.github.io/wave/)
    - ***Videoshop:*** Localized Semantic Video Editing with Noise-Extrapolated Diffusion Inversion [[Paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01890.pdf) [[Code]](https://github.com/sfanxiang/videoshop) [[Project]](https://videoshop-editing.github.io/)
  - **ICLR**
    - ***Ground-A-Video:*** Zero-shot Grounded Video Editing using Text-to-image Diffusion Models [[Paper]](https://arxiv.org/pdf/2310.01107) [[Code]](https://github.com/Ground-A-Video/Ground-A-Video) [[Project]](https://ground-a-video.github.io/)
    - ***TokenFlow:*** Consistent Diffusion Features for Consistent Video Editing [[Paper]](https://arxiv.org/pdf/2307.10373) [[Code]](https://github.com/omerbt/TokenFlow) [[Project]](https://diffusion-tokenflow.github.io/)
    - Consistent Video-to-Video Transfer Using Synthetic Dataset [[Paper]](https://openreview.net/pdf?id=IoKRezZMxF) [[Code]](https://github.com/amazon-science/instruct-video-to-video/tree/main)
    - ***FLATTEN:*** Optical FLow-guided ATTENtion for Consistent Text-to-Video Editing [[Paper]](https://openreview.net/pdf?id=JgqftqZQZ7) [[Code]](https://github.com/yrcong/flatten) [[Project]](https://flatten-video-editing.github.io/)
  - **SIGGRAPH**
    - ***MotionCtrl:*** A Unified and Flexible Motion Controller for Video Generation [[Paper]](https://arxiv.org/pdf/2312.03641.pdf) [[Code]](https://github.com/TencentARC/MotionCtrl) [[Project]](https://wzhouxiff.github.io/projects/MotionCtrl/) [[Demo]](https://huggingface.co/spaces/TencentARC/MotionCtrl)
  - **arXiv**
    - Spectral Motion Alignment for Video Motion Transfer using Diffusion Models [[Paper]](https://arxiv.org/abs/2403.15249) [[Code]](https://github.com/geonyeong-park/Spectral-Motion-Alignment) [[Project]](https://geonyeong-park.github.io/spectral-motion-alignment/)
    - ***UniEdit:*** A Unified Tuning-Free Framework for Video Motion and Appearance Editing [[Paper]](https://arxiv.org/pdf/2402.13185) [[Code]](https://github.com/JianhongBai/UniEdit) [[Project]](https://jianhongbai.github.io/UniEdit/)
    - ***DragAnything:*** Motion Control for Anything using Entity Representation [[Paper]](https://arxiv.org/pdf/2403.07420.pdf) [[Code]](https://github.com/showlab/DragAnything) [[Project]](https://weijiawu.github.io/draganything_page/)
    - ***AnyV2V:*** A Plug-and-Play Framework for Any Video-to-Video Editing Tasks [[Paper]](https://arxiv.org/pdf/2403.14468) [[Code]](https://github.com/TIGER-AI-Lab/AnyV2V) [[Project]](https://tiger-ai-lab.github.io/AnyV2V/)
    - ***CoCoCo:*** Improving Text-Guided Video Inpainting for Better Consistency, Controllability and Compatibility [[Paper]](https://arxiv.org/pdf/2403.12035) [[Code]](https://github.com/zibojia/COCOCO) [[Project]](https://cococozibojia.github.io/)
    - ***VASE:*** Object-Centric Appearance and Shape Manipulation of Real Videos [[Paper]](https://arxiv.org/pdf/2401.02473)
    - ***StableV2V:*** Stablizing Shape Consistency in Video-to-Video Editing [[Paper]](https://arxiv.org/pdf/2411.11045) [[Code]](https://github.com/AlonzoLeeeooo/StableV2V) [[Project]](https://alonzoleeeooo.github.io/StableV2V) [[Dataset]](https://huggingface.co/datasets/AlonzoLeeeooo/DAVIS-Edit)
    - Motion Inversion for Video Customization [[Paper]](https://arxiv.org/pdf/2403.20193) [[Code]](https://github.com/EnVision-Research/MotionInversion) [[Demo]](https://huggingface.co/spaces/ziyangmai/MotionInversion)
- <span id="editing-year-2023">**Year 2023**</span>
  - **CVPR**
    - Shape-aware Text-driven Layered Video Editing [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750705.pdf) [[Code]](https://github.com/text-video-edit/shape-aware-text-driven-layered-video-editing-release) [[Project]](https://text-video-edit.github.io/)
  - **ICCV**
    - ***Pix2Video:*** Video Editing using Image Diffusion [[Paper]](https://arxiv.org/pdf/2303.12688) [[Code]](https://github.com/duyguceylan/pix2video)
    - ***Tune-A-Video:*** One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Tune-A-Video_One-Shot_Tuning_of_Image_Diffusion_Models_for_Text-to-Video_Generation_ICCV_2023_paper.pdf) [[Code]](https://github.com/showlab/Tune-A-Video) [[Project]](https://tuneavideo.github.io/)
  - **NeurIPS**
    - Towards Consistent Video Editing with Text-to-Image Diffusion Models [[Paper]](https://openreview.net/pdf?id=RNVwm4BzXO)
  - **SIGGRAPH**
    - ***Rerender A Video:*** Zero-Shot Text-Guided Video-to-Video Translation [[Paper]](https://arxiv.org/pdf/2306.07954) [[Code]](https://github.com/williamyang1991/Rerender_A_Video) [[Project]](https://www.mmlab-ntu.com/project/rerender/)
  - **arXiv**
    - ***Style-A-Video:*** Agile Diffusion for Arbitrary Text-based Video Style Transfer [[Paper]](https://arxiv.org/pdf/2305.05464.pdf)
    - ***SAVE:*** Spectral-Shift-Aware Adaptation of Image Diffusion Models for Text-guided Video Editing [[Paper]](https://arxiv.org/pdf/2305.18670) [[Code]](https://github.com/nazmul-karim170/SAVE-Text2Video-Diffusion) [[Project]](https://save-textguidedvideoediting.github.io/)
- <span id="editing-year-2022">**Year 2022**</span>
  - **ECCV**
    - ***Text2LIVE:*** Text-Driven Layered Image and Video Editing [[Paper]](https://arxiv.org/pdf/2204.02491) [[Code]](https://github.com/omerbt/Text2LIVE) [[Project]](https://text2live.github.io/)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Datasets
- [arXiv 2012] ***UCF101:*** A Dataset of 101 Human Actions Classes From Videos in The Wild [[Paper]](https://arxiv.org/pdf/1212.0402.pdf) [[Dataset]](https://www.crcv.ucf.edu/data/UCF101.php)
- [arXiv 2017] ***DAVIS:*** The 2017 DAVIS Challenge on Video Object Segmentation [[Paper]](https://arxiv.org/pdf/1704.00675.pdf) [[Dataset]](https://davischallenge.org/)
- [ICCV 2019] ***FaceForensics++:*** Learning to Detect Manipulated Facial Images [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Rossler_FaceForensics_Learning_to_Detect_Manipulated_Facial_Images_ICCV_2019_paper.pdf) [[Code]](https://github.com/ondyari/FaceForensics)
- [NeurIPS 2019] ***TaiChi-HD:*** First Order Motion Model for Image Animation [[Paper]](https://papers.nips.cc/paper_files/paper/2019/file/31c0b36aef265d9221af80872ceb62f9-Paper.pdf) [[Dataset]](https://github.com/AliaksandrSiarohin/first-order-model)
- [ECCV 2020] ***SkyTimeLapse:*** DTVNet: Dynamic Time-lapse Video
Generation via Single Still Image [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500290.pdf) [[Code]](https://github.com/zhangzjn/DTVNet?tab=readme-ov-file)
- [ICCV 2021] ***WebVid-10M:*** Frozen in Time: ️A Joint Video and Image Encoder for End to End Retrieval [[Paper]](https://arxiv.org/pdf/2104.00650.pdf) [[Dataset]](https://maxbain.com/webvid-dataset/) [[Code]](https://github.com/m-bain/webvid) [[Project]](https://www.robots.ox.ac.uk/~vgg/research/frozen-in-time/)
- [ICCV 2021] ***WebVid-10M:*** Frozen in Time: A Joint Video and Image Encoder for End-to-End Retrieval [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Bain_Frozen_in_Time_A_Joint_Video_and_Image_Encoder_for_ICCV_2021_paper.pdf) [[Dataset]](https://github.com/m-bain/webvid) [[Project]](https://www.robots.ox.ac.uk/~vgg/research/frozen-in-time/)
- [ECCV 2022] ***ROS:*** Learning to Drive by Watching YouTube Videos: Action-Conditioned Contrastive Policy Pretraining [[Paper]](https://arxiv.org/pdf/2204.02393.pdf) [[Code]](https://github.com/metadriverse/ACO) [[Dataset]](https://mycuhk-my.sharepoint.com/personal/1155165194_link_cuhk_edu_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F1155165194%5Flink%5Fcuhk%5Fedu%5Fhk%2FDocuments%2Fytb%5Fdriving%5Fvideos&ga=1)
- [arXiv 2023] ***HD-VG-130M:*** VideoFactory: Swap Attention in Spatiotemporal Diffusions for Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2305.10874.pdf) [[Dataset]](https://github.com/daooshee/HD-VG-130M)
- [NeurIPS 2023] ***FETV:*** A Benchmark for Fine-Grained Evaluation of Open-Domain Text-to-Video Generation [[Paper]](https://papers.nips.cc/paper_files/paper/2023/file/c481049f7410f38e788f67c171c64ad5-Paper-Datasets_and_Benchmarks.pdf) [[Code]](https://github.com/llyx97/FETV)
- [ICLR 2024] ***InternVid:*** A Large-scale Video-Text Dataset for Multimodal Understanding and Generation [[Paper]](https://arxiv.org/pdf/2307.06942) [[Dataset]](https://github.com/OpenGVLab/InternVideo/tree/main/Data/InternVid)
- [CVPR 2024] ***Panda-70M:*** Captioning 70M Videos with Multiple Cross-Modality Teachers [[Paper]](https://arxiv.org/pdf/2402.19479.pdf) [[Dataset]](https://github.com/snap-research/Panda-70M) [[Project]](https://snap-research.github.io/Panda-70M)
- [arXiv 2024] ***VidProM:*** A Million-scale Real Prompt-Gallery Dataset for Text-to-Video Diffusion Models [[Paper]](https://arxiv.org/pdf/2403.06098.pdf) [[Dataset]](https://github.com/WangWenhao0716/VidProM)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Evaluation Metrics
- [CVPR 2024] **VBench:** Comprehensive Benchmark Suite for Video Generative Models [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Huang_VBench_Comprehensive_Benchmark_Suite_for_Video_Generative_Models_CVPR_2024_paper.pdf) [[Code]](https://github.com/Vchitect/VBench)
- [ICCV 2023] **DOVER:** Exploring Video Quality Assessment on User Generated Contents from Aesthetic and Technical Perspectives [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wu_Exploring_Video_Quality_Assessment_on_User_Generated_Contents_from_Aesthetic_ICCV_2023_paper.pdf) [[Code]](https://github.com/VQAssessment/DOVER)
- [ICLR 2019] ***FVD:*** A New Metric for Video Generation [[Paper]](https://openreview.net/pdf?id=rylgEULtdN) [[Code]](https://github.com/google-research/google-research/blob/master/frechet_video_distance/frechet_video_distance.py)

<!-- omit in toc -->
# Q&A
- **Q: The conference sequence of this paper list?**
  - This paper list is organized according to the following sequence:
    - CVPR
    - ICCV
    - ECCV
    - NeurIPS
    - ICLR
    - AAAI
    - ACM MM
    - SIGGRAPH
    - arXiv
    - Others
- **Q: What does `Others` refers to?**
  - Some of the following studies (e.g., `Sora`) does not publish their technical report on arXiv. Instead, they tend to write a blog in their official websites. The `Others` category refers to such kind of studies.

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# References

The `reference.bib` file summarizes bibtex references of up-to-date image inpainting papers, widely used datasets, and toolkits.
Based on the original references, I have made the following modifications to make their results look nice in the `LaTeX` manuscripts:
- Refereces are normally constructed in the form of `author-etal-year-nickname`. Particularly, references of datasets and toolkits are directly constructed as `nickname`, e.g., `imagenet`.
- In each reference, all names of conferences/journals are converted into abbreviations, e.g., `Computer Vision and Pattern Recognition -> CVPR`.
- The `url`, `doi`, `publisher`, `organization`, `editor`, `series` in all references are removed.
- The `pages` of all references are added if they are missing.
- All paper names are in title case. Besides, I have added an additional `{}` to make sure that the title case would also work well in some particular templates. 

If you have other demands of reference formats, you may refer to the original references of papers by searching their names in [DBLP](https://dblp.org/) or [Google Scholar](https://scholar.google.com/).

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Star History

<p align="center">
    <a href="https://api.star-history.com/svg?repos=AlonzoLeeeooo/awesome-video-generation&type=Date" target="_blank">
        <img width="500" src="https://api.star-history.com/svg?repos=AlonzoLeeeooo/awesome-video-generation&type=Date" alt="Star History Chart">
    </a>
<p>

[<u><small><🎯Back to Top></small></u>](#contents)
