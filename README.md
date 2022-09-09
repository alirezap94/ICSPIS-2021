# ICSPIS-2021
>📋  This is a readme file for the implementation of paper “A Joint-Entropy Approach To Time-series Classification” published in “7th International Conference on Signal Processing and Intelligent Systems (ICSPIS)”. 

For more information, please refer to:  
K. Safarihamid, A. Pourafzal and A. Fereidunian, "A Joint-Entropy Approach To Time-series Classification," 2021 7th International Conference on Signal Processing and Intelligent Systems (ICSPIS), 2021, pp. 1-7, doi: 10.1109/ICSPIS54653.2021.9729371.
https://ieeexplore.ieee.org/document/9729371
https://www.researchgate.net/publication/359182900_A_Joint-Entropy_Approach_To_Time-series_Classification


## Requirements

The script is written in python Language. 
The required libraries are numpy, matplotlib, pandas, itertools, scipy for dataset generation and feature extraction.
Moreover, for classification sklearn and mlxtend are utilized. 

## File Order in the Repository 

The files in the repository are in the following order: 
1- “Generating_Time_Series” and “Calculating_Entropies” are for generating the time series and extracting entropies, respectively. 
To provide an easier validation for the respected readers, the final values of these time-consuming processes are stored in the “Dataset” directory. 

2- “Time_series_Visual_Inspection” and “Box_Plots” are included for visualization of time series and extracted features, respectively. 
In fact, for the later we can observe how much separability each entropy provides.

3- “3D_ESC_Plots” and “Classification” demonstrate the significant improvement that the proposed method achieves. 
Supported by classification metric and visual inspection, one can confirm that joint-entropy approach surpasses other entropy classifiers. 


## Contributing

You can use and modify this work by citing the original paper
@inproceedings{safarihamid2021joint,
  title={A Joint-Entropy Approach To Time-series Classification},
  author={Safarihamid, Kimia and Pourafzal, Alireza and Fereidunian, Alireza},
  booktitle={2021 7th International Conference on Signal Processing and Intelligent Systems (ICSPIS)},
  pages={1--7},
  year={2021},
  organization={IEEE}
} 
