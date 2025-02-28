### Run TPU
!pip uninstall -y torch torch_xla torchvision timm numpy pillow
!pip install torch==2.1.0 torch_xla[tpu]==2.1.0 torchvision==0.16.0 timm==0.9.2 numpy==1.26.4 pillow -f https://storage.googleapis.com/libtpu-releases/index.html
