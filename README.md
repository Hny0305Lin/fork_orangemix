---
license: cc0-1.0
tags:
  - stable-diffusion
  - text-to-image
---
# This repo is.
This repository shares various Merge models that can be used with StableDiffusionWebui:Automatic1111 and others.

Maintain a repository for the following purposes.
1. to provide easy access to models commonly used in the Japanese community. 
2. As a place to upload my merge models when I feel like it.

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
2. create a folder of your choice and type "cmd" in the directory field → Enter → open a command prompt to the folder's directory.
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

# Model Detail & Merge Recipes




## AbyssOrangeMix

――How can you guys take on such a deep swamp and get results?  
Is it something like "Made in Abyss"?  
By Anon, 115th thread

<img src="https://files.catbox.moe/wst1bp.webp"  width="1000" height="">


▼?

The merged model was formulated using an extension such as sdweb-merge-block-weighted-gui, which merges models at separate rates for each of the 25 U-Net blocks (input, intermediate, and output).
The validation of many Anons has shown that such a recipe can generate a painting style that is anatomically realistic enough to feel the finger skeleton, but still maintains an anime-style face.

※This model is the result of a great deal of testing and experimentation by many Anons🤗
※This model can be very difficult to handle. I am not 100% confident in my ability to use this model. It is peaky and for experts.


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

- Prompts can be long or short
- Sampler: “DPM++ SDE Karras” is good
- Steps: forTest: 20～24 ,illustration: 24～50
- Clipskip: 1
- USE “upscale latent space”
- Denoise strength: 0.45 (0.4~0.5)
If you use 0.7～, the picture will change too much.


🗒Model List

- AbyssOrangeMix_base｜Instagram Merge
    - AbyssOrangeMix_Night｜+ NAI-NAISFW Merge
        - AbyssOrangeMix_half｜+ Gape0.5 Merge
        - AbyssOrangeMix｜+ Gape1.0 Merge


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
I actually tested it and found that it was possible to output NSFW content while retaining Elysium's three-dimensional, thickly painted style.

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

