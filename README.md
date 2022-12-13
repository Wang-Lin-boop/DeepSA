# DeepSA: A novel Prediction of Compound Synthesis Accessibility Based on Deep Learning

## Requirements

- Python == 3.X.X
- tensorflow-gpu == 1.14.0
- scikit-learn == 0.24.0
- pandas ==  1.1.5
- numpy == 1.19.5
- matplotlib == 3.3.4


Dependencies can be installed using the following command:
```bash
conda create -n DeepSA python=3.X.X
conda activate DeepSA

pip install -r requirements.txt
```
- CUDA == 10.0 (This is just a suggestion to make sure your program works properly)
- how to install CUDA and cuDNN:
```
conda install cudatoolkit=10.0   
conda install cudnn=7.6.5
```

## Usage For Researchers

You can run it from the command line

running:
```
    cd ./DeepSA
    python DeepSA.py
```

## Online Server

We deployed a pre-trained model on a dedicated server, which is publicly available at https://bailab.siais.shanghaitech.edu.cn/deepsa, to make it easy for biomedical researcher users to utilize DeepSA in their research activity. 

Users can upload their SMILES or csv files to the server, and then they can quickly obtain the predicted results.

## <span id="citelink">Citation</span>
If you find this repository useful in your research, please consider citing the Github:<br/>
https://github.com/Shihang-Wang-58/DeepSA<br/>

Papers involving DeepSA have been submitted to an academic journal.

## Contact
If you have any questions, please feel free to contact Shihang Wang (Email: wangshh12022@shanghaitech.edu.cn) or Lin Wang (Email: wanglin3@shanghaitech.edu.cn). 

Pull requests are highly welcomed!

## Acknowledgments
We are grateful for the support from HPC Platform of ShanghaiTech University.<br/>
Thank you all for your attention to this work.

