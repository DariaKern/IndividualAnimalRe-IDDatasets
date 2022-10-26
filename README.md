# IndividualAnimalRe-IDDatasets
### a collection of publicly available computer vision datasets for the re-identification of individual animals

|Dataset|Species|# of Individuals|Data|Content|Identifying Feature|Labels|Corresponding Paper*|License|
|--------|--------|--------|--------|--------|--------|--------|--------|--------|
|[Cows2021](https://github.com/Wormgit/Cows2021)|Holstein-Friesian Cattle|186|10402 images + 301 videos|top down view of the cows body|coat pattern|oriented BB + identity + tracklet annotations|[Towards Self-Supervision for Video Identification of Individual Holstein-Friesian Cattle: The Cows2021 Dataset](https://www.researchgate.net/publication/351354662_Towards_Self-Supervision_for_Video_Identification_of_Individual_Holstein-Friesian_Cattle_The_Cows2021_Dataset)|CC BY-NC-SA 4.0|
|[Cat Individual Images](https://www.kaggle.com/datasets/timost1234/cat-individuals)|Cats|518|13536 images|cat faces|face|identity annotations|none found|CC BY 4.0|
|[Happy Whale](https://www.kaggle.com/code/chasset/sampling-happywhale/notebook)|30 species of whales and dolphins|15587|51033 images|animals entierely or partly above the water surface|fin, back|identity annotations|none found|Apache 2.0|
|[ATRW](https://www.kaggle.com/datasets/quadeer15sh/amur-tiger-reidentification)|Amur Tiger|92|8076 videos|tigers in unconstrained poses|coat pattern|BB + keypoint-based pose + identity annotations|[ATRW: A Benchmark for Amur Tiger Re-identification in the Wild](https://doi.org/10.1145/3394171.3413569)|CC BY-NC-SA 4.0|
|[Dog Face Recognition](https://www.kaggle.com/datasets/wutheringwang/dog-face-recognition)|Dogs|1174|?? images|dog faces|face|identity annotations|none found|CC0: Public Domain|
|[SealID](https://doi.org/10.23729/0f4a3296-3b10-40c8-9ad3-0cf00a5a4a53)|Saimaa Ringed Seal|57|2080 images|seals in unconstrained poses on land|pelage patterns|identity annotations|[SealID: Saimaa Ringed Seal Re-Identification Dataset](https://doi.org/10.3390/s22197602)|CC BY 4.0|
|[AAU Zebrafish Re-Identification Dataset](https://www.kaggle.com/datasets/aalborguniversity/aau-zebrafish-reid)|Zebrafish|6|2 videos resulting in 2224 images|side-view of fish in a tank|stripes, body pattern|BB + identity annotations|[Re-Identification of Zebrafish using Metric Learning](https://doi.org/10.1109/WACVW50321.2020.9096922)|CC BY 4.0|

*be sure to check for an [ArXiv](https://arxiv.org/) version of any paper that is behind a paywall

### further Publications on the topic where the dataset could not be found and might not be public

|Year|Publication|Species|Identifying Feature|
|--------|--------|--------|--------|
|2022|[Honeybee Re-identification in Video: New Datasets and Impact of Self-supervision](https://jachansantiago.com/assets/pdf/VISAPP.pdf)|Honey Bees|abdomen|
|2021|[YakReID-103: A Benchmark for Yak Re-Identification](https://doi.org/10.1109/IJCB52358.2021.9484341)|Yak|fur, texture, horns|
|2021|[Robust Re-identification of Manta Rays from Natural Markings by Learning Pose Invariant Embeddings](https://doi.org/10.1109/DICTA52665.2021.9647359)|Manta Rays|belly markings|
|2020|[A study on giant panda recognition based on images of a large proportion of captive pandas](https://doi.org/10.1002/ece3.6152)|Giant Panda|face|
|2019|[ELPephants: A Fine-Grained Dataset for Elephant Re-Identification](https://doi.org/10.1109/ICCVW.2019.00035)|Elephants|tusks, body shapes, injury marks|
|2018|[Individual Common Dolphin Identification Via Metric Embedding Learning](https://doi.org/10.1109/IVCNZ.2018.8634778)|Common Dolphin|fin|
