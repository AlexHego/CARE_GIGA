# CARE_GIGA
# CARE : Content-Aware Image Restoration

<img src="https://github.com/AlexHego/CARE_GIGA/blob/main/ressource/CARE%20planaria%20RAW.gif%20resampled.gif" width="300" title="care" alt="care" align="left" vspace = "50">
<img src="https://github.com/AlexHego/CARE_GIGA/blob/main/ressource/CARE%20planaria%20prediction.gif" width="300" title="care" alt="care" align="center" vspace = "50">

(example of result from CSBDeep plugin)



## Step-by-step tutorial
#### 1. Acquire data with low SNR and high SNR of the exact same scene 
#### 2. Create a folder and subfolder as below
1. model
2. train_data
    1. ground_truth
         1. 001.tif
         2. 002.tif
         3. 003.tif
         ....
     1. noisy
         1. 001.tif
         2. 002.tif
         3. 003.tif
         ....

#### 3. Download script 
[CARE script](https://github.com/AlexHego/CARE_GIGA/blob/main/Script/CARE_script_3D.ipynb)

#### 4. Start CARE with conda
1. Activate miniconda3
2. conda activate cellpose
3. jupyter notebook
4. open CARE_script_3D.ipynb 
5. run it


#### 5. Batch prediction with fiji
1. Download the script in Jython [CARE_prediction](https://github.com/AlexHego/CARE_GIGA/blob/main/Script/CARE_prediction_script_3D.py)
</br> (credit : Deborah Schmidt, frauzufall, https://github.com/CSBDeep/CSBDeep_fiji/blob/master/script/CARE_generic.py)
2. download [imageJ/Fiji](https://imagej.net/software/fiji/downloads)
3. Update ImageJ/Fiji > `Help` > `Update...`
4. Restart ImageJ
5. Drag and drop the script and run it 



## Citation:

[Content-Aware Image Restoration: Pushing the Limits of Fluorescence Microscopy](https://www.nature.com/articles/s41592-018-0216-7). Martin Weigert, Uwe Schmidt, Tobias Boothe, Andreas Müller, Alexandr Dibrov, Akanksha Jain, Benjamin Wilhelm, Deborah Schmidt, Coleman Broaddus, Siân Culley, Mauricio Rocha-Martins, Fabián Segovia-Miranda, Caren Norden, Ricardo Henriques, Marino Zerial, Michele Solimena, Jochen Rink, Pavel Tomancak, Loic Royer, Florian Jug, and Eugene W. Myers. Nature Methods 15.12 (2018): 1090–1097.

## More infos:
Please see the documentation at http://csbdeep.bioimagecomputing.com/doc/
