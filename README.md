---
license: cc0-1.0
tags:
  - stable-diffusion
  - text-to-image
---

----



# OrangeMixs🍊
"OrangeMixs" shares various Merge models that can be used with StableDiffusionWebui:Automatic1111 and others.

Maintain a repository for the following purposes.
1. to provide easy access to models commonly used in the Japanese community.The Wisdom of the Anons💎
3. As a place to upload my merge models when I feel like it.

<img src="https://i.imgur.com/VZg0LqQ.png"  width="1000" height="">


# Reference
+/hdg/ Stable Diffusion Models Cookbook - https://rentry.org/hdgrecipes#g-anons-unnamed-mix-e93c3bf7
Model names are named after Cookbook precedents🍊

# Disclaimer
The user has complete control over whether or not to generate NSFW content, and the user's decision to enjoy either SFW or NSFW is entirely up to the user. 
The learning model does not contain any obscene visual content that can be viewed with a single click. 
The posting of the Learning Model is not intended to display obscene material in a public place.

----

# How to download

## Batch Download

1. install Git
2. create a folder of your choice and right click → "Git bash here" and open a gitbash on the folder's directory.
3. run the following commands in order.
```
git lfs install
git clone https://huggingface.co/WarriorMama777/OrangeMixs
```
4. complete



## select and download

1. Go to the Files and vaersions tab.
2. select the model you want to download
3. download
4. complete


----

# Model Detail & Merge Recipes🍊


## AbyssOrangeMix2

――Creating the next generation of illustration with “Abyss”!

<img src="https://github.com/WarriorMama777/imgup/blob/main/img/AbyssOrangeMix2/HeroImage_AbyssOrangeMix2_Designed_01_comp001.webp?raw=true"  width="" height="" alt=”HeroImage_AbyssOrangeMix2_Designed_01_comp001”>

▼About

AbyssOrangeMix2 is an AI model capable of generating high-quality, highly realistic illustrations. 
It can generate elaborate and detailed illustrations that cannot be drawn by hand. It can also be used for a variety of purposes, making it extremely useful for design and artwork.
Furthermore, it provides an unparalleled new means of expression. 
It can generate illustrations in a variety of genres to meet a wide range of needs. I encourage you to use "Abyss" to make your designs and artwork richer and of higher quality.

▼Description for engineers/enthusiasts

The merged model was formulated using an extension such as sdweb-merge-block-weighted-gui, which merges models at separate rates for each of the 25 U-Net blocks (input, intermediate, and output).
The validation of many Anons has shown that such a recipe can generate a painting style that is anatomically realistic enough to feel the finger skeleton, but still maintains an anime-style face.

The changes from AbyssOrangeMix are as follows.

