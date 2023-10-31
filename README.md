# AIWD6-dataset
## Dataset for capturing continuous weather scenarios
<img src="images/m2smart.png" width="200"> <img src="images/iith.png" width="100">

We introduce a large-scale comprehensive dataset known as the Adverse Intermediate Weather Driving (AIWD6) dataset. This dataset comprises six transitional weather states designed for autonomous driving scenarios: \textit{cloudy to rainy, rainy to cloudy, sunny to rainy, rainy to sunny, sunny to foggy, and foggy to sunny}. These transitional states are generated at various temporal scales. Further, we propose an approach to classify the transitional weather images using a gated recurrent unit (GRU). We anticipate that our dataset with realistic continuous weather shifts will shape the data collection paradigm for real-world driving datasets and advance scene perception techniques for AVs. Additionally, the spatio-temporal CNN-GRU followed by an attention mechanism could effectively classify the weather transition data even for larger sequences. In future, we would like to improve the quality of generated data, anticipate the weather transition state, and perform segmentation on the AIWD6 dataset.

**Paldi (P)**         | **Nehru Bridge Ashram Road (N)**       
----------------|--------------
![](images/paldi.png) |![](images/nehru.png)
4-way signalized intersection | 4-way signalized intersection 
**APMC market (A)**
![](images/apmc.png)
3-way unsignalized intersection


<h2> Spatio - Temporal Annotations </h2>

Spatial regions of traffic states for the above intersections are manually annotated as shown below <br>

**Red: Clump, Yellow: Neutral, Blue: Unclump**

**Paldi (P)**         | **Nehru Bridge Ashram Road (N)**       
----------------|--------------
![](images/paldi.jpg) |![](images/nehru.jpg)
4-way signalized intersection | 4-way signalized intersection 
**APMC market (A)**
![](images/apmc.jpg)
3-way unsignalized intersection



