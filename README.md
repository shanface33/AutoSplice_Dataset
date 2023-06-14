# AutoSplice: A Text-prompt Manipulated Image Dataset

[Shan Jia](https://shanface33.github.io/), Mingzhen Huang, Zhou Zhou, Yan Ju, Jialing Cai, [Siwei Lyu](https://cse.buffalo.edu/~siweilyu/)
University at Buffalo, State University of New York, NY, USA

The AutoSplice dataset was proposed in the [CVPR2023 Workshop on Media Forensics](https://sites.google.com/view/wmf2023/home) paper "AutoSplice: A Text-prompt Manipulated Image Dataset for Media Forensics", which leverages the DALL-E2 [^1] language-image model to automatically generate and splice masked regions guided by a text prompt. It consists of 5,894 manipulated and authentic images. 

[[Paper]](https://openaccess.thecvf.com/content/CVPR2023W/WMF/papers/Jia_AutoSplice_A_Text-Prompt_Manipulated_Image_Dataset_for_Media_Forensics_CVPRW_2023_paper.pdf) [[Download]](https://docs.google.com/forms/d/1bHbWZ-DsG1-VKaMs4Puy0996yj485x7HK13fgbNRerE/edit)

![fig1_compressed-1](Figure/Fig1.png)

## Summary 
The database contains 3, 621 images by locally or globally manipulating real-world images, and 2, 273 authentic images.

Three JPEG compression versions along with their manipulation masks are included, 
- JPEG-100, lossless compression with a JPEG quality factor of 100;
- JPEG-90, gently lossy compression with a JPEG quality factor of 90;
- JPEG-75, lossy compression with a JPEG factor of 75 (the same as the authentic images derived from Visual News dataset[^2]), used for fine-tuning tasks.

![fig1_compressed-1](Figure/Fig2.png)
[^1]: Ramesh, Aditya, et al. "Hierarchical text-conditional image generation with clip latents." arXiv preprint arXiv:2204.06125 (2022).
[^2]: Liu, Fuxiao, et al. "Visual news: Benchmark and challenges in news image captioning." Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing (2021).

## Dataset Download
If you would like to access the *AutoSplice* dataset, please fill out this [google form](https://docs.google.com/forms/d/1bHbWZ-DsG1-VKaMs4Puy0996yj485x7HK13fgbNRerE/edit). The download link will be sent to you once the form is accepted (in 48 hours). If you have any questions, please send email to [autosplice.dataset@gmail.com].

## License and Citation
The AutoSplice dataset is released only for academic research. Researchers from educational institute are allowed to use this database freely for noncommercial purpose.

If you use this dataset, please cite the following papers:
```
@inproceedings{jia2023autosplice,
  title={AutoSplice: A Text-prompt Manipulated Image Dataset for Media Forensics},
  author={Jia, Shan and Huang, Mingzhen and Zhou, Zhou and Ju, Yan and Cai, Jialing and Lyu, Siwei},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={893--903},
  year={2023}
}