1. the model used for U-Net Blocks Weight Merge was changed from Instagram+F222 to BasilMix. (https://huggingface.co/nuigurumi)

This is an excellent merge model that can generate decent human bodies while maintaining the facial layers of the Instagram model. Thanks!!!
This has improved the dullness of the color and given a more Japanese skin tone (or more precisely, the moisturized white skin that the Japanese would ideally like).
Also, the unnatural bokeh that sometimes occurred in the previous version may have been eliminated (needs to be verified). 

2.Added IN deep layers (IN06-11) to the layer merging from the realistic model (BasilMix).

It is said that the IN deep layer (IN06-11) is the layer that determines composition, etc., but perhaps light, reflections, skin texture, etc., may also be involved.
It is like "Global Illumination," "Normal Map," and "Ambient Occlusion" in 3DCG.

<img src="https://github.com/WarriorMama777/imgup/blob/main/img/AbyssOrangeMix2/AbyssOrangeMix2_comparison_comp001.webp?raw=true"  width="" height="" alt=”AbyssOrangeMix2_comparison_comp001”>

※This does not fundamentally improve the fingers, and I recommend using bad_prompt, etc. (Embedding) in combination.  
About 30-50% chance of generating correct fingers(?). Abyss is deep.

▼Sample Gallery

The prompts for generating these images were all generated using ChatGPT. I simply asked "Pirates sailing the oceans" to tell me what the prompts were.  
However, to make sure the AI understood the specifications, I used the template for AI questions (Question template for AI prompt generation(v1.2) ).   
Please review the following.

```jsx
https://seesaawiki.jp/nai_ch/d/AI%a4%f2%b3%e8%cd%d1%a4%b7%a4%bf%a5%d7%a5%ed%a5%f3%a5%d7%a5%c8%c0%b8%c0%ae
```

The images thus generated, strangely enough, look like MidJourney or Nijijourney illustrations. Perhaps they are passing user prompts through GPT or something else before passing them on to the image AI🤔

<img src="https://github.com/WarriorMama777/imgup/blob/main/img/AbyssOrangeMix2/SampleGallerBoardDesign_AbyssOrangeMix2_ReadMore_comp001.webp?raw=true"  width="" height="" alt=”SampleGallerBoardDesign_AbyssOrangeMix2_03_comp001”>

<details>
<summary>▼READ MORE🖼</summary>

<img src="https://github.com/WarriorMama777/imgup/blob/main/img/AbyssOrangeMix2/SampleGallerBoardDesign_AbyssOrangeMix2_03_comp001.webp?raw=true"  width="" height="" alt=”SampleGallerBoardDesign_AbyssOrangeMix2_03_comp001”>
</details>

All prompts to generate sample images ※Preparing

1. a
2. a
3. a
4. a
5. a
6. a
7. a
8. a
9. a
10. a
11. a

▼How to use

- ~~Prompts can be long or short~~  
As simple as possible is good. Do not add excessive detail prompts. Start with just this negative propmt.  
(worst quality, low quality:1.4)  
- Sampler: “DPM++ SDE Karras” is good
- Steps: forTest: 12～ ,illustration: 20～
- Clipskip: 1 or 2
- Upscaler : Latenet (nearest-exact)
- Denoise strength: 0.5 (0.5~0.6)  
If you use 0.7～, the picture will change too much.  
If below 0.45, Block noise occurs.  

🗒Model List

- AbyssOrangeMix2_sfw｜BasilMix U-Net Blocks Weight Merge
    - AbyssOrangeMix2_nsfw｜+ NAI-NAISFW Merge
        - AbyssOrangeMix2_hard｜+ Gape0.3 Merge

※Changed suffix of models.  
_base → _sfw: _base was changed to _sfw.    
_night → _nsfw: Merged models up to NAI-NAI SFW were changed from _night to _nsfw.    
_half and non suffix → _hard: Gape merged models were given the suffix _hard.gape was reduced to 0.3 because it affects character modeling.  

▼How to choice models

- _sfw : SFW😉
- _nsfw : SFW ～ Soft NSFW🥰
- _hard : SFW ～ hard NSFW👄

▼Hash

- AbyssOrangeMix2_sfw.safetensors  
f75b19923f2a4a0e70f564476178eedd94e76e2c94f8fd8f80c548742b5b51b9  
- AbyssOrangeMix2_nsfw.safetensors  
0873291ac5419eaa7a18726e8841ce0f15f701ace29e0183c47efad2018900a4  
- AbyssOrangeMix_hard.safetensors  
0fc198c4908e98d7aae2a76bd78fa004e9c21cb0be7582e36008b4941169f18e  

▼Use Models

1. AnythingV3.0 huggingface pruned  
[2700c435]「543bcbc21294831c6245cd74c8a7707761e28812c690f946cb81fef930d54b5e」  
2. NovelAI animefull-final-pruned  
[925997e9]「89d59c3dde4c56c6d5c41da34cc55ce479d93b4007046980934b14db71bdb2a8」  
3. NovelAI sfw  
[1d4a34af]「22fa233c2dfd7748d534be603345cb9abf994a23244dfdfc1013f4f90322feca」  
4. Gape60  
[25396b85]「893cca5903ccd0519876f58f4bc188dd8fcc5beb8a69c1a3f1a5fe314bb573f5」  
5. BasilMix  
「bbf07e3a1c3482c138d096f7dcdb4581a2aa573b74a68ba0906c7b657942f1c2」  

### AbyssOrangeMix2_sfw

▼**Instructions:**

STEP: 1｜Block Merge

| Model: A | Model: B | Weight | Base alpha | Merge Name |
| --- | --- | --- | --- | --- |
| AnythingV3.0  | BasilMix | 1,0.9,0.7,0.5,0.3,0.1,1,1,1,1,1,1,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1 | 0 | AbyssOrangeMix2_sfw |

### AbyssOrangeMix2_nsfw

▼?

JUST AbyssOrangeMix2_sfw+ (NAI-NAISFW) 0.3.

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AbyssOrangeMix_base | NovelAI animefull | NovelAI sfw  | AbyssOrangeMix2_nsfw |

### AbyssOrangeMix2_hard

▼?
+Gape0.3 version AbyssOrangeMix2_nsfw.

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AbyssOrangeMix2_nsfw | Gape60 | NovelAI animefull | AbyssOrangeMix2_hard |

----


## EerieOrangeMix🍊

EerieOrangeMix is the generic name for a U-Net Blocks Weight Merge Models based on Elysium(Anime V2).  
Since there are infinite possibilities for U-Net Blocks Weight Merging, I plan to treat all Elysium-based models as a lineage of this model.

※This does not fundamentally improve the fingers, and I recommend using bad_prompt, etc. (Embedding) in combination.

<img src="https://files.catbox.moe/yjnqna.webp"  width="1000" height="" alt=”HeroImage_EerieOrangeMix_Designed_comp001” >


### EerieOrangeMix

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

▼ Sample Gallery  

<img src="https://files.catbox.moe/oqbvti.webp"  width="1000" height="" alt=”2022-12-30_MotorbikeGIrlAsa3_comp001”>
<details>
  <summary>More🖼</summary>
  <img src="https://files.catbox.moe/nmmswd.webp"  width="" height="600" alt=”2022-12-30_SampleGallery5”>
</details>

▼ How to use  


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

### EerieOrangeMix_base

▼?  
Details are omitted since it is the same as AbyssOrangeMix.

▼**Instructions:**

STEP: 1｜Creation of photorealistic model for Merge

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 1.0 | instagram-latest-plus-clip-v6e1_50000 | f222 | sd1.5_pruned | Insta_F222 |

STEP: 2｜Block Merge

Merge InstaF222

| Model: A | Model: B | Weight | Base alpha | Merge Name |
| --- | --- | --- | --- | --- |
| AnythingV3.0 | Insta_F222 | 1,0.9,0.7,0.5,0.3,0.1,0,0,0,0,0,0,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1 | 0 | Temp1 |

### EerieOrangeMix_Night

▼?

JUST EerieOrangeMix_base+ (NAI-NAISFW) 0.3.

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | EerieOrangeMix_base | NovelAI animefull | NovelAI sfw | EerieOrangeMix_Night |

### EerieOrangeMix_half

▼?
+Gape0.5 version EerieOrangeMix.

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.5 | EerieOrangeMix_Night | NovelAI animefull | NovelAI sfw | EerieOrangeMix_half |

### EerieOrangeMix

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 1.0 | EerieOrangeMix_Night | Gape60 | NovelAI animefull | EerieOrangeMix |

----

### 🍊EerieOrangeMix2

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

### EerieOrangeMix2_base

▼?

▼**Instructions:**

STEP: 1｜Block Merge

Merge ElysiumV1

The generated results do not change much with or without this process, but I wanted to incorporate Elysium's depiction, so I merged it.

| Model: A | Model: B | Weight | Base alpha | Merge Name |
| --- | --- | --- | --- | --- |
| EerieOrangeMix_base | ElysiumV1 | 1,0.9,0.7,0.5,0.3,0.1,0,0,0,0,0,0,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1 | 0 | EerieOrangeMix2_base |

### EerieOrangeMix_night

▼?

JUST EerieOrangeMix2_base+ (NAI-NAISFW) 0.3.

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | EerieOrangeMix_base | NovelAI animefull | NovelAI sfw | EerieOrangeMix2_Night |

### EerieOrangeMix_half

▼?
+Gape0.5 version EerieOrangeMix2.

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.5 | EerieOrangeMix_Night | NovelAI animefull | NovelAI sfw | EerieOrangeMix2_half |

### EerieOrangeMix

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 1.0 | EerieOrangeMix_Night | Gape60 | NovelAI animefull | EerieOrangeMix2 |


## Models Comparison

<img src="https://files.catbox.moe/mp2fr4.webp"  width="1000" height="" alt="MotorbikeGIrlAsa_Eerie_Abyss_Comparison_comp001">  
<img src="https://files.catbox.moe/9xqths.webp"  width="1000" height="" alt=”Eerie_Abyss_Comparison_02_comp001”> 
<img src="https://files.catbox.moe/cm6c7m.webp"  width="1000" height="" alt=”Eerie_Comparison_01_comp001”>  
※The difference is slight but probably looks like this.
← warm color, ↑ natural color, → animated color



----


## AbyssOrangeMix🍊

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



### AbyssOrangeMix_base

▼?

The basic trick for this merged model is to incorporate a model that has learned more than 1m Instagram photos (mostly Japanese) or a photorealistic model like f222. The choice of base model here depends on the person. I chose AnythingV3 for versatility.

▼**Instructions:**

STEP: 1｜Creation of photorealistic model for Merge

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 1.0 | instagram-latest-plus-clip-v6e1_50000 | f222 | sd1.5_pruned | Insta_F222 |

STEP: 2｜Block Merge

| Model: A | Model: B | Weight | Base alpha | Merge Name |
| --- | --- | --- | --- | --- |
| AnythingV3.0  | Insta_F222 | 1,0.9,0.7,0.5,0.3,0.1,0,0,0,0,0,0,0,0,0,0,0,0,0,0.1,0.3,0.5,0.7,0.9,1 | 0 | AbyssOrangeMix_base |

### AbyssOrangeMix_Night

▼?

JUST AbyssOrangeMix_base+ (NAI-NAISFW) 0.3.

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AbyssOrangeMix_base | NovelAI animefull | NovelAI sfw  | AbyssOrangeMix_Night |

### AbyssOrangeMix_half

▼?
+Gape0.5 version AbyssOrangeMix.

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.5 | AbyssOrangeMix_Night | Gape60 | NovelAI animefull | AbyssOrangeMix_half |

### AbyssOrangeMix

▼**Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 1.0 | AbyssOrangeMix_Night | Gape60 | NovelAI animefull | AbyssOrangeMix |


----




## ElyOrangeMix [6b508e59]｜Elysium_Anime_V2 + NAI + Gape

<img src="https://i.imgur.com/AInEXA5.jpg"  width="1000" height="">

▼?

This is a merge model that improves on the Elysium_Anime_V2, where NSFW representation is not good.
It can produce SFW, NSFW, and any other type of artwork, while retaining the Elysium's three-dimensional, thickly painted style.

▼ How to choice models

- _base : SFW😉
- _Night : SFW ～ Soft NSFW🥰
- _half : SFW ～ NSFW👄
- unlabeled : SFW ～ HARDCORE ～🤯  ex)AbyssOrangeMix, BloodOrangeMix...etc

