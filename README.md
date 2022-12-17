# stable-diffusion-TAiPET
Code used to fine-tune Stable Diffusion on wallpaper images. A project made during the Young Talent program at AI Sweden.

python main.py -t --base configs/stable-diffusion/low-lr1-5.yaml --gpus 1 --scale_lr False --num_nodes 1 --check_val_every_n_epoch 5 --finetune_from trainModel/v1-5-pruned.ckpt
