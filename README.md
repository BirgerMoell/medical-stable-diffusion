# medical-stable-diffusion
Medical stable diffusion.

1. Collect data. I think starting out with this chest-xray-dataset makes sense since it's freely available on the hub.
https://huggingface.co/datasets/alkzar90/NIH-Chest-X-ray-dataset
2. Performing segmentation masks on the chest xrays using SEM model.
3. Extract information about relevant anatomy based on the SEM model results and include that with the label and hopefully combine that with a LLM to create a text description that would be similar to a radiology assessment.
4. Train the stable diffusion / controlnet model on the description and images.


## List of medical datasets

https://docs.google.com/spreadsheets/d/1zU3qbGpqbRySeyn7jJarPxdLBPH33Jzw4U0u-49nf0U/edit?usp=sharing


## How to access TPUs
https://github.com/huggingface/community-events/tree/main/jax-controlnet-sprint#setting-up-your-tpu-vm


## Information on how to use our 3 terrabyte drive
https://cloud.google.com/tpu/docs/setup-persistent-disk#mount-pd
