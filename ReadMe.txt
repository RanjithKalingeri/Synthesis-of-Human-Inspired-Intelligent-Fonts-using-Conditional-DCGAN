
After downloading 'intelligent_font_files' folder upload it in your drive, 
the path of uploaded folder should be '/MyDrive/intelligent_font_files'. 

1. Trained I-cDCGAN, R-cDCGAN and FID_feature_extractor models saved in folder 'all_trained models'. 

2. In 'code_files' folder : 
   2.1 code for developing, training, demo, and fid calculations of I-cDCGAN is complied and stored 
       in 'icdcgan_all.ipynb' file. 
   2.2 code for developing, training, demo, and fid calculations of R-cDCGAN is complied and stored 
       in 'rcdcgan_all.ipynb' file.
   2.3 code for extracting data from TXT file and its corresponding handwriting PNG image is complied and stored 
       in 'intelligentFontDataPreproccessingipynb.ipynb' file.
   2.4 code for sentence formation using real data is complied and stored 
       in 'Real_Data_Sentence_Formation.ipynb' file.
You need not to change any file path in above code files, you just need to upload 'intelligent_font_files' in your 
drive, the path of uploaded folder should be '/MyDrive/intelligent_font_files'. 


3. In CSV_files folder there are two files:
   3.1 'mygdatasheet12.csv' file is the dataset used for training purpose.
   3.2 'mygdatasheet12_ordered_data.csv' file is dataset used for sentence formation. 
Note: 'mygdatasheet12.csv' is just oversampled and shuffled version of  extracted csv file 'mygdatasheet12_ordered_data.csv'. 

4. In 'PNG +TXT_files' folder 12 TXT files and their corresponding Handwritten PNG images are stored in their 12 respective 
   folders. 

5. all FID, BCFID and WCFID results can be found in 'fid_results' folder.  

