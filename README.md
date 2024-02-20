<p align="center">
  <h1 align="center">A Collection of Video Generation Studies</h1>

This GitHub repository summarizes papers and resources related to the video generation task. 

If you have any suggestions about this repository, please feel free to [start a new issue](https://github.com/AlonzoLeeeooo/awesome-video-generation/issues/new) or [pull requests](https://github.com/AlonzoLeeeooo/awesome-video-generation/pulls).

<!-- omit in toc -->
# <span id="contents">Contents</span>
- [References](#references)
- [Products](#products)
  - [Year 2024](#product-year-2024)
  - [Year 2023](#product-year-2023)
- [Papers](#papers)
  - [Text-to-Video Generation](#text-to-video-generation)
    - [Year 2024](#text-year-2024)
    - [Year 2023](#text-year-2023)
    - [Year 2022](#text-year-2022)
  - [Image-to-Video Generation](#image-to-video-generation)
    - [Year 2024](#image-year-2024)
    - [Year 2023](#image-year-2023)
    - [Year 2022](#image-year-2022)
  - [Style Transfer](#style-transfer)
    - [Year 2023](#style-year-2023)
- [Datasets](#datasets)
- [To-Do Lists](#to-do-lists)


<!-- omit in toc -->
# References

The `reference.bib` file summarizes bibtex references of up-to-date image inpainting papers, widely used datasets, and toolkits.
Based on the original references, I have made the following modifications to make their results look nice in the `LaTeX` manuscripts:
- Refereces are normally constructed in the form of `author-etal-year-nickname`. Particularly, references of datasets and toolkits are directly constructed as `nickname`, e.g., `imagenet`.
- In each reference, all names of conferences/journals are converted into abbreviations, e.g., `{IEEE/CVF} Conference on Computer Vision and Pattern Recognition -> CVPR`.
- The `url`, `doi`, `publisher`, `organization`, `editor`, `series` in all references are removed.
- The `pages` of all references are added if they are missing.
- All paper names are in title case. Besides, I have added an additional `{}` to make sure that the title case would also work well in some particular templates. 

If you have other demands of reference formats, you may refer to the original references of papers by searching their names in [DBLP](https://dblp.org/) or [Google Scholar](https://scholar.google.com/).

[<u><small><🎯Back to Top></small></u>](#contents)


<!-- omit in toc -->
# Products
- <span id="product-year-2024">**Year 2024**</span>
  - Sora [Paper](https://openai.com/research/video-generation-models-as-world-simulators) [[Website]](https://openai.com/sora)
- <span id="product-year-2023">**Year 2023**</span>
  - Animate Anyone [[Paper]](https://arxiv.org/pdf/2311.17117.pdf) [[GitHub]](https://github.com/HumanAIGC/AnimateAnyone) [[Website]](https://humanaigc.github.io/animate-anyone/)
  - Emu [[Website]](https://emu-video.metademolab.com/)
  - Gen-2 [[Website]](https://research.runwayml.com/gen2)
  - Gen-1  [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Esser_Structure_and_Content-Guided_Video_Synthesis_with_Diffusion_Models_ICCV_2023_paper.pdf) [[Website]](https://research.runwayml.com/gen1)
  - Midjourney [[Website]](https://www.midjourney.com/)
  - Morph Studio [[Website]](https://www.morphstudio.com/)
  - Outfit Anyone [[Website]](https://humanaigc.github.io/outfit-anyone/)
  - Pika [[Website]](https://pika.art/login) 
  - PixelDance [[Website]](https://makepixelsdance.github.io/)
  - Stable Video Diffusion [[Paper]](https://arxiv.org/pdf/2311.15127.pdf) [[Website]](https://stability.ai/news/stable-video-diffusion-open-ai-video-model)
  - VideoPoet [[Website]](https://sites.research.google/videopoet/)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Papers

<!-- omit in toc -->
## Text-to-Video Generation
- <span id="text-year-2024">**Year 2024**</span>
  - **arXiv**  
    - ***Lumiere:*** A Space-Time Diffusion Model for Video Generation [[Paper]](https://arxiv.org/pdf/2401.12945.pdf) [[Project]](https://lumiere-video.github.io/)
    - ***Boximator:*** Generating Rich and Controllable Motions for Video Synthesis [[Paper]](https://arxiv.org/pdf/2402.01566.pdf) [[Project]](https://boximator.github.io/) [[Video]](https://www.youtube.com/watch?v=reto_TYsYyQ)
  - **Others**
    - ***Sora:*** Video Generation Models as World Simulators [[Paper]](https://openai.com/research/video-generation-models-as-world-simulators)
- <span id="text-year-2023">**Year 2023**</span>
  - **CVPR**
    - ***Align your Latents:*** High-resolution Video Synthesis with Latent Diffusion Models [[Paper]](https://arxiv.org/pdf/2304.08818.pdf) [[Project]](https://research.nvidia.com/labs/toronto-ai/VideoLDM/) [[Reproduced code]](https://github.com/srpkdyy/VideoLDM)
    - ***Text2Video-Zero:*** Text-to-image Diffusion Models are Zero-shot Video Generators [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Khachatryan_Text2Video-Zero_Text-to-Image_Diffusion_Models_are_Zero-Shot_Video_Generators_ICCV_2023_paper.pdf) [[Code]](https://github.com/Picsart-AI-Research/Text2Video-Zero) [[Demo]](https://huggingface.co/spaces/PAIR/Text2Video-Zero) [[Project]](https://text2video-zero.github.io/) 
    - Video Probabilistic Diffusion Models in Projected Latent Space [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yu_Video_Probabilistic_Diffusion_Models_in_Projected_Latent_Space_CVPR_2023_paper.pdf) [[Code]](https://github.com/sihyun-yu/PVDM)
  - **NeurIPS**
    - Video Diffusion Models [[Paper]](https://arxiv.org/pdf/2204.03458.pdf) [[Project]](https://video-diffusion.github.io/)
  - **ICCV**
    - Preserve Your Own Correlation: A Noise Prior for Video Diffusion Models [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ge_Preserve_Your_Own_Correlation_A_Noise_Prior_for_Video_Diffusion_ICCV_2023_paper.pdf) [[Project]](https://research.nvidia.com/labs/dir/pyoco/)
    - ***Gen-1:*** Structure and Content-guided Video Synthesis with Diffusion Models [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Esser_Structure_and_Content-Guided_Video_Synthesis_with_Diffusion_Models_ICCV_2023_paper.pdf) [[Project]](https://research.runwayml.com/gen1)
  - **ICLR**
    - ***CogVideo:*** Large-scale Pretraining for Text-to-video Generation via Transformers [[Paper]](https://openreview.net/pdf?id=rB6TpjAuSRy) [[Code]](https://github.com/THUDM/CogVideo) [[Demo]](https://models.aminer.cn/cogvideo/)
    - ***Make-A-Video:*** Text-to-video Generation without Text-video Data [[Paper]](https://arxiv.org/pdf/2209.14792.pdf) [[Project]](https://makeavideo.studio/) [[Reproduced code]](https://github.com/lucidrains/make-a-video-pytorch)
    - ***Phenaki:*** Variable Length Video Generation From Open Domain Textual Description [[Paper]](https://openreview.net/pdf/fe8e106a2746992c9c2e658bdc8cb9c89cc5a39a.pdf) [[Code]](https://github.com/lucidrains/phenaki-pytorch)
  - **arXiv**
    - ***Animate Anyone:*** Consistent and Controllable Image-to-video Synthesis for Character Animation [[Paper]](https://arxiv.org/pdf/2311.17117.pdf) [[Code]](https://github.com/HumanAIGC/AnimateAnyone) [[Project]](https://humanaigc.github.io/animate-anyone/)
    - ***AnimateDiff:*** Animate Your Personalized Text-to-image Diffusion Models without Specific Tuning [[Paper]](https://openreview.net/pdf?id=Fx2SbBgcte) [[Project]](https://animatediff.github.io/)
    - ***Control-A-Video:*** Controllable Text-to-video Generation with Diffusion Models [[Paper]](https://arxiv.org/pdf/2305.13840.pdf) [[Code]](https://github.com/Weifeng-Chen/control-a-video) [[Demo]](https://huggingface.co/spaces/wf-genius/Control-A-Video) [[Project]](https://arxiv.org/pdf/2305.13840.pdf)
    - ***ControlVideo:*** Training-free Controllable Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2305.13077.pdf) [[Code]](https://github.com/YBYBZhang/ControlVideo)
    - ***Imagen Video:*** High Definition Video Generation with Diffusion Models [[paper]](https://arxiv.org/pdf/2210.02303.pdf) 
    - ***Latent-Shift:*** Latent Diffusion with Temporal Shift for Efficient Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2304.08477.pdf) [[Project]](https://latent-shift.github.io/)
    - ***LAVIE:*** High-quality Video Generation with Cascaded Latent Diffusion Models [[Paper]](https://arxiv.org/pdf/2309.15103.pdf) [[code]](https://github.com/Vchitect/LaVie) [[Project]](https://vchitect.github.io/LaVie-project/)
    - ***Show-1:*** Marrying Pixel and Latent Diffusion Models for Text-to-video Generation [[Paper]](https://showlab.github.io/Show-1/assets/Show-1.pdf) [[Code]](https://github.com/showlab/Show-1) [[Project]](https://showlab.github.io/Show-1/)
    - ***SimDA:*** Simple Diffusion Adapter for Efficient Video Generation [[Paper]](https://arxiv.org/pdf/2308.09710.pdf) [[Code]](https://github.com/ChenHsing/SimDA) [[Project]](https://chenhsing.github.io/SimDA/)
    - ***Stable Video Diffusion:*** Scaling Latent Video Diffusion Models to Large Datasets [[Paper]](https://arxiv.org/pdf/2311.15127.pdf) [[Code]](https://github.com/Stability-AI/generative-models) [[Project]](https://stability.ai/news/stable-video-diffusion-open-ai-video-model)
    - ***VideoComposer:*** Compositional Video Synthesis with Motion Controllability [[Paper]](https://arxiv.org/pdf/2306.02018.pdf) [[Code]](https://github.com/ali-vilab/videocomposer) [[Project]](https://videocomposer.github.io/)
    - ***VideoFactory:*** Swap Attention in Spatiotemporal Diffusions for Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2305.10874.pdf)
    - ***VideoGen:*** A Reference-guided Latent Diffusion Approach for High Definition Text-to-video Generation [[Paper]](https://arxiv.org/pdf/2309.00398.pdf) [[Code]](https://videogen.github.io/VideoGen/)
    - ***InstructVideo:*** Instructing Video Diffusion Models with Human Feedback [[Paper]](https://arxiv.org/pdf/2312.12490.pdf) [[Code]](https://github.com/ali-vilab/i2vgen-xl/blob/main/doc/InstructVideo.md) [[Project]](https://arxiv.org/pdf/2312.12490.pdf)
- <span id="text-year-2022">**Year 2022**</span>
  - **CVPR**    
    - Show Me What and Tell Me How: Video Synthesis via Multimodal Conditioning [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Han_Show_Me_What_and_Tell_Me_How_Video_Synthesis_via_CVPR_2022_paper.pdf) [[Code]](https://github.com/snap-research/MMVID) [[Dataset]](https://github.com/snap-research/MMVID/blob/main/mm_vox_celeb/README.md)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Image-to-Video Generation
- <span id="image-year-2024">**Year 2024**</span>
  - **arXiv** 
    - ***I2V-Adapter:*** A General Image-to-Video Adapter for Diffusion Models [[Paper]](https://arxiv.org/pdf/2312.16693.pdf) [[Code]](https://github.com/I2V-Adapter/I2V-Adapter-repo)
- <span id="image-year-2023">**Year 2023**</span>
  - **CVPR**
    - Conditional Image-to-Video Generation with Latent Flow Diffusion Models [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Ni_Conditional_Image-to-Video_Generation_With_Latent_Flow_Diffusion_Models_CVPR_2023_paper.pdf) [[Code]](https://github.com/nihaomiao/CVPR23_LFDM)
  - **arXiv**
    - ***I2VGen-XL:*** High-quality Image-to-video Synthesis via Cascaded Diffusion Models [[Paper]](https://arxiv.org/pdf/2311.04145.pdf) [[Code]](https://github.com/ali-vilab/i2vgen-xl) [[Project]](https://i2vgen-xl.github.io/)
- <span id="image-year-2022">**Year 2022**</span>
  - **CVPR**    
    - ***Make It Move:*** Controllable Image-to-Video Generation with Text Descriptions [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_Make_It_Move_Controllable_Image-to-Video_Generation_With_Text_Descriptions_CVPR_2022_paper.pdf) [[Code]](https://github.com/Youncy-Hu/MAGE)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Audio-to-Video Generation
- <span id="audio-year-2023">**Year 2023**</span>
  - **CVPR**
    - ***MM-Diffusion:*** Learning Multi-Modal Diffusion Models for Joint Audio and Video Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Ruan_MM-Diffusion_Learning_Multi-Modal_Diffusion_Models_for_Joint_Audio_and_Video_CVPR_2023_paper.pdf) [[Code]](https://github.com/researchmm/MM-Diffusion)



[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
## Style Transfer
- <span id="style-year-2023">**Year 2023**</span>
  - **arXiv**
    - ***Style-A-Video:*** Agile Diffusion for Arbitrary Text-based Video Style Transfer [[Paper]](https://arxiv.org/pdf/2305.05464.pdf)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Datasets
- [ICCV 2021] ***WebVid-10M:*** Frozen in Time: ️A Joint Video and Image Encoder for End to End Retrieval [[Paper]](https://arxiv.org/pdf/2104.00650.pdf) [[Dataset]](https://maxbain.com/webvid-dataset/) [[GitHub]](https://github.com/m-bain/webvid) [[Project]](https://www.robots.ox.ac.uk/~vgg/research/frozen-in-time/)
- [ECCV 2022] **ROS:** Learning to Drive by Watching YouTube Videos: Action-Conditioned Contrastive Policy Pretraining [[Paper]](https://arxiv.org/pdf/2204.02393.pdf) [[Code]](https://github.com/metadriverse/ACO) [[Dataset]](https://mycuhk-my.sharepoint.com/personal/1155165194_link_cuhk_edu_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F1155165194%5Flink%5Fcuhk%5Fedu%5Fhk%2FDocuments%2Fytb%5Fdriving%5Fvideos&ga=1)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# To-Do Lists
- Published Papers on Conferences
  - [x] Update CVPR papers
  - [ ] Update ICCV papers
  - [ ] Update ECCV papers
  - [ ] Update ACM MM papers
  - [ ] Update NeurIPS papers
  - [ ] Update ICLR papers
- Regular Maintenance of Preprint arXiv Papers and Missed Papers
[<u><small><🎯Back to Top></small></u>](#contents)