▼Use Models

1. Elysium_Anime_V2 [6b508e59]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

### Instructions

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | Elysium_Anime_V2 | NovelAI animefull | NovelAI sfw  | tempmix-part1 [] |
| 2 | Add Difference @ 1.0 | tempmix-part1 | Gape60 | NovelAI animefull | ElyOrangeMix  [6b508e59] |

---

## ElyOrangeMix_half [6b508e59]

▼?

+Gape0.5 version ElyOrangeMix.

▼Use Models

1. Elysium_Anime_V2 [6b508e59]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

### Instructions

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | Elysium_Anime_V2 | NovelAI animefull | NovelAI sfw  | tempmix-part1 [] |
| 2 | Add Difference @ 0.5 | tempmix-part1 | Gape60 | NovelAI animefull | ElyOrangeMix_half  [6b508e59] |


----

## ElyNightOrangeMix[6b508e59]

▼?

It is a merged model that just did Elysium_Anime_V2+ (NAI-NAISFW) 0.3.

▼Use Models

1. Elysium_Anime_V2 [6b508e59]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]

### Instructions

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | Elysium_Anime_V2 | NovelAI animefull | NovelAI sfw  | ElyNightOrangeMix |

----

## BloodOrangeMix [ffa7b160]｜Anything+NAI+Gape

