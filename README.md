### What is CXRlabeler?
CXRlabeler is a deep learning labeler that takes raw radiology text as input and extracts 14 positive/negative CXR observations in its output. It utilizes the encoder learned from fine-tuning a language model on radiology reports in labeling these reports.
[[More Information]](https://doi.org/10.1007/978-3-030-86365-4_55) 


### Implementation:  
- Python: 3.7.8 
- Pytorch: 1.7.0
- fastai: 2.1.8
- GPU: 1 x NVIDIA Tesla V100 GPU
- Machine: n1- highmem-8 (8 vCPUs, 52 GB memory)
- Platform: Linux-4.19.0-12-cloud-amd64-x86_64-with-debian-10.6


### Citation:
Monshi, M.M.A., Poon, J., Chung, V. and Monshi, F.M., 2021. Labeling Chest X-Ray Reports Using Deep Learning. In International Conference on Artificial Neural Networks, 12893, p.684-694. [[Paper]](https://doi.org/10.1007/978-3-030-86365-4_55) 

### Contact: 
Maram Monshi at mmon4544@uni.sydney.edu.au or m.monshi@tu.edu.sa 
