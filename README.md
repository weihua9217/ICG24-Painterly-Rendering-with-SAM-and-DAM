# ICG Final Project
- Requirements

```
pip install -r requirements.txt
```

- Weight of SAM

   - please download pretrain weight, and place in 'weights' folder: 
   - https://github.com/facebookresearch/segment-anything?tab=readme-ov-file#model-checkpoints



- Run draw_layers.ipynb to render oil painting style of image

   - put your image under 'images' folder

   - change the image_name in draw_layers.ipynb


### Input Image & Output of DAM
![Input](./images/tomato.png) 
![DAM](depth_tomato.png) 

### Output of SAM & Output of our Algorithm
![SAM](sam_tomato.png)
![Render](canvas_tomato.png) 