# AI-Proposal-2022-
### TO Do
- [ ] [Proposal PPT](https://docs.google.com/presentation/d/1-ZdYMbY4Zq_WSd2lBxrQ-H3U7_JbkAf37cZSVyEMnW0/edit#slide=id.g124790f166a_3_5)
- [x] [Paper 1 PPT](https://docs.google.com/presentation/d/1gEe2carjGd7-xu7UHD-omJtS8JjAkBb7Xnx80wVPJK8/edit?pli=1#slide=id.g11da5a5c396_1_35)
- [x] [Paper 1](https://web.kamihq.com/web/viewer.html?state=%7B%22ids%22%3A%5B%22105X3WRWJ7eBbkGrrT2koD84wVLBnR5WX%22%5D%2C%22action%22%3A%22open%22%2C%22userId%22%3A%22101601498344690328896%22%2C%22resourceKeys%22%3A%7B%7D%7D&kami_user_id=27731356)

### Structure
```
├── LICENSE
├── README.md
├── Split
│   ├── AZH_m
│   │   ├── train
│   │   └── val
│   └── Medetic_m
│       ├── train
│       └── val
└── Without spit
    ├── AZH
    │   ├── Diabetes
    │   ├── Pressure
    │   └── Venous
    └── Medetic
        ├── Diabetes
        ├── Pressure
        └── Venous and Aterial
```
----------------
### Datasets
#### [AZH Datasets](https://github.com/uwm-bigdata/wound_classification/tree/main/data/original%20images)
**Original**
* D: 154 images
* V: 156 images
* P: 100 images

**Training**
* D: 123 images
* V: 124 images
* P: 80 images


#### **[Medectec](http://www.medetec.co.uk/files/medetec-image-databases.html)** 
**Original**
* D: 46 images
* P:166 images
* A+V: total 120. (original website has 136 images, manully deleted 15 images with covered by dressing, and 1 image which doesn't belong to wound.)

**Training**
* D: 36 images
* P:132 images
* A+V: 96 images
