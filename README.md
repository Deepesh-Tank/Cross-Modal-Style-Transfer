Cross-Modal-Style-Transfer
This project is based on a field of deep learning that is "NEURAL STYLE TRANSFER".The standard neural style transfer takes a content image and style image and transfer style from style image to content image.
Project/Research in such field include variation in the method used in style tranfer.Our project idea is based on paper "cross modal style tranfer" Sahil Chelaramani,Abhishek Jha,Anoop Namboodiri iiit hyderabad but working is different and efficient than the mentioned paper.We try to add more feature and reduces the working complexity of the research paper.
Here we takes only content image with the text embedded in it.text describe how the content image should stylize.We just need a database of  style-text captioned images for this purpose.
Advantage over standard NST.
1) We eliminate the need of giving style image to the program as the text automatically select the resembling style images from the database.
2) The standard NST works with single style image, while our program deals transfer style for multiple style images that are retrieved from the database resemble content image text this ensure better output image.
How our project is different/Better from/than mentioned paper
1) Our method gives the best result as we used pretrained pytesseract model ensuring accuracy of 98 – 99 % which greater than purposed word2vec model of original paper.
2) Pytesseract based on retrieving letter from image than forming word therefore identifying out of vocabulary words while word2vec can’t identify such words
3) We don't use primtive gradient decent that is used in mentioned paper instead we use algorithm fmin_l_bfgs_b. 
4) We use an additional loss factor i.e. total variation loss that was not in mentioned paper.


The folder IMPLEMENTED_PAPER Contains CODE.pynb file along with used database images and content images.

For more detailed analysis and working of project view the CODE_ANALYIS_WORKING_RESULTS.pptx

At last I want to thank my project superviser Dr Tanima Dutta for providing me opportunity to implement the project.