<img src="https://i.imgur.com/soAnnFk.jpg"  width="1000" height="">

▼?

This is a merge model that improves on the AnythingV3, where NSFW representation is not good.
It can produce SFW, NSFW, and any other type of artwork, while retaining the flat, beautifully painted style of AnythingV3.
Stable. Popular in the Japanese community.


▼ModelList & Hash(SHA256)  
- BloodNightOrangeMix.ckpt  
f8aff727ba3da0358815b1766ed232fd1ef9682ad165067cac76e576d19689e0
- BloodOrangeMix_half.ckpt  
b2168aaa59fa91229b8add21f140ac9271773fe88a387276f3f0c7d70f726a83
- BloodOrangeMix.ckpt  
25cece3fe303ea8e3ad40c3dca788406dbd921bcf3aa8e3d1c7c5ac81f208a4f

▼ How to choice models

- _base : SFW😉
- _Night : SFW ～ Soft NSFW🥰
- _half : SFW ～ NSFW👄
- unlabeled : SFW ～ HARDCORE ～🤯  ex)AbyssOrangeMix, BloodOrangeMix...etc

▼Use Models
1. AnythingV3.0 huggingface pruned [2700c435]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

### **Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AnythingV3.0 | NovelAI animefull | NovelAI sfw  | tempmix-part1 [] |
| 2 | Add Difference @ 1.0 | tempmix-part1 | Gape60 | NovelAI animefull | BloodOrangeMix [ffa7b160] |

