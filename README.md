## train

python main.py --num_workers num_workers  --pretrain_model_path /path/to/file.pth --batch_size batch_size --coco_path /path/to/coco

(all args are not required)

## eval

python main.py --eval --pretrain_model_path /path/to/file.pth --options dn_scalar=100 embed_init_tgt=TRUE dn_label_coef=1.0 dn_bbox_coef=1.0 use_ema=False dn_box_noise_scale=1.0



[download pth](https://drive.google.com/drive/folders/1IreYtAhfq_pbN1AnWbsd-DNL7R2KUoWl?usp=drive_link)

## notes

models are saved to /outputs/checkpoint.pth

logs are saved to /outputs/loss.log