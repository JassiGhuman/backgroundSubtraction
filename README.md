# background Matting
MM805 project
Our matting network generate trimaps automatically. First we uses pretrained semantic segmentation model to predict trimaps without human intervention and then, the trimap along with RGb image are fed into the matting network to produce alpha matting. 
- Install the packages using pip install requirements.txt.
- Please use the pretrained model FBA.pth in the models file for testing.
- Run this command generate_trimaps.py -i image_path --target_class person to generate trimap , please give the image path and target file by giving argumennts -i and --target_class accordingly.
- After successful run, the trimap will be stored in image_path/trimaps.
- Please run the demo.py file to get the predictions, the results will be stored in image_path/predictions folder.
