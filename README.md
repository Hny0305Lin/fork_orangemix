---
license: cc0-1.0
tags:
  - stable-diffusion
  - text-to-image
---
# This repo is.
This repository shares various Merge models that can be used with StableDiffusionWebui:Automatic1111 and others.

Maintain a repository for the following purposes.
1. to provide easy access to models commonly used in the Japanese community. Model names are named after Cookbook precedents.
2. As a place to upload my merge models when I feel like it.

<img src="https://i.imgur.com/VZg0LqQ.png"  width="1000" height="">


# Reference
+/hdg/ Stable Diffusion Models Cookbook - https://rentry.org/hdgrecipes#g-anons-unnamed-mix-e93c3bf7

# Disclaimer
You have complete control over whether or not to generate NSFW content, and you do so at your own will.
The posting of learning models is not intended to display obscene material.

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

# Merge Recipes


## ElyOrangeMix [6b508e59]

<img src="https://i.imgur.com/AInEXA5.jpg"  width="800" height="">

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

## BloodOrangeMix [ffa7b160]｜Anything+Nai+Gape

<img src="https://i.imgur.com/soAnnFk.jpg"  width="800" height="">

▼?

This is a merge model that improves on the AnythingV3, where NSFW representation is not good.

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