Spatial annotations can be downloaded here:[Paldi](https://drive.google.com/file/d/1QwkxbhTl25x9F1sOD8iH3Hy-yMmqYXD2/view?usp=sharing), [Nehru](https://drive.google.com/file/d/1x7GMiAUyp47DPDXtt5KoRqhoKFk_bYTI/view?usp=sharing), [APMC](https://drive.google.com/file/d/1XXFk2RGhHDkUfyARKSZe-mhEuAmDFEqb/view?usp=sharing)

Temporal annotations and corresponding videos can be downloaded using the below table

Paldi|| Nehru|| APMC||
-|-|-|-|-|-|
Video|Annotation| Video|Annotation| Video|Annotation| 
[1_1.mp4](https://drive.google.com/file/d/1W6fGg_k83EBXf_gfJyxJJNoz76WcRrpS/view?usp=sharing)|[Paldi_1_1.csv](https://drive.google.com/file/d/17F6drdN36469GVZnt2-KGSC6vWh-Kib2/view?usp=sharing)| [3_1.mp4](https://drive.google.com/file/d/1-mKo8MC68oEtVh201TnswEHKZjfREY6v/view?usp=sharing)|[Nehru_3_1.csv](https://drive.google.com/file/d/1EwNsix-gCpOsAJa5wpNBmcXXClQujWCi/view?usp=sharing)| [4_1.mp4](https://drive.google.com/file/d/1MK8JZmXJLnBVKFBd8OU_HZPh_wlKESK7/view?usp=sharing)|[APMC_4_1.csv](https://drive.google.com/file/d/1VW2QIqhIr7Vq0SN0q9P8mCWLCo_D_y8s/view?usp=sharing)| 
[1_2.mp4](https://drive.google.com/file/d/1BVz7Kh4gCrUQxfK9G7IlhDJVcSOUTgKr/view?usp=sharing)|[Paldi_1_1.csv](https://drive.google.com/file/d/1GWdL7dBEvi-G2UD_HoE_oC5rH1cSB7Ts/view?usp=sharing)| [3_2.mp4](https://drive.google.com/file/d/1PPJidGwy0oe8Zu2Ccd8ErQjzW8_So-wC/view?usp=sharing)|[Nehru_3_2.csv](https://drive.google.com/file/d/17vbPp-rlAh49LeYEoT6GQEzOcw-V8JD9/view?usp=sharing)| [4_2.mp4](https://drive.google.com/file/d/1oBdYcbuO4cM16KXHd5cluy3XbuENDEpV/view?usp=sharing)|[APMC_4_2.csv](https://drive.google.com/file/d/1e-zU9bFTDHckBDrESk9TTlPZcj5Sd5ee/view?usp=sharing)| 
[1_3.mp4](https://drive.google.com/file/d/1ReLqI7zfQru7RnVNbxofU9XnV1yuEKt8/view?usp=sharing)|[Paldi_1_1.csv](https://drive.google.com/file/d/1lCYJ3Tu214TPZjyu6cyqDsPVMjK5QnhK/view?usp=sharing)| [3_3.mp4](https://drive.google.com/file/d/191CdrD223OiP9PUcnaz4btyf8UfLcPXH/view?usp=sharing)|[Nehru_3_3.csv](https://drive.google.com/file/d/1DW4LLuWe_YKrVosPXt7XKVgAlNklTyeS/view?usp=sharing)| [4_3.mp4](https://drive.google.com/file/d/1wMFQNJzOn1bjSqA34H8Mwtn9AICwQdN5/view?usp=sharing)|[APMC_4_3.csv](https://drive.google.com/file/d/1gzV-wGHD7tafPNZ0ZrecvNbtPx11KH-6/view?usp=sharing)| 
NA|NA|[3_4.mp4](https://drive.google.com/file/d/1mvdfsFFsENlQDXHOadPeuHUnHsQjOOR5/view?usp=sharing)|[Nehru_3_4.csv](https://drive.google.com/file/d/1I-Y94tqC0bscpdGzTmhlqbqwqbZjCHKF/view?usp=sharing)|NA|NA| 

Finally, the Spatio-Temporal annotations segmented at the rate 5fps combining spatial and temporal annotations and for 3 intersections can be downloaded from the below table:

State|Paldi|Nehru|APMC|
-|-|-|-|
Clump|[P_C](https://drive.google.com/drive/folders/167InTOE5rwVDMPME-5u3oZR43odK5pN_?usp=sharing)|[N_C](https://drive.google.com/drive/folders/1LDJpIHh70UYiNsDphzcl_h48GBTfZpKl?usp=sharing)|[A_C](https://drive.google.com/drive/folders/16j7F3znca_HAsfGtpjdzPPcZjIaT4YFe?usp=sharing)|
Neutral|[P_N](https://drive.google.com/drive/folders/1GNjcOhctVALqUQffoqBnnHVH8InPcnKJ?usp=sharing)|[N_N](https://drive.google.com/drive/folders/1-5ZafOJwDU0tPjiWv4ixCzZI3XcpADy1?usp=sharing)|[A_N](https://drive.google.com/drive/folders/1de8WWPRHL92g_qGOExMYI7uvLfVvub7M?usp=sharing)|
Unclump|[P_U](https://drive.google.com/drive/folders/19zeHDCnB9dlrnuvexwzKJjcF0IWeNoas?usp=sharing)|[N_U](https://drive.google.com/drive/folders/1XwuTcwxlkSL6emuK7yrFiqVDYtxH2Na2?usp=sharing)|[A_U](https://drive.google.com/drive/folders/146ZAW3kKI_KM2aRL2HfnYc6tSmK-JbAK?usp=sharing)|

The overall breakdown of EoT dataset is given below:
![](images/details.png)

<h3>CNN Features</h3>
The tracks obtained for each of the Spatio-temporal regions are used to create a corresponding adjacency matrix based on the road user ids. The distance between two road users is converted into meters from pixel values. If the distance is less than μ= 10m, the corresponding entry is added to the adjacency matrix based on road width.  The image representation of the adjacency matrices is sent as input to the VGG16  CNN  architecture pre-trained on the ImageNet dataset.  The  input  image  is  resized  to  224×224  and  a  147 dimension feature vector is extracted from the average pool layer.<br><br>

The features can be downloaded [here](https://drive.google.com/drive/folders/156e5u6czBblMhLEFxG-gzbyj8H2Rk6WY?usp=sharing)

<h2> License </h2>

This dataset is provided for academic and research purposes only.

<h3> Annotator </h3>

* [K Naveen Kumar](https://naveenkumar1311.github.io/), First-year PhD Research Scholar, Dept. of Computer Science and Engineering, Indian Institute of Technology Hyderabad, India

<h2> Citation</h2>

If you use this dataset, consider citing our paper.

```
@inproceedings{roy2020defining,
  title={Defining Traffic States using Spatio-temporal Traffic Graphs},
  author={Roy, Debaditya and Kumar, K Naveen and Mohan, C Krishna},
  booktitle={2020 IEEE 23rd International Conference on Intelligent Transportation Systems (ITSC)},
  pages={1--6},
  year={2020},
  organization={IEEE}
}

```

<h2> Acknowledgment </h2>

This  work  has  been  conducted  as  the  part  of  SATREPS project [M2Smart “Smart  Cities  development  for  EmergingCountries by Multimodal Transport System based on Sensing, Network  and  Big  Data  Analysis  of  Regional  Transportation”](http://m2smart.org/en/) (JPMJSA1606) funded by JST and JICA
