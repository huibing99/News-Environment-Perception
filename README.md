# News Environment Perception

**[Notes]** The repo may be incomplete and some of the code is a bit messy. We will improve in the near future. Readme will also include more details. Coming soon stay tuned :)

---

This is the official repository of the paper:

> **Zoom Out and Observe: News Environment Perception for Fake News Detection**
>
> Qiang Sheng, Juan Cao, Xueyao Zhang, Rundong Li, Danding Wang, and Yongchun Zhu
>
> *Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (ACL 2022)*
>
> [PDF](https://aclanthology.org/2022.acl-long.311.pdf) / [Poster](https://sheng-qiang.github.io/data/NEP-Poster.pdf) / [Code](https://github.com/ICTMCG/News-Environment-Perception) / [Chinese Video](https://www.bilibili.com/video/BV1MS4y1e7PY) / [Chinese Blog](https://mp.weixin.qq.com/s/aTFeuCYIpSoazeRi52jqew)

## Datasets

The experimental datasets where can be seen in `dataset` folder, including the [Chinese Dataset](https://github.com/ICTMCG/News-Environment-Perception/tree/main/dataset/Chinese), and the [English Dataset](https://github.com/ICTMCG/News-Environment-Perception/tree/main/dataset/English). Note that you can download the datasets only after an ["Application to Use the Datasets for XXXXXX"]() has been submitted.

## Code

### Key Requirements

```
python==3.6.10
torch==1.6.0
transformers==3.2.0
```

### Preparation

#### Step1: Construct the macro & micro environment

BM25

#### Step 2: Obtain the representations of posts and news environment items

SimCSE

#### Step 3: Prepare for the specific detectors

- BiLSTM
- EANN
- BERT
- BERT-Emo
- DeClarE
- MAC

### Training and Inferring

## Citation

```
@inproceedings{NEP,
    title = "Zoom Out and Observe: News Environment Perception for Fake News Detection",
    author = "Sheng, Qiang  and
      Cao, Juan  and
      Zhang, Xueyao  and
      Li, Rundong and
      Wang, Danding  and
      Zhu, Yongchun",
    booktitle = "Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics",
    month = may,
    year = "2022",
    publisher = "Association for Computational Linguistics"
}
```
