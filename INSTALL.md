# Install steps taken

```
conda create --name DGSDRP python=3.8

conda activate DGSDRP

conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia

conda install pyg -c pyg

conda install matplotlib pandas numpy scipy h5py

conda install rdkit -c conda-forge

conda install pubchempy -c mcs07

( cd data ; unzip -j data.zip )
```



