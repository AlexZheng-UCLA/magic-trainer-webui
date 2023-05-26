# Magic Trainer Webui

This extension aim for training **Lora** and **Dreambooth**(upcoming) inside **stable-diffusion-webui**. "Magic" Recipes are embedded in the training code so that even newbies can train a good model easily.
![](/screenshots/lora trainer.png)
![](/screenshots/data preparation.png)
## Features 

- Solve the original environment conflict with stable-diffusion-webui. 
    Now the dependency can be easily ensured without breaking the webui venv
- Hide some trivial arguments to render a more simple UI. 
    This lower the barrier to user especially for amateurs. For checking the default value of the hidden features, see [Lora.py]() and [Prepare.py](https://github.com/AUTOMATIC1111/stable-diffusion-webui).py under kohya_ss_revised
- More useful dataset preparation. 
    Besides the most common tool "blip" and "wd tagger", we add "both" option that add the tags generated by "wd tagger" behind the caption generated by "blip". We also add arguments "tags to add to front", "tags to replace" for automatical tag editing.
- Add a terminal tab that copy the teminal output. This feature free you from switching between the web page and the terminal. 
- A tutorial that tells the mearning of some confusing arguments.  

## Install
as an extension of stable-diffusion-webui, you can install by **one** way below:

- Go to `Extensions` > `Install from URL`, enter the following URL and press the install button.
  https://github.com/AlexZheng-UCLA/magic-trainer-webui.git

- Go inside the `extensions folder` in `stable-diffusion-webui` and clone the repo

  ```bash
  cd /path/to/stable-diffusion-webui
  git clone https://github.com/AlexZheng-UCLA/magic-trainer-webui.git
  ```

- Download the source code and move the unzipped folder to the `extensions` folder 



