# MSML640Project
This paper aims to address the ability of Neural networks in extracting geological and environmental information in computer visions. The goal is to build a multi-classes classifier that could predict the location from a set of pictures which are similar to a game named Geoguessr. This classifier would attempt to deduce which states from the United States the input images are taken from. 
The dataset 50States10k is collected from Google Street view in United States across 50 states, each state containing 10000 images forming a cumulative 0.5 million images dataset. Each street view contains 4 images from north to west in the format (year_prefix_deg.jpg), forming 2500 data samples for each label.
Steps to recreate:
1.Upload John_Wong_640Project.ipynb into Google Colab and the zip file into Google Drive. 
2. For the test folder which contain 8 jpegs, you can upload it inside the colab after create a folder named new_images(or other name but you need to change the name in test_root parameter).
3. Training: Run the whole file by its order until any block under the line "Model Loading"
4. Pretrained: Upload the pth file in the directory. Run the file in order until the block under "Testing", then go to Model Loading part and run the bottom block to load the model. Test the performance of the model by runing code under the testing part and visualization part.
5. Dataset spliting: To adjust the training and testing data size, adjust the n parameter on the block over "model setup and training".
Requirement.txt: while I add the requirement txt here, there is already a line of code of installation of package needed in the ipynb file.
