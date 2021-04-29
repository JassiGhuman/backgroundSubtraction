# background Matting
MM805 project
- Install the packages using pip install requirements.txt.
- Please use the pretrained model FBA.pth in the models file for testing.
- Run generate_trimaps.py -i image_path --target_class person file to generate trimap , please give the image path and target file by giving argumennts -i and --target_class accordingly.
- After successful run, the trimap will be stored in image_path/trimaps.
- Please run the demo.py file to get the predictions, the results will be stored in image_path/predictions folder.
- 