----

## BloodOrangeMix_half [ffa7b160]｜Anything+Nai+Gape0.5

▼?

+Gape0.5 version BloodOrangeMix.
NSFW expression will be softer and have less impact on the Anything style painting style.

▼Use Models

1. AnythingV3.0 huggingface pruned [2700c435]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

### Instructions

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AnythingV3.0 | NovelAI animefull | NovelAI sfw  | tempmix-part1 [] |
| 2 | Add Difference @ 0.5 | tempmix-part1 | Gape60 | NovelAI animefull | BloodOrangeMix_half [ffa7b160] |

----


## BloodNightOrangeMix [ffa7b160]

▼?

It is a merged model that just did AnythingV3+ (NAI-NAISFW) 0.3.

▼Use Models

1. AnythingV3.0 huggingface pruned [2700c435]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]

### **Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AnythingV3.0 | NovelAI animefull | NovelAI sfw  | BloodNightOrangeMix |

----

## ElderOrangeMix [3a46a1e0] ｜anything and everything mix ver.1.5+Gape+Nai(AnEve.G.N0.3)

※I found this model to be very prone to body collapse. Not recommended.

▼?

This is a merged model with improved NSFW representation of anything and everything mix ver.1.5.

▼Use Models
1. anything and everything mix ver.1.5 [5265dcf6]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

### **Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.5 | anything and everything mix ver.1.5 | Gape60 | NovelAI full | tempmix-part1 [] |
| 2 | Add Difference @ 0.3 | tempmix-part1 | NovelAI full | NovelAI sfw | ElderOrangeMix  [3a46a1e0] |

----


## Troubleshooting

1. blurred Images & clearly low quality output  
If the generated images are blurred or only clearly low quality output is produced, it is possible that the vae, etc. are not loaded properly. Try reloading the model/vae or restarting the WebUI/OS.

## FAQ

<details>
  <summary>READ MORE</summary>

▼Nooo, Don’t work. This guy is Scammer  
STEP1: BUY HUGE PC  
Anon is working day and night on the minimum PC specs that GenerativeAI can run on. The following is a detailed list.    
https://seesaawiki.jp/nai_ch/d/%a5%ed%a1%bc%a5%ab%a5%eb%c9%f4%a1%a1PC%a5%b9%a5%da%a5%c3%a5%af%c1%ea%c3%cc%bc%bc

▼Noooo, can't generate image like samples.This models is hype.
<img src="https://files.catbox.moe/nte6ud.webp"  width="500" height="">
<img src="https://files.catbox.moe/lta462.webp"  width="500" height="">

▼Nooooo, This models have troy virus. don't download.  
All models in this repository are secure. It is most likely that anti-virus software has detected them erroneously.    
However, the models with the .ckpt extension have the potential danger of executing arbitrary code.    
A safe model that is free from these dangers is the model with the .safetensors extension.  

</details>

