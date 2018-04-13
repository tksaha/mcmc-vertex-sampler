
# Vertex Sampler (MCMC)

## Installation
```
clean: make clean
compile: make
``


Please convert the input file into intended format: 
Format:

```
vertex_id_1 vertex_id_2  vertex_1_label edge_label vertex_2_label
```


For using our code, vertex label has to start from 1 and end at the maximum vertex id. 

A converter (python file) is provided under undir_data directory. 


## Reference
If you are using the code for research purposes, please consider citing any of the following paper:

```
@article{saha.hasan:15,
  title={FS3: A sampling based method for top-k frequent subgraph mining},
  author={Saha, Tanay Kumar and Al Hasan, Mohammad},
  journal={Statistical Analysis and Data Mining: The ASA Data Science Journal},
  volume={8},
  number={4},
  pages={245--261},
  year={2015},
  publisher={Wiley Online Library}
}

@inproceedings{saha.hasan:15*2,
  title={Finding Network Motifs Using MCMC Sampling.},
  author={Saha, Tanay Kumar and Al Hasan, Mohammad},
  booktitle={CompleNet},
  pages={13--24},
  year={2015}
}
```