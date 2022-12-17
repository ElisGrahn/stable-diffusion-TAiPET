# stable-diffusion-TAiPET
Code used to fine-tune Stable Diffusion on wallpaper images. A project made during the Young Talent program at AI Sweden.

The complete guide that we followed: https://lambdalabs.com/blog/how-to-fine-tune-stable-diffusion-how-we-made-the-text-to-pokemon-model-at-lambda

The command we used to initiate training: python main.py -t --base configs/stable-diffusion/low-lr1-5.yaml --gpus 1 --scale_lr False --num_nodes 1 --check_val_every_n_epoch 5 --finetune_from trainModel/v1-5-pruned.ckpt

Example images:

![test5](https://user-images.githubusercontent.com/75640839/208248504-7fb53752-8071-493c-acfe-f97725e4b7fc.png)![test7](https://user-images.githubusercontent.com/75640839/208248571-8b55718b-7599-46c3-9288-940e5c687011.png)
![test8](https://user-images.githubusercontent.com/75640839/208248575-9cdfb9ba-e387-42da-a52f-d8ef78f8a9d1.png)
![test3](https://user-images.githubusercontent.com/75640839/208248582-6a51f096-a0c1-4c05-bf79-fa3c6baee237.png)
![test6](https://user-images.githubusercontent.com/75640839/208248584-df951db4-f9e6-40eb-94b4-d0da115774cd.png)
![test2](https://user-images.githubusercontent.com/75640839/208248588-f15d948b-16c6-49f5-bb49-c78bc4161459.png)
