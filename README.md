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
2. Upload models that I have personally merged with my own in my mood!

<img src="https://i.imgur.com/PRHjwT3.jpg"  width="600" height="">


## Reference
+/hdg/ Stable Diffusion Models Cookbook - https://rentry.org/hdgrecipes#g-anons-unnamed-mix-e93c3bf7

# Merge Recipes

## BloodOrangeMix [ffa7b160]｜Anything+Nai+Gape

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

### **Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AnythingV3.0 | NovelAI animefull | NovelAI sfw  | tempmix-part1 [] |
| 2 | Add Difference @ 0.5 | tempmix-part1 | Gape60 | NovelAI animefull | BloodOrangeMix_half [ffa7b160] |

----

## NightOrangeMix [ffa7b160]

▼?

AnythingV3+(NAI-NAISFW)0.3. That's it.

▼Use Models

1. AnythingV3.0 huggingface pruned [2700c435]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]

### **Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AnythingV3.0 | NovelAI animefull | NovelAI sfw  | NightOrangeMix |

----

## ElderOrangeMix [3a46a1e0] ｜anything and everything mix ver.1.5+Gape+Nai(AnEve.G.N0.3)

▼?

NSFW improved merge model based on anything and everything mix ver.1.5

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

