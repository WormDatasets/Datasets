# Benchmark Datasets for Worm Propagation Studies
We generated two categories of datasets, each of which contains several sets of traffic traces. the simulated worms are Slammer, Code Red I, Code Red II, and modified versions of them. these datasets have been generated in two different networks with different background traffic. for more details on how we generated these datasets, worm parameters, infection network parameters, and so on, see [our](https://ijict.itrc.ac.ir/browse.php?a_id=451&slc_lang=en&sid=1&printcase=1&hbnr=1&hmb=1) [papers](https://ieeexplore.ieee.org/document/9345845).


This repo contains our generated datasets. each directory contains a traffic trace in pcap format as well as the worm propagation path. The mappings between hostnames and IPs are also available in IPs.txt files.

The source code of INET and ReaSE (modified versions) for generating additional datasets are available in [https://github.com/Sara-Asgari/Datasets](https://github.com/Sara-Asgari/Datasets)

## Citations
if you find our datasets or source code useful for your research, please cite our papers:<br />
```
@article{asgari2020simulating,
  title={Simulating Benchmark Datasets for Worm Propagation Studies},
  author={Asgari, Sara and Sadeghian, Babak},
  journal={International Journal of Information and Communication Technology Research},
  volume={12},
  number={1},
  pages={20--31},
  year={2020},
  publisher={International Journal of Information and Communication Technology Research}
}
```
```
@inproceedings{asgari2020towards,
  title={Towards Generating Benchmark Datasets for Worm Infection Studies},
  author={Asgari, Sara and Sadeghiyan, Babak},
  booktitle={2020 10th International Symposium on Telecommunications (IST)},
  year={2020},
  organization={IEEE}
}
```
## Contacts
if you have any question, please drop me an email.

s.asgari [at] aut.ac.ir
