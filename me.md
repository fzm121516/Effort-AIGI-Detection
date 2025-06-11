cd DeepfakeBench/

CUDA_VISIBLE_DEVICES=6 python3 training/demo.py --detector_config training/config/detector/effort.yaml --weights /root/zgp2/fanzheming2/ArtGate/weights/effort_clip_L14_trainOn_sdv14.pth --image /root/zgp2/fanzheming2/testingset/genimage/test/adm/1_fake/0_adm_7.PNG