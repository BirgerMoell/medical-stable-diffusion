# medical-stable-diffusion
Medical stable diffusion.

1. Collect data. I think starting out with this chest-xray-dataset makes sense since it's freely available on the hub.
https://huggingface.co/datasets/alkzar90/NIH-Chest-X-ray-dataset
2. Performing segmentation masks on the chest xrays using SEM model.
3. Extract information about relevant anatomy based on the SEM model results and include that with the label and hopefully combine that with a LLM to create a text description that would be similar to a radiology assessment.
4. Train the stable diffusion / controlnet model on the description and images.
