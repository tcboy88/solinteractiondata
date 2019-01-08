# solinteractiondata
Dataset for Exploring Tangible Interactions with Radar Sensing published in the Journal Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies  Volume 2 Issue 4, December 2018 Article No. 200 https://dl.acm.org/citation.cfm?id=3287078

In Soli chip there are 2 Tx and 4 Rx antennas so in total there are 8 channels of raw radar signals, each channel has 64 data points. For simplicity, it is saved in one row of 512 inside a CSV file.The header is just a1-a64, then b1-b64 and so on indicating each channel. The last column is the class label.

Since this is the raw data without extra extracted features (in the paper we calculated extra features), the result might be slightly different from the paper, but it should be very small around 1%.

The easiest way it to use the Weka GUI. Weka can read CSV file directly but I recommend to convert to ARFF file first.

If you use the data please cite our paper, thanks.

Hui-Shyong Yeo, Ryosuke Minami, Kirill Rodriguez, George Shaker, and Aaron Quigley. 2018. Exploring Tangible Interactions with Radar Sensing. Proc. ACM Interact. Mob. Wearable Ubiquitous Technol. 2, 4, Article 200 (December 2018), 25 pages. DOI: https://doi.org/10.1145/3287078 

```
@article{Yeo:2018:ETI:3301777.3287078,
 author = {Yeo, Hui-Shyong and Minami, Ryosuke and Rodriguez, Kirill and Shaker, George and Quigley, Aaron},
 title = {Exploring Tangible Interactions with Radar Sensing},
 journal = {Proc. ACM Interact. Mob. Wearable Ubiquitous Technol.},
 issue_date = {December 2018},
 volume = {2},
 number = {4},
 month = dec,
 year = {2018},
 issn = {2474-9567},
 pages = {200:1--200:25},
 articleno = {200},
 numpages = {25},
 url = {http://doi.acm.org/10.1145/3287078},
 doi = {10.1145/3287078},
 acmid = {3287078},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {Context-Aware Interaction, Machine Learning, Radar Sensing, Soli, Tangible Interaction, Tangible User Interface, Token+Constraint, Ubiquitous Computing},
}
```