# sd-portraits (Stable Diffusion Portraits)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sharkf1n/sd-portraits/blob/master/portrait_diffusion.ipynb
)

#### what?
A colab notebook for creating 4:5 portraits with Stable Diffusion.
- see notebook `portrait_diffusion.ipynb` 
- other notebooks are experiments preceding the construction of `portrait_diffusion.ipynb` 

#### why?
- Prompts like `"A portrait of..."` work best close to 512x512 resolution with Stable Diffusion
- But we want higher resolution images at a 4:5 aspect ratio

#### how?
- Good prompt engineering
- Upscale/clean-up using GFPGAN 
