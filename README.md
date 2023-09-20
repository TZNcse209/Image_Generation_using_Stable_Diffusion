# Image_Generation_using_Stable_Diffusion

# Part 1: Stable Diffusion
  - Installing the libraries (xformers library to memory optimization)
  - Pipeline for image generation: Creating the prompt -> Generating the image -> Saving the result
  - Generating multiple images
  - Parameters: Seed, Inference steps, Guidance scale (CFG), Image size (dimensions), Negative prompt
  - Other models: SD v1.5, SD v2.x, Fine-tuned models with specific styles
  - Changing the scheduler: PNDM (default), DDIM Scheduler, K-LMS Scheduler, Euler Ancestral Discrete Scheduler (Euler A), DPM Scheduler
# Part 2: Prompt Engineering
  - Exploring the prompts: Subject / object, Action and location, Type, Style, Colors, Artist, Resolution, Site. And Other attributes: Ilumination, Negative prompts
  - Use cases: Generating arts, Generating photographs, Generating landscapes, Generating 3D images, Generating drawings, Generating architectures
  - Improving the results using custom models: Anything (cag/anything-v3-1), DreamShaper (Lykon/DreamShaper), Realistic Vision (SG161222/Realistic_Vision_V1.4), Analog Diffusion (wavymulder/Analog-Diffusion), Protogen (darkstorm2150/Protogen_x3.4_Official_Release), Mitsua Diffusion One (Mitsua/mitsua-diffusion-one)
# Part 3: Fine-tuning
  - Installing the libraries (accelerate transformers ftfy bitsandbytes==0.35.0 gradio natsort safetensors xformers)
  - Loading the model
  - Training: Three components are needed: unique identifier, class name, images
  - Convert the weights into (checkpoint)
  - Inference (tests)
  - Generating images: Testing multiple prompts, More prompt examples: in the forest, in cairo, in cairo desert, in a western scene, in star wars, in mountain fuji, in the snow, etc.
  - Saving the results
# Part 4: Image-to-image
  - Installing the libraries (accelerate transformers ftfy bitsandbytes==0.35.0 gradio natsort safetensors xformers)
  - Generating the image
  - Strength parameter (intensity)
  - Testing different styles
  - Changing the input image
  - Changing the scheduler
  - Image to image "editing" (InstructPix2pix)
# Part 5: Inpainting
  - Installing the libraries (accelerate transformers ftfy bitsandbytes==0.35.0 gradio natsort safetensors xformers)
  - Creating the prompt
  - Exchanging the objects
  - Comparing the results (Other image, Generating multiple images)
# Part 6: ControlNet
