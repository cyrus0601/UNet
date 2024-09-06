# UNet
Medical Image Segmentation


## To avoid ToTensor compress the value 0~1, using PILToTensor.
```
mask_transform = transforms.Compose([
    transforms.PILToTensor(),
    transforms.Resize([800, 800], interpolation=Image.NEAREST),
])
```


![image](https://github.com/user-attachments/assets/e872eae0-72d9-4b07-b9d4-c41a651743c7)
