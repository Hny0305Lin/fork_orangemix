---
license: creativeml-openrail-m
tags:
- stable-diffusion
- text-to-image
datasets: Nerfgun3/bad_prompt
---



----

# OrangeMixs

"OrangeMixs" shares various Merge models that can be used with StableDiffusionWebui:Automatic1111 and others.Enjoy the drawing AI.

![](https://github.com/WarriorMama777/imgup/raw/main/img/img_general/img_orangemixs_infograph_01_comp001.webp "image_orangemixs_infographics_01")

Maintain a repository for the following purposes.

1. to provide easy access to models commonly used in the Japanese community.The Wisdom of the Anons💎
2. As a place to upload my merge models when I feel like it.

<img src="https://i.imgur.com/VZg0LqQ.png"  width="1000" height="">


----

# Gradio

We support a [Gradio](https://github.com/gradio-app/gradio) Web UI to run OrangeMixs:
[![Open In Spaces](https://camo.githubusercontent.com/00380c35e60d6b04be65d3d94a58332be5cc93779f630bcdfc18ab9a3a7d3388/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f25463025394625413425393725323048756767696e67253230466163652d5370616365732d626c7565)](https://huggingface.co/spaces/akhaliq/webui-orangemixs)

----

# Table of Contents

- [OrangeMixs](#orangemixs)
- [Gradio](#gradio)
- [Table of Contents](#table-of-contents)
- [Reference](#reference)
- [Licence](#licence)
- [Terms of use](#terms-of-use)
- [Disclaimer](#disclaimer)
- [How to download](#how-to-download)
  - [Batch Download](#batch-download)
  - [Batch Download (Advanced)](#batch-download-advanced)
  - [Select and download](#select-and-download)
- [Model Detail \& Merge Recipes](#model-detail--merge-recipes)
  - [AbyssOrangeMix3 (AOM3)](#abyssorangemix3-aom3)
    - [UPDATE NOTE](#update-note)
    - [AOM3](#aom3)
    - [AOM3A1](#aom3a1)
    - [AOM3A2](#aom3a2)
    - [AOM3A3](#aom3a3)
    - [AOM3A1B](#aom3a1b)
    - [MORE](#more)
    - [Sample Gallery](#sample-gallery)
    - [Description for enthusiast](#description-for-enthusiast)
  - [AbyssOrangeMix2 (AOM2)](#abyssorangemix2-aom2)
    - [AbyssOrangeMix2\_sfw (AOM2s)](#abyssorangemix2_sfw-aom2s)
    - [AbyssOrangeMix2\_nsfw (AOM2n)](#abyssorangemix2_nsfw-aom2n)
    - [AbyssOrangeMix2\_hard (AOM2h)](#abyssorangemix2_hard-aom2h)
  - [EerieOrangeMix (EOM)](#eerieorangemix-eom)
    - [EerieOrangeMix (EOM1)](#eerieorangemix-eom1)
      - [EerieOrangeMix\_base (EOM1b)](#eerieorangemix_base-eom1b)
      - [EerieOrangeMix\_Night (EOM1n)](#eerieorangemix_night-eom1n)
      - [EerieOrangeMix\_half (EOM1h)](#eerieorangemix_half-eom1h)
      - [EerieOrangeMix (EOM1)](#eerieorangemix-eom1-1)
    - [EerieOrangeMix2 (EOM2)](#eerieorangemix2-eom2)
      - [EerieOrangeMix2\_base (EOM2b)](#eerieorangemix2_base-eom2b)
      - [EerieOrangeMix2\_night (EOM2n)](#eerieorangemix2_night-eom2n)
      - [EerieOrangeMix2\_half (EOM2h)](#eerieorangemix2_half-eom2h)
      - [EerieOrangeMix2 (EOM2)](#eerieorangemix2-eom2-1)
    - [Models Comparison](#models-comparison)
  - [AbyssOrangeMix (AOM)](#abyssorangemix-aom)
    - [AbyssOrangeMix\_base (AOMb)](#abyssorangemix_base-aomb)
    - [AbyssOrangeMix\_Night (AOMn)](#abyssorangemix_night-aomn)
    - [AbyssOrangeMix\_half (AOMh)](#abyssorangemix_half-aomh)
    - [AbyssOrangeMix (AOM)](#abyssorangemix-aom-1)
  - [ElyOrangeMix (ELOM)](#elyorangemix-elom)
    - [ElyOrangeMix (ELOM)](#elyorangemix-elom-1)
    - [ElyOrangeMix\_half (ELOMh)](#elyorangemix_half-elomh)
    - [ElyNightOrangeMix (ELOMn)](#elynightorangemix-elomn)
  - [BloodOrangeMix (BOM)](#bloodorangemix-bom)
    - [BloodOrangeMix (BOM)](#bloodorangemix-bom-1)
    - [BloodOrangeMix\_half (BOMh)](#bloodorangemix_half-bomh)
    - [BloodNightOrangeMix (BOMn)](#bloodnightorangemix-bomn)
  - [ElderOrangeMix](#elderorangemix)
  - [Troubleshooting](#troubleshooting)
  - [FAQ and Tips (🐈MEME ZONE🦐)](#faq-and-tips-meme-zone)



----

# Reference

+/hdg/ Stable Diffusion Models Cookbook - <https://rentry.org/hdgrecipes#g-anons-unnamed-mix-e93c3bf7>
Model names are named after Cookbook precedents🍊

# Licence

This model is open access and available to all, with a CreativeML OpenRAIL-M license further specifying rights and usage. The CreativeML OpenRAIL License specifies: 
1. You can't use the model to deliberately produce nor share illegal or harmful outputs or content
2. The authors claims no rights on the outputs you generate, you are free to use them and are accountable for their use which must not go against the provisions set in the license
3. You may re-distribute the weights and use the model commercially and/or as a service. If you do, please be aware you have to include the same use restrictions as the ones in the license and share a copy of the CreativeML OpenRAIL-M to all your users (please read the license entirely and carefully) Please read the full license here ：https://huggingface.co/spaces/CompVis/stable-diffusion-license

# Terms of use

- **Clearly indicate where modifications have been made.**  
If you used it for merging, please state what steps you took to do so.

# Disclaimer

<details><summary>READ MORE: Disclaimer</summary>
The user has complete control over whether or not to generate NSFW content, and the user's decision to enjoy either SFW or NSFW is entirely up to the user.The learning model does not contain any obscene visual content that can be viewed with a single click.The posting of the Learning Model is not intended to display obscene material in a public place.  
In publishing examples of the generation of copyrighted characters, I consider the following cases to be exceptional cases in which unauthorised use is permitted. 
"when the use is for private use or research purposes; when the work is used as material for merchandising (however, this does not apply when the main use of the work is to be merchandised); when the work is used in criticism, commentary or news reporting; when the work is used as a parody or derivative work to demonstrate originality."
In these cases, use against the will of the copyright holder or use for unjustified gain should still be avoided, and if a complaint is lodged by the copyright holder, it is guaranteed that the publication will be stopped as soon as possible.  
I would also like to note that I am aware of the fact that many of the merged models use NAI, which is learned from Danbooru and other sites that could be interpreted as illegal, and whose model data itself is also a leak, and that this should be watched carefully. I believe that the best we can do is to expand the possibilities of GenerativeAI while protecting the works of illustrators and artists.  
</details>


----

# How to download

## Batch Download

⚠Deprecated: Orange has grown too huge. Doing this will kill your storage.

1. install Git
2. create a folder of your choice and right click → "Git bash here" and open a gitbash on the folder's directory.
3. run the following commands in order.

```
git lfs install
git clone https://huggingface.co/WarriorMama777/OrangeMixs
```

4. complete


## Batch Download (Advanced)

Advanced: (When you want to download only selected directories, not the entire repository.)
&nbsp;
<details>
<summary>Toggle: How to Batch Download (Advanced)</summary>

1. Run the command `git clone --filter=tree:0 --no-checkout https://huggingface.co/WarriorMama777/OrangeMixs` to clone the huggingface repository. By adding the `--filter=tree:0` and `--no-checkout` options, you can download only the file names without their contents.
```
git clone --filter=tree:0 --no-checkout https://huggingface.co/WarriorMama777/OrangeMixs
```

2. Move to the cloned directory with the command `cd OrangeMixs`.
```
cd OrangeMixs
```

3. Enable sparse-checkout mode with the command `git sparse-checkout init --cone`. By adding the `--cone` option, you can achieve faster performance.
```
git sparse-checkout init --cone
```

4. Specify the directory you want to get with the command `git sparse-checkout add <directory name>`. For example, if you want to get only the `Models/AbyssOrangeMix3` directory, enter `git sparse-checkout add Models/AbyssOrangeMix3`.
```
git sparse-checkout add Models/AbyssOrangeMix3
```

5. Download the contents of the specified directory with the command `git checkout main`.
```
git checkout main
```

This completes how to clone only a specific directory. If you want to add other directories, run `git sparse-checkout add <directory name>` again.


</details>



## Select and download

1. Go to the Files and vaersions tab.
2. select the model you want to download
3. download
4. complete

----



----

# Model Detail & Merge Recipes

## AbyssOrangeMix3 (AOM3)

![](https://github.com/WarriorMama777/imgup/raw/main/img/AOM3/AOM3_G_Top_comp001.webp "")

――Everyone has different “ABYSS”!

▼About

The main model, "AOM3 (AbyssOrangeMix3)", is a purely upgraded model that improves on the problems of the previous version, "AOM2". "AOM3" can generate illustrations with very realistic textures and can generate a wide variety of content. There are also three variant models based on the AOM3 that have been adjusted to a unique illustration style. These models will help you to express your ideas more clearly.

▼Links

- [⚠NSFW] Civitai: AbyssOrangeMix3 (AOM3) | Stable Diffusion Checkpoint | https://civitai.com/models/9942/abyssorangemix3-aom3

### UPDATE NOTE

- 2023-03-11: Change model name : () to _  
Changed to _ because an error occurs when using () in the Cloud environment(e.g.:paperspace).  
"ModelName + _orangemixs"  
- 2023-03-10: Model name fix  
I found that I abbreviated the model name too much, so that when users see illustrations using OrangeMixs models on the web, they cannot reach them in their searches.  
To make the specification more search engine friendly, I renamed it to "ModelName + (orangemixs)".  
- 2023-02-27: Add AOM3A1B  

### AOM3

Features: high-quality, realistic textured illustrations can be generated.  
There are two major changes from AOM2.

1: Models for NSFW such as _nsfw and _hard have been improved: the models after nsfw in AOM2 generated creepy realistic faces, muscles and ribs when using Hires.fix, even though they were animated characters. These have all been improved in AOM3.

e.g.: explanatory diagram by MEME : [GO TO MEME ZONE↓](#MEME_realface)

2: sfw/nsfw merged into one model. Originally, nsfw models were separated because adding NSFW content (models like NAI and gape) would change the face and cause the aforementioned problems. Now that those have been improved, the models can be packed into one.  
In addition, thanks to excellent extensions such as [ModelToolkit](https://github.com/arenatemp/stable-diffusion-webui-model-toolkit
), the model file size could be reduced (1.98 GB per model).


![](https://github.com/WarriorMama777/imgup/raw/main/img/AOM3/AOM3_G_Full_2_comp002.webp "")

▼Variations

### AOM3A1

Features: Anime like illustrations with flat paint. Cute enough as it is, but I really like to apply LoRA of anime characters to this model to generate high quality anime illustrations like a frame from a theatre version.

 ### AOM3A2

Features: Oil paintings like style artistic illustrations and stylish background depictions. In fact, this is mostly due to the work of Counterfeit 2.5, but the textures are more realistic thanks to the U-Net Blocks Weight Merge.

 ### AOM3A3

Features: Midpoint of artistic and kawaii. the model has been tuned to combine realistic textures, a artistic style that also feels like an oil colour style, and a cute anime-style face. Can be used to create a wide range of illustrations.

### AOM3A1B

AOM3A1B added. This model is my latest favorite. I recommend it for its moderate realism, moderate brush touch, and moderate LoRA conformity.  
The model was merged by mistakenly selecting 'Add sum' when 'Add differences' should have been selected in the AOM3A3 recipe. It was an unintended merge, but we share it because the illustrations produced are consistently good results.  
In my review, this is an illustration style somewhere between AOM3A1 and A3.

### MORE
In addition, these U-Net Blocks Weight Merge models take numerous steps but are carefully merged to ensure that mutual content is not overwritten.  

(Of course, all models allow full control over adult content.)
- 🔐 When generating illustrations for the general public: write "nsfw" in the negative prompt field
- 🔞 ~~When generating adult illustrations: "nsfw" in the positive prompt field~~ -> It can be generated without putting it in. If you include it, the atmosphere will be more NSFW.


&nbsp;

![](https://github.com/WarriorMama777/imgup/raw/main/img/AOM3/AOM3_G_Art_comp003.webp "")


### Sample Gallery

🚧Editing🚧

▼AOM3
![](https://github.com/WarriorMama777/imgup/raw/2c840982550fab41f45ba4b5aedbd3d84ddf2390/img/AOM3/img_sanmples_AOM3_01_comp001.webp "OrangeMixs_img_sanmples_AOM3_01_comp001")

<span style="font-size: 80%;">(Actually, this gallery doesn't make much sense since AOM3 is mainly an improvement of the NSFW part 😂  ...But we can confirm that the picture is not much different from AOM2sfw.)</span>


▼A1B

![](https://github.com/WarriorMama777/imgup/raw/c66097319405d5373fab1cebec03c5c71427879c/img/AOM3/img_AOM3A1B_01_comp001.webp "orangemix_img_AOM3A1B_01_comp001.webp")  
![](https://github.com/WarriorMama777/imgup/raw/3e060893c0fb2c80c6f3aedf63bf8d576c9a37fc/img/AOM3/img_samples_AOM3A1B_01_comp001.webp "orangemix_img_samples_AOM3A1B_01_comp001.webp")  
- Meisho Doto (umamusume): https://civitai.com/models/11980/meisho-doto-umamusume
- Train and Girl: [JR East E235 series / train interior](https://civitai.com/models/9517/jr-east-e235-series-train-interior) 

<details>
<summary>©</summary>
©umamusume: Meisho Doto, ©Girls und Panzer: Nishizumi Miho,©IDOLM@STER: Sagisawa Fumika
</details>


▼A1

![](https://github.com/WarriorMama777/imgup/raw/33d21cd31e35ae6b7593e7f6dd913f5f71ddef4e/img/AOM3/img_sanmples_AOMA1_3.0_comp001.webp "OrangeMixs_img_sanmples_AOMA1_3.0_comp001")


<details>
<summary>©</summary>
(1)©Yurucamp: Inuyama Aoi, (2)©The Quintessential Quintuplets: Nakano Yotsuba, (3)©Sailor Moon: Mizuno Ami/SailorMercury
</details>


### Description for enthusiast

AOM3 was created with a focus on improving the nsfw version of AOM2, as mentioned above.The AOM3 is a merge of the following two models into AOM2sfw using U-Net Blocks Weight Merge, while extracting only the NSFW content part.  
(1) NAI: trained in Danbooru  
(2)gape: Finetune model of NAI trained on Danbooru's very hardcore NSFW content.  
In other words, if you are looking for something like AOM3sfw, it is AOM2sfw.The AOM3 was merged with the NSFW model while removing only the layers that have a negative impact on the face and body.   However, the faces and compositions are not an exact match to AOM2sfw.AOM2sfw is sometimes superior when generating SFW content. I recommend choosing according to the intended use of the illustration.See below for a comparison between AOM2sfw and AOM3.

![](https://github.com/WarriorMama777/imgup/raw/main/img/AOM3/img_modelComparison_AOM_comp001.webp "modelComparison_AOM")


▼A summary of the AOM3 work is as follows

1. investigated the impact of the NAI and gape layers as AOM2 _nsfw onwards is crap.  
2. cut face layer: OUT04 because I want realistic faces to stop → Failed. No change.  
3. gapeNAI layer investigation｜  
  a. (IN05-08 (especially IN07) | Change the illustration   significantly. Noise is applied, natural colours are lost, shadows die, and we can see that the IN deep layer is a layer of light and shade.  
  b. OUT03-05(?) | likely to be sexual section/NSFW layer.Cutting here will kill the NSFW.  
  c. OUT03,OUT04｜NSFW effects are in(?). e.g.: spoken hearts, trembling, motion lines, etc...  
  d. OUT05｜This is really an NSFW switch. All the "NSFW atmosphere" is in here. Facial expressions, Heavy breaths, etc...  
  e. OUT10-11｜Paint layer. Does not affect detail, but does have an extensive impact.  
1. (mass production of rubbish from here...)   
2. cut IN05-08 and merge NAIgape with flat parameters → avoided creepy muscles and real faces. Also, merging NSFW models stronger has less impact.  
3. so, cut IN05-08, OUT10-11 and merge NAI+gape with all others 0.5.  
4. → AOM3  
AOM3 roughly looks like this  



----

▼How to use

- Prompts
    - Negative prompts is As simple as possible is good.  
    (worst quality, low quality:1.4)
    - Using "3D" as a negative will result in a rough sketch style at the "sketch" level. Use with caution as it is a very strong prompt.
    - How to avoid Real Face  
    (realistic, lip, nose, tooth, rouge, lipstick, eyeshadow:1.0), (abs, muscular, rib:1.0),
    - How to avoid Bokeh  
    (depth of field, bokeh, blurry:1.4)
    - How to remove mosaic: `(censored, mosaic censoring, bar censor, convenient censoring, pointless censoring:1.0),`
    - How to remove blush: `(blush, embarrassed, nose blush, light blush, full-face blush:1.4), `
    - 🔰Basic negative prompts sample for Anime girl ↓  
      - v1  
    `nsfw, (worst quality, low quality:1.4), (realistic, lip, nose, tooth, rouge, lipstick, eyeshadow:1.0), (dusty sunbeams:1.0),, (abs, muscular, rib:1.0), (depth of field, bokeh, blurry:1.4),(motion lines, motion blur:1.4), (greyscale, monochrome:1.0), text, title, logo, signature`
      - v2  
    `nsfw, (worst quality, low quality:1.4), (lip, nose, tooth, rouge, lipstick, eyeshadow:1.4), (blush:1.2), (jpeg artifacts:1.4), (depth of field, bokeh, blurry, film grain, chromatic aberration, lens flare:1.0), (1boy, abs, muscular, rib:1.0), greyscale, monochrome, dusty sunbeams,  trembling, motion lines, motion blur, emphasis lines, text, title, logo, signature, `
- Sampler: ~~“DPM++ SDE Karras” is good~~ Take your pick  
- Steps: 
  - DPM++ SDE Karras: Test: 12～ ,illustration: 20～  
  - DPM++ 2M Karras: Test: 20～ ,illustration: 28～  
- Clipskip: 1 or 2  
- CFG: 8 (6～12)
- Upscaler :  
    - Detailed illust → Latenet (nearest-exact)  
    Denoise strength: 0.5 (0.5~0.6)  
    - Simple upscale: Swin IR, ESRGAN, Remacri etc…  
    Denoise strength: Can be set low. (0.35~0.6)  



---

👩‍🍳Model details / Recipe

▼Hash

- AOM3.safetensors  
D124FC18F0232D7F0A2A70358CDB1288AF9E1EE8596200F50F0936BE59514F6D
- AOM3A1.safetensors  
F303D108122DDD43A34C160BD46DBB08CB0E088E979ACDA0BF168A7A1F5820E0
- AOM3A2.safetensors  
553398964F9277A104DA840A930794AC5634FC442E6791E5D7E72B82B3BB88C3
- AOM3A3.safetensors  
EB4099BA9CD5E69AB526FCA22A2E967F286F8512D9509B735C892FA6468767CF

▼Use Models

1. AOM2sfw  
「038ba203d8ba3c8af24f14e01fbb870c85bbb8d4b6d9520804828f4193d12ce9」
1. AnythingV3.0 huggingface pruned  
[2700c435]「543bcbc21294831c6245cd74c8a7707761e28812c690f946cb81fef930d54b5e」
1. NovelAI animefull-final-pruned  
[925997e9]「89d59c3dde4c56c6d5c41da34cc55ce479d93b4007046980934b14db71bdb2a8」
1. NovelAI sfw  
[1d4a34af]「22fa233c2dfd7748d534be603345cb9abf994a23244dfdfc1013f4f90322feca」
1. Gape60  
[25396b85]「893cca5903ccd0519876f58f4bc188dd8fcc5beb8a69c1a3f1a5fe314bb573f5」
1. BasilMix  
「bbf07e3a1c3482c138d096f7dcdb4581a2aa573b74a68ba0906c7b657942f1c2」
1. chilloutmix_fp16.safetensors  
「4b3bf0860b7f372481d0b6ac306fed43b0635caf8aa788e28b32377675ce7630」
1. Counterfeit-V2.5_fp16.safetensors  
「71e703a0fca0e284dd9868bca3ce63c64084db1f0d68835f0a31e1f4e5b7cca6」
1. kenshi_01_fp16.safetensors  
「3b3982f3aaeaa8af3639a19001067905e146179b6cddf2e3b34a474a0acae7fa」

----

▼AOM3

▼**Instructions:**

USE: [https://github.com/hako-mikan/sd-webui-supermerger/](https://github.com/hako-mikan/sd-webui-supermerger/)  

(This extension is really great. It turns a month's work into an hour. Thank you)

STEP: 1 | BWM : NAI - NAIsfw & gape - NAI

CUT: IN05-IN08, OUT10-11

| Model: A | Model: B | Model: C | Interpolation Method | Weight                                                                                    | Merge Name |
| -------- | -------- | -------- | -------------------- | ----------------------------------------------------------------------------------------- | ---------- |
| AOM2sfw  | NAI full | NAI sfw  | Add Difference @ 1.0 | 0,0.5,0.5,0.5,0.5,0.5,0,0,0,0,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0,0 | temp01     |

CUT: IN05-IN08, OUT10-11

| Model: A | Model: B | Model: C | Interpolation Method | Weight                                                                                    | Merge Name |
| -------- | -------- | -------- | -------------------- | ----------------------------------------------------------------------------------------- | ---------- |
| temp01   | gape60   | NAI full | Add Difference @ 1.0 | 0,0.5,0.5,0.5,0.5,0.5,0,0,0,0,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0,0 | AOM3       |

▼AOM3A1

▼**Instructions:**

STEP: 1 | Change the base photorealistic model of AOM3 from BasilMix to Chilloutmix.

Change the photorealistic model from BasilMix to Chilloutmix and proceed to gapeNAI merge.

STEP: 2 | 

| Step | Interpolation Method | Primary Model  | Secondary Model | Tertiary Model | Merge Name         |
| ---- | -------------------- | -------------- | --------------- | -------------- | ------------------ |
| 1    | SUM @ 0.5            | Counterfeit2.5 | Kenshi          |                | Counterfeit+Kenshi |

STEP: 3 | 

CUT: BASE0, IN00-IN08：0, IN10：0.1, OUT03-04-05：0, OUT08：0.2

| Model: A | Model: B           | Model: C | Interpolation Method | Weight                                                                      | Merge Name |
| -------- | ------------------ | -------- | -------------------- | --------------------------------------------------------------------------- | ---------- |
| AOM3     | Counterfeit+Kenshi |          | Add SUM @ 1.0        | 0,0,0,0,0,0,0,0,0,0.3,0.1,0.3,0.3,0.3,0.2,0.1,0,0,0,0.3,0.3,0.2,0.3,0.4,0.5 | AOM3A1     |

▼AOM3A2

▼?

CUT: BASE0, IN05:0.3、IN06-IN08：0, IN10：0.1, OUT03：0, OUT04：0.3, OUT05：0, OUT08：0.2

▼**Instructions:**

| Model: A | Model: B       | Model: C | Interpolation Method | Weight                                                    | Merge Name |
| -------- | -------------- | -------- | -------------------- | --------------------------------------------------------- | ---------- |
| AOM3     | Counterfeit2.5 |          | Add SUM @ 1.0        | 0,1,1,1,1,1,0.3,0,0,0,1,0.1,1,1,1,1,1,0,1,0,1,1,0.2,1,1,1 | AOM3A2     |

▼AOM3A3

▼?

CUT : BASE0, IN05-IN08：0, IN10：0.1, OUT03：0.5, OUT04-05：0.1, OUT08：0.2

| Model: A | Model: B       | Model: C | Interpolation Method | Weight                                                                                        | Merge Name |
| -------- | -------------- | -------- | -------------------- | --------------------------------------------------------------------------------------------- | ---------- |
| AOM3     | Counterfeit2.5 |          | Add SUM @ 1.0        | 0,0.6,0.6,0.6,0.6,0.6,0,0,0,0,0.6,0.1,0.6,0.6,0.6,0.6,0.6,0.5,0.1,0.1,0.6,0.6,0.2,0.6,0.6,0.6 | AOM3A3     |

----

&nbsp;

## AbyssOrangeMix2 (AOM2)

――Creating the next generation of illustration with “Abyss”!

<img src="https://github.com/WarriorMama777/imgup/raw/main/img/AbyssOrangeMix2/HeroImage_AbyssOrangeMix2_Designed_01_comp001.webp"  width="" height="" alt=”HeroImage_AbyssOrangeMix2_Designed_01_comp001”>

Prompt: [https://majinai.art/ja/i/nxpKRpw](https://majinai.art/ja/i/nxpKRpw)

▼About

AbyssOrangeMix2 (AOM2) is an AI model capable of generating high-quality, highly realistic illustrations.
It can generate elaborate and detailed illustrations that cannot be drawn by hand. It can also be used for a variety of purposes, making it extremely useful for design and artwork.
Furthermore, it provides an unparalleled new means of expression.
It can generate illustrations in a variety of genres to meet a wide range of needs. I encourage you to use "Abyss" to make your designs and artwork richer and of higher quality.

<img src="https://github.com/WarriorMama777/imgup/raw/main/img/AbyssOrangeMix2/UBM_ON_OFF_4_comp001.webp"  width="" height="" alt=”UBM_ON_OFF_4_comp001.webp”>
※nvidia joke.

▼Description for engineers/enthusiasts

The merged model was formulated using an extension such as sdweb-merge-block-weighted-gui, which merges models at separate rates for each of the 25 U-Net blocks (input, intermediate, and output).
The validation of many Anons has shown that such a recipe can generate a painting style that is anatomically realistic enough to feel the finger skeleton, but still maintains an anime-style face.

The changes from AbyssOrangeMix are as follows.

1. the model used for U-Net Blocks Weight Merge was changed from Instagram+F222 to BasilMix. (<https://huggingface.co/nuigurumi>)

This is an excellent merge model that can generate decent human bodies while maintaining the facial layers of the Instagram model. Thanks!!!
This has improved the dullness of the color and given a more Japanese skin tone (or more precisely, the moisturized white skin that the Japanese would ideally like).
Also, the unnatural bokeh that sometimes occurred in the previous version may have been eliminated (needs to be verified).

2.Added IN deep layers (IN06-11) to the layer merging from the realistic model (BasilMix).

It is said that the IN deep layer (IN06-11) is the layer that determines composition, etc., but perhaps light, reflections, skin texture, etc., may also be involved.
It is like "Global Illumination", "Ray tracing" and "Ambient Occlusion" in 3DCG.

<img src="https://github.com/WarriorMama777/imgup/raw/main/img/AbyssOrangeMix2/AbyssOrangeMix2_comparison_comp001.webp"  width="" height="" alt=”AbyssOrangeMix2_comparison_comp001”>

※This does not fundamentally improve the fingers. Therefore, More research needs to be done to improve the fingers (e.g. '[bad_prompt](https://huggingface.co/datasets/Nerfgun3/bad_prompt)').
About 30-50% chance of generating correct fingers(?). Abyss is deep.

▼Sample Gallery

The prompts for generating these images were all generated using ChatGPT. I simply asked "Pirates sailing the oceans" to tell me what the prompts were.  
However, to make sure the AI understood the specifications, I used the template for AI questions (Question template for AI prompt generation(v1.2) ).
Please review the following.

```jsx
https://seesaawiki.jp/nai_ch/d/AI%a4%f2%b3%e8%cd%d1%a4%b7%a4%bf%a5%d7%a5%ed%a5%f3%a5%d7%a5%c8%c0%b8%c0%ae
```

The images thus generated, strangely enough, look like MidJourney or Nijijourney illustrations. Perhaps they are passing user prompts through GPT or something else before passing them on to the image AI🤔

<img src="https://github.com/WarriorMama777/imgup/raw/main/img/AbyssOrangeMix2/SampleGallerBoardDesign_AbyssOrangeMix2_ReadMore_comp001.webp"  width="" height="" alt=”SampleGallerBoardDesign_AbyssOrangeMix2_03_comp001”>

<details>
<summary>▼READ MORE🖼</summary>

<img src="https://github.com/WarriorMama777/imgup/raw/main/img/AbyssOrangeMix2/SampleGallerBoardDesign_AbyssOrangeMix2_03_comp001.webp"  width="" height="" alt=”SampleGallerBoardDesign_AbyssOrangeMix2_03_comp001”>

▼All prompts to generate sample images

1. [Gaming Girl](https://majinai.art/ja/i/GbTbLyk)
2. [Fantasy](https://majinai.art/ja/i/ax45Pof)
3. [Rainy Day](https://majinai.art/ja/i/1P9DUul)
4. [Kemomimi Girl](https://majinai.art/ja/i/hrUSb31)
5. [Supermarket](https://majinai.art/ja/i/6Mf4bVK)
6. [Lunch Time](https://majinai.art/ja/i/YAgQ4On)
7. [Womens in the Garden](https://majinai.art/ja/i/oHZYum_)
8. [Pirate](https://majinai.art/ja/i/yEA3EZk)
9. [Japanese Girl](https://majinai.art/ja/i/x4G_B_e)
10. [Sweets Time](https://majinai.art/ja/i/vK_mkac)
11. [Glasses Girl](https://majinai.art/ja/i/Z87IHOC)

</details>



▼How to use

- VAE: orangemix.vae.pt
- ~~Prompts can be long or short~~  
As simple as possible is good. Do not add excessive detail prompts. Start with just this negative propmt.  
(worst quality, low quality:1.4)  
- Sampler: “DPM++ SDE Karras” is good
- Steps: forTest: 12～ ,illustration: 20～
- Clipskip: 1 or 2
- Upscaler : Latenet (nearest-exact)
- CFG Scale : 5 or 6 (4～8)
- Denoise strength: 0.5 (0.45~0.6)  
If you use 0.7～, the picture will change too much.  
If below 0.45, Block noise occurs.  

🗒Model List

- AbyssOrangeMix2_sfw｜BasilMix U-Net Blocks Weight Merge
  - AbyssOrangeMix2_nsfw｜+ NAI-NAISFW 0.3 Merge
    - AbyssOrangeMix2_hard｜+ Gape 0.3 Merge

※Changed suffix of models.  
_base →_sfw: _base was changed to_sfw.
_night →_nsfw: Merged models up to NAI-NAI SFW were changed from _night to_nsfw.
_half and non suffix →_hard: Gape merged models were given the suffix _hard.gape was reduced to 0.3 because it affects character modeling.  

▼How to choice models

- _sfw : SFW😉
- _nsfw : SFW ～ Soft NSFW🥰
- _hard : SFW ～ hard NSFW👄

▼Hash

- AbyssOrangeMix2_sfw.ckpt  
「f75b19923f2a4a0e70f564476178eedd94e76e2c94f8fd8f80c548742b5b51b9」  
- AbyssOrangeMix2_sfw.safetensors  
「038ba203d8ba3c8af24f14e01fbb870c85bbb8d4b6d9520804828f4193d12ce9」  
- AbyssOrangeMix2_nsfw.safetensors  
「0873291ac5419eaa7a18726e8841ce0f15f701ace29e0183c47efad2018900a4」  
- AbyssOrangeMix_hard.safetensors  
「0fc198c4908e98d7aae2a76bd78fa004e9c21cb0be7582e36008b4941169f18e」  

▼Use Models

1. AnythingV3.0 huggingface pruned  
[2700c435]「543bcbc21294831c6245cd74c8a7707761e28812c690f946cb81fef930d54b5e」  
1. NovelAI animefull-final-pruned  
[925997e9]「89d59c3dde4c56c6d5c41da34cc55ce479d93b4007046980934b14db71bdb2a8」  
1. NovelAI sfw  
[1d4a34af]「22fa233c2dfd7748d534be603345cb9abf994a23244dfdfc1013f4f90322feca」  
1. Gape60  
[25396b85]「893cca5903ccd0519876f58f4bc188dd8fcc5beb8a69c1a3f1a5fe314bb573f5」  
1. BasilMix  
「bbf07e3a1c3482c138d096f7dcdb4581a2aa573b74a68ba0906c7b657942f1c2」  

### AbyssOrangeMix2_sfw (AOM2s)

▼**Instructions:**

STEP: 1｜Block Merge

| Model: A     | Model: B | Weight                                                                | Base alpha | Merge Name          |
| ------------ | -------- | --------------------------------------------------------------------- | ---------- | ------------------- |
| AnythingV3.0 | BasilMix | 1,0.9,0.7,0.5,0.3,0.1,1,1,1,1,1,1,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1 | 0          | AbyssOrangeMix2_sfw |

### AbyssOrangeMix2_nsfw (AOM2n)

▼?

JUST AbyssOrangeMix2_sfw+ (NAI-NAISFW) 0.3.

▼**Instructions:**

| Step | Interpolation Method | Primary Model       | Secondary Model   | Tertiary Model | Merge Name           |
| ---- | -------------------- | ------------------- | ----------------- | -------------- | -------------------- |
| 1    | Add Difference @ 0.3 | AbyssOrangeMix_base | NovelAI animefull | NovelAI sfw    | AbyssOrangeMix2_nsfw |

### AbyssOrangeMix2_hard (AOM2h)

▼?
+Gape0.3 version AbyssOrangeMix2_nsfw.

▼Instructions

| Step | Interpolation Method | Primary Model        | Secondary Model | Tertiary Model    | Merge Name           |
| ---- | -------------------- | -------------------- | --------------- | ----------------- | -------------------- |
| 1    | Add Difference @ 0.3 | AbyssOrangeMix2_nsfw | Gape60          | NovelAI animefull | AbyssOrangeMix2_hard |

----

## EerieOrangeMix (EOM)

EerieOrangeMix is the generic name for a U-Net Blocks Weight Merge Models based on Elysium(Anime V2).  
Since there are infinite possibilities for U-Net Blocks Weight Merging, I plan to treat all Elysium-based models as a lineage of this model.

※This does not fundamentally improve the fingers. Therefore, More research needs to be done to improve the fingers (e.g. '[bad_prompt](https://huggingface.co/datasets/Nerfgun3/bad_prompt)').

<img src="https://files.catbox.moe/yjnqna.webp"  width="1000" height="" alt=”HeroImage_EerieOrangeMix_Designed_comp001” >


&nbsp;

### EerieOrangeMix (EOM1)

▼?  

This merge model is simply a U-Net Blocks Weight Merge of ElysiumAnime V2 with the AbyssOrangeMix method.

The AnythingModel is good at cute girls anyway, and no matter how hard I try, it doesn't seem to be good at women in their late 20s and beyond. Therefore, I created a U-Net Blocks Weight Merge model based on my personal favorite ElysiumAnime V2 model. ElyOrangeMix was originally my favorite, so this is an enhanced version of that.

🗒Model List  

- EerieOrangeMix_base｜Instagram+F222 U-Net Blocks Weight Merge
  - EerieOrangeMix_night｜+ NAI-NAISFW Merge
    - EerieOrangeMix_half｜+ Gape0.5 Merge
    - EerieOrangeMix｜+ Gape1.0 Merge

▼ How to choice models

- _base : SFW😉
- _Night : SFW ～ Soft NSFW🥰
- _half : SFW ～ NSFW👄
- unlabeled : SFW ～ HARDCORE ～🤯  ex)AbyssOrangeMix, BloodOrangeMix...etc

▼Hash  

- EerieOrangeMix.safetensors
- EerieOrangeMix_half.safetensors
- EerieOrangeMix_night.safetensors
- EerieOrangeMix_base.ckpt

▼Use Models  

[] = WebUI Hash,「」= SHA256

1. Elysium Anime V2
[]「5c4787ce1386500ee05dbb9d27c17273c7a78493535f2603321f40f6e0796851」
2. NovelAI animefull-final-pruned
[925997e9]「89d59c3dde4c56c6d5c41da34cc55ce479d93b4007046980934b14db71bdb2a8」
3. NovelAI sfw
[1d4a34af]「22fa233c2dfd7748d534be603345cb9abf994a23244dfdfc1013f4f90322feca」
4. Gape60
[25396b85]「893cca5903ccd0519876f58f4bc188dd8fcc5beb8a69c1a3f1a5fe314bb573f5」
5. instagram-latest-plus-clip-v6e1_50000.safetensors
[] 「8f1d325b194570754c6bd06cf1e90aa9219a7e732eb3d488fb52157e9451a2a5」
6. f222
[] 「9e2c6ceff3f6d6f65c6fb0e10d8e69d772871813be647fd2ea5d06e00db33c1f」
7. sd1.5_pruned
[] 「e1441589a6f3c5a53f5f54d0975a18a7feb7cdf0b0dee276dfc3331ae376a053」

▼ Sample Gallery  

<img src="https://files.catbox.moe/oqbvti.webp"  width="1000" height="" alt=”2022-12-30_MotorbikeGIrlAsa3_comp001”>
<details>
  <summary>More🖼</summary>
  <img src="https://files.catbox.moe/nmmswd.webp"  width="" height="600" alt=”2022-12-30_SampleGallery5”>
</details>

▼ How to use  

- VAE: orangemix.vae.pt
- As simple as possible is good. Do not add excessive detail prompts. Start with just this.
(worst quality, low quality:1.4)
- Sampler: “DPM++ SDE Karras” is good
- Steps: forTest: 20～24 ,illustration: 24～50
- Clipskip: 1
- USE “upscale latent space”
- Denoise strength: 0.45 (0.4~0.5)  
If you use 0.7～, the picture will change too much.

▼Prompts

🖌When generating cute girls, try this negative prompt first. It avoids low quality, prevents blurring, avoids dull colors, and dictates Anime-like cute face modeling.

```jsx
nsfw, (worst quality, low quality:1.3), (depth of field, blurry:1.2), (greyscale, monochrome:1.1), 3D face, nose, cropped, lowres, text, jpeg artifacts, signature, watermark, username, blurry, artist name, trademark, watermark, title, (tan, muscular, loli, petite, child, infant, toddlers, chibi, sd character:1.1), multiple view, Reference sheet,
```

---

#### EerieOrangeMix_base (EOM1b)

▼?  
Details are omitted since it is the same as AbyssOrangeMix.

▼**Instructions:**

STEP: 1｜Creation of photorealistic model for Merge

| Step | Interpolation Method | Primary Model                         | Secondary Model | Tertiary Model | Merge Name |
| ---- | -------------------- | ------------------------------------- | --------------- | -------------- | ---------- |
| 1    | Add Difference @ 1.0 | instagram-latest-plus-clip-v6e1_50000 | f222            | sd1.5_pruned   | Insta_F222 |

STEP: 2｜Block Merge

Merge InstaF222

| Model: A         | Model: B   | Weight                                                                | Base alpha | Merge Name |
| ---------------- | ---------- | --------------------------------------------------------------------- | ---------- | ---------- |
| Elysium Anime V2 | Insta_F222 | 1,0.9,0.7,0.5,0.3,0.1,0,0,0,0,0,0,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1 | 0          | Temp1      |

#### EerieOrangeMix_Night (EOM1n)

▼?

JUST EerieOrangeMix_base+ (NAI-NAISFW) 0.3.

▼Instructions

| Step | Interpolation Method | Primary Model       | Secondary Model   | Tertiary Model | Merge Name           |
| ---- | -------------------- | ------------------- | ----------------- | -------------- | -------------------- |
| 1    | Add Difference @ 0.3 | EerieOrangeMix_base | NovelAI animefull | NovelAI sfw    | EerieOrangeMix_Night |

#### EerieOrangeMix_half (EOM1h)

▼?
+Gape0.5 version EerieOrangeMix.

▼**Instructions:**

| Step | Interpolation Method | Primary Model        | Secondary Model   | Tertiary Model | Merge Name          |
| ---- | -------------------- | -------------------- | ----------------- | -------------- | ------------------- |
| 1    | Add Difference @ 0.5 | EerieOrangeMix_Night | NovelAI animefull | NovelAI sfw    | EerieOrangeMix_half |

#### EerieOrangeMix (EOM1)

▼**Instructions:**

| Step | Interpolation Method | Primary Model        | Secondary Model | Tertiary Model    | Merge Name     |
| ---- | -------------------- | -------------------- | --------------- | ----------------- | -------------- |
| 1    | Add Difference @ 1.0 | EerieOrangeMix_Night | Gape60          | NovelAI animefull | EerieOrangeMix |

----

### EerieOrangeMix2 (EOM2)

▼?

The model was created by adding the hierarchy responsible for detailing and painting ElysiumV1 to EerieOrangeMix_base, then merging NAI and Gape.

🗒Model List

- EerieOrangeMix2_base｜Instagram+F222+ElysiumV1 U-Net Blocks Weight Merge
  - EerieOrangeMix2_night｜+ NAI-NAISFW Merge
    - EerieOrangeMix2_half｜+ Gape0.5 Merge
    - EerieOrangeMix2｜+ Gape1.0 Merge

▼ How to choice models

- _base : SFW😉
- _Night : SFW ～ Soft NSFW🥰
- _half : SFW ～ NSFW👄
- unlabeled : SFW ～ HARDCORE ～🤯  ex)AbyssOrangeMix, BloodOrangeMix...etc

▼Hash

- EerieOrangeMix2.safetensors
- EerieOrangeMix2_half.safetensors
- EerieOrangeMix2_night.safetensors
- EerieOrangeMix2_base.ckpt

▼Use Models

[] = webuHash,「」= SHA256

1. Elysium Anime V2
[]「5c4787ce1386500ee05dbb9d27c17273c7a78493535f2603321f40f6e0796851」
2. NovelAI animefull-final-pruned
[925997e9]「89d59c3dde4c56c6d5c41da34cc55ce479d93b4007046980934b14db71bdb2a8」
3. NovelAI sfw
[1d4a34af]「22fa233c2dfd7748d534be603345cb9abf994a23244dfdfc1013f4f90322feca」
4. Gape60
[25396b85]「893cca5903ccd0519876f58f4bc188dd8fcc5beb8a69c1a3f1a5fe314bb573f5」
5. instagram-latest-plus-clip-v6e1_50000.safetensors
[] 「8f1d325b194570754c6bd06cf1e90aa9219a7e732eb3d488fb52157e9451a2a5」
6. f222
[] 「9e2c6ceff3f6d6f65c6fb0e10d8e69d772871813be647fd2ea5d06e00db33c1f」
7. sd1.5_pruned
[] 「e1441589a6f3c5a53f5f54d0975a18a7feb7cdf0b0dee276dfc3331ae376a053」
8. ElysiumV1
「abbb28cb5e70d3e0a635f241b8d61cefe42eb8f1be91fd1168bc3e52b0f09ae4」

#### EerieOrangeMix2_base (EOM2b)

▼?

▼Instructions

STEP: 1｜Block Merge

Merge ElysiumV1

The generated results do not change much with or without this process, but I wanted to incorporate Elysium's depiction, so I merged it.

| Model: A            | Model: B  | Weight                                                                | Base alpha | Merge Name           |
| ------------------- | --------- | --------------------------------------------------------------------- | ---------- | -------------------- |
| EerieOrangeMix_base | ElysiumV1 | 1,0.9,0.7,0.5,0.3,0.1,0,0,0,0,0,0,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1 | 0          | EerieOrangeMix2_base |

#### EerieOrangeMix2_night (EOM2n)

▼?

JUST EerieOrangeMix2_base+ (NAI-NAISFW) 0.3.

▼Instructions

| Step | Interpolation Method | Primary Model       | Secondary Model   | Tertiary Model | Merge Name            |
| ---- | -------------------- | ------------------- | ----------------- | -------------- | --------------------- |
| 1    | Add Difference @ 0.3 | EerieOrangeMix_base | NovelAI animefull | NovelAI sfw    | EerieOrangeMix2_Night |

#### EerieOrangeMix2_half (EOM2h)

▼?
+Gape0.5 version EerieOrangeMix2.

▼Instructions

| Step | Interpolation Method | Primary Model        | Secondary Model   | Tertiary Model | Merge Name           |
| ---- | -------------------- | -------------------- | ----------------- | -------------- | -------------------- |
| 1    | Add Difference @ 0.5 | EerieOrangeMix_Night | NovelAI animefull | NovelAI sfw    | EerieOrangeMix2_half |

#### EerieOrangeMix2 (EOM2)

▼**Instructions:**

| Step | Interpolation Method | Primary Model        | Secondary Model | Tertiary Model    | Merge Name      |
| ---- | -------------------- | -------------------- | --------------- | ----------------- | --------------- |
| 1    | Add Difference @ 1.0 | EerieOrangeMix_Night | Gape60          | NovelAI animefull | EerieOrangeMix2 |

### Models Comparison

<img src="https://files.catbox.moe/mp2fr4.webp"  width="1000" height="" alt="MotorbikeGIrlAsa_Eerie_Abyss_Comparison_comp001">  
<img src="https://files.catbox.moe/9xqths.webp"  width="1000" height="" alt=”Eerie_Abyss_Comparison_02_comp001”>
<img src="https://files.catbox.moe/cm6c7m.webp"  width="1000" height="" alt=”Eerie_Comparison_01_comp001”>  
※The difference is slight but probably looks like this.
← warm color, ↑ natural color, → animated color

----

## AbyssOrangeMix (AOM)

――How can you guys take on such a deep swamp and get results?  
Is it something like "Made in Abyss"?  
By Anon, 115th thread

<img src="https://files.catbox.moe/wst1bp.webp"  width="1000" height="">


▼?

The merged model was formulated using an extension such as sdweb-merge-block-weighted-gui, which merges models at separate rates for each of the 25 U-Net blocks (input, intermediate, and output).
The validation of many Anons has shown that such a recipe can generate a painting style that is anatomically realistic enough to feel the finger skeleton, but still maintains an anime-style face.

※This model is the result of a great deal of testing and experimentation by many Anons🤗
※This model can be very difficult to handle. I am not 100% confident in my ability to use this model. It is peaky and for experts.  
※This does not fundamentally improve the fingers, and I recommend using bad_prompt, etc. (Embedding) in combination.  

▼Sample Gallery

(1)
<img src="https://files.catbox.moe/8mke0t.webp" width="1000" height="">

```jsx
((masterpiece)), best quality, perfect anatomy, (1girl, solo focus:1.4), pov, looking at viewer, flower trim,(perspective, sideway, From directly above ,lying on water, open hand, palm, :1.3),(Accurate five-fingered hands, Reach out, hand focus, foot focus, Sole, heel, ball of the thumb:1.2), (outdoor, sunlight:1.2),(shiny skin:1.3),,(masterpiece, white border, outside border, frame:1.3),
, (motherhood, aged up, mature female, medium breasts:1.2), (curvy:1.1), (single side braid:1.2), (long hair with queue and braid, disheveled hair, hair scrunchie, tareme:1.2), (light Ivory hair:1.2), looking at viewer,, Calm, Slight smile,
,(anemic, dark, lake, river,puddle, Meadow, rock, stone, moss, cliff, white flower, stalactite, Godray, ruins, ancient, eternal, deep ,mystic background,sunlight,plant,lily,white flowers, Abyss, :1.2), (orange fruits, citrus fruit, citrus fruit bearing tree:1.4), volumetric lighting,good lighting,, masterpiece, best quality, highly detailed,extremely detailed cg unity 8k wallpaper,illustration,((beautiful detailed face)), best quality, (((hyper-detailed ))), high resolution illustration ,high quality, highres, sidelighting, ((illustrationbest)),highres,illustration, absurdres, hyper-detailed, intricate detail, perfect, high detailed eyes,perfect lighting, (extremely detailed CG:1.2),

Negative prompt: (bad_prompt_version2:1), distant view, lip, Pregnant, maternity, pointy ears, realistic, tan, muscular, greyscale, monochrome, lineart, 2koma, 3koma, 4koma, manga, 3D, 3Dcubism, pablo picasso, disney, marvel, mutanted breasts, mutanted nipple, cropped, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name, lowres, trademark, watermark, title, text, deformed, bad anatomy, disfigured, mutated, extra limbs, ugly, missing limb, floating limbs, disconnected limbs, out of frame, mutated hands and fingers, poorly drawn hands, malformed hands, poorly drawn face, poorly drawn asymmetrical eyes, (blurry:1.4), duplicate (loli, petite, child, infant, toddlers, chibi, sd character, teen age:1.4), tsurime, helmet hair, evil smile, smug_face, naughty smile, multiple view, Reference sheet, (worst quality, low quality:1.4),
Steps: 24, Sampler: DPM++ SDE Karras, CFG scale: 10, Seed: 1159970659, Size: 1536x768, Model hash: cc44dbff, Model: AbyssOrangeMix, Variation seed: 93902374, Variation seed strength: 0.45, Denoising strength: 0.45, ENSD: 31337
```

(2)
<img src="https://files.catbox.moe/6cbrqh.webp" width="" height="600">

```jsx
street, 130mm f1.4 lens, ,(shiny skin:1.3),, (teen age, school uniform:1.2), (glasses, black hair, medium hair with queue and braid, disheveled hair, hair scrunchie, tareme:1.2), looking at viewer,, Calm, Slight smile,

Negative prompt: (bad_prompt_version2:1), distant view, lip, Pregnant, maternity, pointy ears, realistic, tan, muscular, greyscale, monochrome, lineart, 2koma, 3koma, 4koma, manga, 3D, 3Dcubism, pablo picasso, disney, marvel, mutanted breasts, mutanted nipple, cropped, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name, lowres, trademark, watermark, title, text, deformed, bad anatomy, disfigured, mutated, extra limbs, ugly, missing limb, floating limbs, disconnected limbs, out of frame, mutated hands and fingers, poorly drawn hands, malformed hands, poorly drawn face, poorly drawn asymmetrical eyes, (blurry:1.4), duplicate (loli, petite, child, infant, toddlers, chibi, sd character, teen age:1.4), tsurime, helmet hair, evil smile, smug_face, naughty smile, multiple view, Reference sheet, (worst quality, low quality:1.4),
Steps: 24, Sampler: DPM++ SDE Karras, CFG scale: 10, Seed: 1140782193, Size: 1024x1536, Model hash: cc44dbff, Model: AbyssOrangeMix, Denoising strength: 0.45, ENSD: 31337, First pass size: 512x768, Model sha256: 6bb3a5a3b1eadd32, VAE sha256: f921fb3f29891d2a, Options: xformers medvram gtx_16x0

Used embeddings: bad_prompt_version2 [afea]
```

----

▼How to use

- VAE: orangemix.vae.pt
- ~~Prompts can be long or short~~  
As simple as possible is good. Do not add excessive detail prompts. Start with just this.
(worst quality, low quality:1.4)
- Sampler: “DPM++ SDE Karras” is good
- Steps: forTest: 20～24 ,illustration: 24～50
- Clipskip: 1
- USE “upscale latent space”
- Denoise strength: 0.45 (0.4~0.5)
If you use 0.7～, the picture will change too much.

▼Prompts

🖌When generating cute girls, try this negative prompt first. It avoids low quality, prevents blurring, avoids dull colors, and dictates Anime-like cute face modeling.

```jsx
nsfw, (worst quality, low quality:1.3), (depth of field, blurry:1.2), (greyscale, monochrome:1.1), 3D face, nose, cropped, lowres, text, jpeg artifacts, signature, watermark, username, blurry, artist name, trademark, watermark, title, (tan, muscular, loli, petite, child, infant, toddlers, chibi, sd character:1.1), multiple view, Reference sheet,
```

🗒Model List

- AbyssOrangeMix_base｜Instagram Merge
  - AbyssOrangeMix_Night｜+ NAI-NAISFW Merge
    - AbyssOrangeMix_half｜+ Gape0.5 Merge
    - AbyssOrangeMix｜+ Gape1.0 Merge

▼ How to choice models

- _base : SFW😉
- _Night : SFW ～ Soft NSFW🥰
- _half : SFW ～ NSFW👄
- unlabeled : SFW ～ HARDCORE ～🤯  ex)AbyssOrangeMix, BloodOrangeMix...etc

▼Hash (SHA256)

- AbyssOrangeMix.safetensors  
6bb3a5a3b1eadd32dfbc8f0987559c48cb4177aee7582baa6d6a25181929b345
- AbyssOrangeMix_half.safetensors  
468d1b5038c4fbd354113842e606fe0557b4e0e16cbaca67706b29bcf51dc402
- AbyssOrangeMix_Night.safetensors  
167cd104699dd98df22f4dfd3c7a2c7171df550852181e454e71e5bff61d56a6
- AbyssOrangeMix_base.ckpt  
bbd2621f3ec4fad707f75fc032a2c2602c296180a53ed3d9897d8ca7a01dd6ed

▼Use Models

1. AnythingV3.0 huggingface pruned
[2700c435]「543bcbc21294831c6245cd74c8a7707761e28812c690f946cb81fef930d54b5e」
1. NovelAI animefull-final-pruned
[925997e9]「89d59c3dde4c56c6d5c41da34cc55ce479d93b4007046980934b14db71bdb2a8」
1. NovelAI sfw
[1d4a34af]「22fa233c2dfd7748d534be603345cb9abf994a23244dfdfc1013f4f90322feca」
1. Gape60
[25396b85]「893cca5903ccd0519876f58f4bc188dd8fcc5beb8a69c1a3f1a5fe314bb573f5」
1. instagram-latest-plus-clip-v6e1_50000.safetensors
[] 「8f1d325b194570754c6bd06cf1e90aa9219a7e732eb3d488fb52157e9451a2a5」
1. f222
[] 「9e2c6ceff3f6d6f65c6fb0e10d8e69d772871813be647fd2ea5d06e00db33c1f」
1. sd1.5_pruned
[] 「e1441589a6f3c5a53f5f54d0975a18a7feb7cdf0b0dee276dfc3331ae376a053」

### AbyssOrangeMix_base (AOMb)

▼?

The basic trick for this merged model is to incorporate a model that has learned more than 1m Instagram photos (mostly Japanese) or a photorealistic model like f222. The choice of base model here depends on the person. I chose AnythingV3 for versatility.

▼**Instructions:**

STEP: 1｜Creation of photorealistic model for Merge

| Step | Interpolation Method | Primary Model                         | Secondary Model | Tertiary Model | Merge Name |
| ---- | -------------------- | ------------------------------------- | --------------- | -------------- | ---------- |
| 1    | Add Difference @ 1.0 | instagram-latest-plus-clip-v6e1_50000 | f222            | sd1.5_pruned   | Insta_F222 |

STEP: 2｜Block Merge

| Model: A     | Model: B   | Weight                                                                | Base alpha | Merge Name          |
| ------------ | ---------- | --------------------------------------------------------------------- | ---------- | ------------------- |
| AnythingV3.0 | Insta_F222 | 1,0.9,0.7,0.5,0.3,0.1,0,0,0,0,0,0,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1 | 0          | AbyssOrangeMix_base |

### AbyssOrangeMix_Night (AOMn)

▼?

JUST AbyssOrangeMix_base+ (NAI-NAISFW) 0.3.

▼**Instructions:**

| Step | Interpolation Method | Primary Model       | Secondary Model   | Tertiary Model | Merge Name           |
| ---- | -------------------- | ------------------- | ----------------- | -------------- | -------------------- |
| 1    | Add Difference @ 0.3 | AbyssOrangeMix_base | NovelAI animefull | NovelAI sfw    | AbyssOrangeMix_Night |

### AbyssOrangeMix_half (AOMh)

▼?
+Gape0.5 version AbyssOrangeMix.

▼**Instructions:**

| Step | Interpolation Method | Primary Model        | Secondary Model | Tertiary Model    | Merge Name          |
| ---- | -------------------- | -------------------- | --------------- | ----------------- | ------------------- |
| 1    | Add Difference @ 0.5 | AbyssOrangeMix_Night | Gape60          | NovelAI animefull | AbyssOrangeMix_half |

### AbyssOrangeMix (AOM)

▼**Instructions:**

| Step | Interpolation Method | Primary Model        | Secondary Model | Tertiary Model    | Merge Name     |
| ---- | -------------------- | -------------------- | --------------- | ----------------- | -------------- |
| 1    | Add Difference @ 1.0 | AbyssOrangeMix_Night | Gape60          | NovelAI animefull | AbyssOrangeMix |

----

## ElyOrangeMix (ELOM)

<img src="https://i.imgur.com/AInEXA5.jpg"  width="1000" height="">

▼?  
Elysium_Anime_V2 + NAI + Gape.  
This is a merge model that improves on the Elysium_Anime_V2, where NSFW representation is not good.  
It can produce SFW, NSFW, and any other type of artwork, while retaining the Elysium's three-dimensional, thickly painted style.

▼ How to choice models

- _base : SFW😉
- _Night : SFW ～ Soft NSFW🥰
- _half : SFW ～ NSFW👄
- unlabeled : SFW ～ HARDCORE ～🤯  ex)AbyssOrangeMix, BloodOrangeMix...etc

▼How to use
- VAE: orangemix.vae.pt

▼Hash (SHA256)

- ElyOrangeMix [6b508e59]
- ElyOrangeMix_half [6b508e59]
- ElyNightOrangeMix[6b508e59]


### ElyOrangeMix (ELOM)

▼Use Models

1. Elysium_Anime_V2 [6b508e59]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

▼Instructions

| Step | Interpolation Method | Primary Model    | Secondary Model   | Tertiary Model    | Merge Name               |
| ---- | -------------------- | ---------------- | ----------------- | ----------------- | ------------------------ |
| 1    | Add Difference @ 0.3 | Elysium_Anime_V2 | NovelAI animefull | NovelAI sfw       | tempmix-part1 []         |
| 2    | Add Difference @ 1.0 | tempmix-part1    | Gape60            | NovelAI animefull | ElyOrangeMix  [6b508e59] |

---

### ElyOrangeMix_half (ELOMh)

▼?

+Gape0.5 version ElyOrangeMix.

▼Use Models

1. Elysium_Anime_V2 [6b508e59]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

▼Instructions

| Step | Interpolation Method | Primary Model    | Secondary Model   | Tertiary Model    | Merge Name                    |
| ---- | -------------------- | ---------------- | ----------------- | ----------------- | ----------------------------- |
| 1    | Add Difference @ 0.3 | Elysium_Anime_V2 | NovelAI animefull | NovelAI sfw       | tempmix-part1 []              |
| 2    | Add Difference @ 0.5 | tempmix-part1    | Gape60            | NovelAI animefull | ElyOrangeMix_half  [6b508e59] |

----

### ElyNightOrangeMix (ELOMn)

▼?

It is a merged model that just did Elysium_Anime_V2+ (NAI-NAISFW) 0.3.

▼Use Models

1. Elysium_Anime_V2 [6b508e59]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]

▼Instructions

| Step | Interpolation Method | Primary Model    | Secondary Model   | Tertiary Model | Merge Name        |
| ---- | -------------------- | ---------------- | ----------------- | -------------- | ----------------- |
| 1    | Add Difference @ 0.3 | Elysium_Anime_V2 | NovelAI animefull | NovelAI sfw    | ElyNightOrangeMix |

----

## BloodOrangeMix (BOM)

<img src="https://i.imgur.com/soAnnFk.jpg"  width="1000" height="">

▼?
Anything+NAI+Gape.  
This is a merge model that improves on the AnythingV3, where NSFW representation is not good.  
It can produce SFW, NSFW, and any other type of artwork, while retaining the flat, beautifully painted style of AnythingV3.  
Stable. Popular in the Japanese community.  

▼ModelList & [] = WebUI Hash,「」= SHA256

- BloodNightOrangeMix.ckpt  
  [ffa7b160]「f8aff727ba3da0358815b1766ed232fd1ef9682ad165067cac76e576d19689e0」
- BloodOrangeMix_half.ckpt  
 [ffa7b160]「b2168aaa59fa91229b8add21f140ac9271773fe88a387276f3f0c7d70f726a83」
- BloodOrangeMix.ckpt  
[ffa7b160] 「25cece3fe303ea8e3ad40c3dca788406dbd921bcf3aa8e3d1c7c5ac81f208a4f」
- BloodOrangeMix.safetensors  
「79a1edf6af43c75ee1e00a884a09213a28ee743b2e913de978cb1f6faa1b320d」

▼ How to choice models

- _base : SFW😉
- _Night : SFW ～ Soft NSFW🥰
- _half : SFW ～ NSFW👄
- unlabeled : SFW ～ HARDCORE ～🤯  ex)AbyssOrangeMix, BloodOrangeMix...etc

▼How to use
- VAE: orangemix.vae.pt

### BloodOrangeMix (BOM)

▼Use Models

1. AnythingV3.0 huggingface pruned [2700c435]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

▼Instructions

| Step | Interpolation Method | Primary Model | Secondary Model   | Tertiary Model    | Merge Name                |
| ---- | -------------------- | ------------- | ----------------- | ----------------- | ------------------------- |
| 1    | Add Difference @ 0.3 | AnythingV3.0  | NovelAI animefull | NovelAI sfw       | tempmix-part1 []          |
| 2    | Add Difference @ 1.0 | tempmix-part1 | Gape60            | NovelAI animefull | BloodOrangeMix [ffa7b160] |

----

### BloodOrangeMix_half (BOMh)

▼?
Anything+Nai+Gape0.5
+Gape0.5 version BloodOrangeMix.
NSFW expression will be softer and have less impact on the Anything style painting style.

▼Use Models

1. AnythingV3.0 huggingface pruned [2700c435]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

▼Instructions

| Step | Interpolation Method | Primary Model | Secondary Model   | Tertiary Model    | Merge Name                     |
| ---- | -------------------- | ------------- | ----------------- | ----------------- | ------------------------------ |
| 1    | Add Difference @ 0.3 | AnythingV3.0  | NovelAI animefull | NovelAI sfw       | tempmix-part1 []               |
| 2    | Add Difference @ 0.5 | tempmix-part1 | Gape60            | NovelAI animefull | BloodOrangeMix_half [ffa7b160] |

----

### BloodNightOrangeMix (BOMn)

▼?

It is a merged model that just did AnythingV3+ (NAI-NAISFW) 0.3.

▼Use Models

1. AnythingV3.0 huggingface pruned [2700c435]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]

▼Instructions

| Step | Interpolation Method | Primary Model | Secondary Model   | Tertiary Model | Merge Name          |
| ---- | -------------------- | ------------- | ----------------- | -------------- | ------------------- |
| 1    | Add Difference @ 0.3 | AnythingV3.0  | NovelAI animefull | NovelAI sfw    | BloodNightOrangeMix |

----

## ElderOrangeMix 

※I found this model to be very prone to body collapse. Not recommended.

▼?  
anything and everything mix ver.1.5+Gape+Nai(AnEve.G.N0.3)  
This is a merged model with improved NSFW representation of anything and everything mix ver.1.5.

▼Hash
[3a46a1e0]

▼Use Models

1. anything and everything mix ver.1.5 [5265dcf6]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

▼Instructions:**

| Step | Interpolation Method | Primary Model                       | Secondary Model | Tertiary Model | Merge Name                 |
| ---- | -------------------- | ----------------------------------- | --------------- | -------------- | -------------------------- |
| 1    | Add Difference @ 0.5 | anything and everything mix ver.1.5 | Gape60          | NovelAI full   | tempmix-part1 []           |
| 2    | Add Difference @ 0.3 | tempmix-part1                       | NovelAI full    | NovelAI sfw    | ElderOrangeMix  [3a46a1e0] |

----

## Troubleshooting

1. blurred Images & clearly low quality output  
If the generated images are blurred or only clearly low quality output is produced, it is possible that the vae, etc. are not loaded properly. Try reloading the model/vae or restarting the WebUI/OS.

## FAQ and Tips (🐈MEME ZONE🦐)

<a name="MEME_realface"></a>
Trash zone.

----

▼No, AOM2 (only hentai models)  


![](https://github.com/WarriorMama777/imgup/raw/main/img/img_general/img_Neko.webp "")


▼Nooo^()&*%#NG0u!!!!!!!!縺ゅ♀繧?縺医?縺､繝ｼ縺ｨ縺医?縺吶ｊ繝ｼ縺ｯ驕主ｭｦ鄙偵?繧ｴ繝溘〒縺? (「AOM3A2 and A3 are overlearning and Trash. delete!」)

<img src="https://github.com/WarriorMama777/imgup/raw/main/img/img_general/img_meme_tension_comp001.webp"  width="300" height="" alt=”getting_excited”>


▼Noo, Too many models. Tell me which one to choose.  

→ [全部同じじゃないですか](https://github.com/WarriorMama777/imgup/blob/main/img/img_general/img_MEME_whichModel_comp001.webp?raw=true "全部同じじゃないですか")

▼Nooo, not work. This guy is Scammer  
STEP1: BUY HUGE PC  

▼Noooo, can't generate image like samples.This models is hype. 

❌  
<img src="https://files.catbox.moe/nte6ud.webp"  width="500" height="">  

🟢  
<img src="https://files.catbox.moe/lta462.webp"  width="500" height="">  


▼Nooooo, This models have troy virus. don't download.  
All models in this repository are secure. It is most likely that anti-virus software has detected them erroneously.  
However, the models with the .ckpt extension have the potential danger of executing arbitrary code.  
A safe model that is free from these dangers is the model with the .safetensors extension.  


