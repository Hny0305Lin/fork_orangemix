# Model Helth Check

According to the author of the U-Net Blocks Weight Merge extension, there are cases of model corruption in merged models. The results of a health check carried out using a script to repair problems with corrupted merged models🕵️‍♀️  
Reference：[調査] Smile Test: Elysium_Anime_V3 問題を調べる #3｜bbcmc｜note - https://note.com/bbcmc/n/n12c05bf109cc

## 🩺Models Helth Check List🩺




 - AbyssOrangeMixs2
    
    ✅
    python fix_position_ids.py --model C:\ProgramTools\__GenerativeAI\StableDiffusion_AUTOMATIC1111_v6.0\stable-diffusion-webui\models\Stable-diffusion\AbyssOrangeMix2_hard.safetensors
    
    ```jsx
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True]])
    ```
    
    ✅
    python fix_position_ids.py --model C:\ProgramTools\__GenerativeAI\StableDiffusion_AUTOMATIC1111_v6.0\stable-diffusion-webui\models\Stable-diffusion\AbyssOrangeMix2_nsfw.safetensors
    
    ```jsx
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True]])
    ```
    
    ✅
    python fix_position_ids.py --model C:\ProgramTools\__GenerativeAI\StableDiffusion_AUTOMATIC1111_v6.0\stable-diffusion-webui\models\Stable-diffusion\AbyssOrangeMix2_sfw.safetensors
    
    ```jsx
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True]])
    ```
    
- AbyssOrangeMix
    
    
    ✅
    
    python fix_position_ids.py --model H:\Resources\Resources_AI\__Models\MergeModels\OrangeMixs\AbyssOrangeMix\AbyssOrangeMix.safetensors
    
    ```
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True]])
    ```
    
    python fix_position_ids.py --model H:\Resources\Resources_AI\__Models\MergeModels\OrangeMixs\AbyssOrangeMix\AbyssOrangeMix_night.safetensors
    
    ```
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True]])
    ```
    
    python fix_position_ids.py --model H:\Resources\Resources_AI\__Models\MergeModels\OrangeMixs\AbyssOrangeMix\AbyssOrangeMix_half.safetensors
    
    ```
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True]])
    ```
    
    python fix_position_ids.py --model H:\Resources\Resources_AI\__Models\MergeModels\OrangeMixs\AbyssOrangeMix\AbyssOrangeMix_base.ckpt
    
    ```
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True]])
    ```


- AnythingV3
    
    ✅
    ```jsx
    python fix_position_ids.py --model C:\ProgramTools\__GenerativeAI\StableDiffusion_AUTOMATIC1111_v6.0\stable-diffusion-webui\models\Stable-diffusion\An_V3_Pr.ckpt
    ```
    
    ```jsx
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True]])
    ```
    
- NAI
    
    ✅
    python fix_position_ids.py --model C:\ProgramTools\__GenerativeAI\StableDiffusion_AUTOMATIC1111_v6.0\stable-diffusion-webui\models\Stable-diffusion\nai.safetensors
    
    ```jsx
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True, True, True, True, True, True, True, True,
    True, True, True, True, True]])
    ```
    
    ✅
    python fix_position_ids.py --model C:\ProgramTools\__GenerativeAI\StableDiffusion_AUTOMATIC1111_v6.0\stable-diffusion-webui\models\Stable-diffusion\nai_sfw.safetensors
    
    ```jsx
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True]])
    ```
    
- gape
    
    ✅
    
    python fix_position_ids.py --model "C:\ProgramTools\__GenerativeAI\StableDiffusion_AUTOMATIC1111_v6.0\stable-diffusion-webui\models\Stable-diffusion\gape60.ckpt”
    
    ```jsx
    tensor([[True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True, True, True, True, True, True, True, True,
             True, True, True, True, True]])
    ```
    

- EerieOrangeMix
    
    ```
    ⚠ All model 1 False  
    1 False

    tensor([[ True,  True,  True,  True,  True,  True,  True,  True,  True,  True,
    True,  True,  True,  True,  True,  True,  True,  True,  True,  True,
    True,  True,  True,  True,  True,  True,  True,  True,  True,  True,
    True,  True,  True,  True,  True,  True,  True,  True,  True,  True,
    True, False,  True,  True,  True,  True,  True,  True,  True,  True,
    True,  True,  True,  True,  True,  True,  True,  True,  True,  True,
    True,  True,  True,  True,  True,  True,  True,  True,  True,  True,
    True,  True,  True,  True,  True,  True,  True]])
    corrupt token indexes : [41]
    missing token numbers : [41]
    ```

&nbsp;
&nbsp;
&nbsp;
&nbsp;