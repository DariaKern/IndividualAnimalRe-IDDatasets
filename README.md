# IndividualAnimalRe-IDDatasets
### a collection of publicly available computer vision datasets for the re-identification of individual animals

|Dataset|# of Individuals|Data|Content|Labels|License|
|--------|--------|--------|--------|--------|--------|
|[AAU Zebrafish Re-Identification Dataset](https://www.kaggle.com/datasets/aalborguniversity/aau-zebrafish-reid) ![zebrafish](./zebrafish.png)|6 zebrafish|2 videos resulting in 2224 images|side-view of fish in a tank|BB + identity annotations|CC BY 4.0|
|[ATRW](https://www.kaggle.com/datasets/quadeer15sh/amur-tiger-reidentification) ![tiger](./tiger.jpg)|92 tigers|8076 videos|tigers in unconstrained poses|BB + keypoint-based pose + identity annotations|CC BY-NC-SA 4.0|
|[Cat Individual Images](https://www.kaggle.com/datasets/timost1234/cat-individuals) ![cat](./cat.jpg)|518 cats|13536 images|front-view of cats with a focus on faces|identity annotations|CC BY 4.0|
|[Cow Dataset](https://doi.org/10.6084/m9.figshare.16879780) ![cow](./cow.jpg)|13 cows|3772 Images|side-view of cows|identity annotations|CC BY 4.0|
|[Cows2021](https://data.bris.ac.uk/data/dataset/4vnrca7qw1642qlwxjadp87h7) ![cows2021](./cows2021.png)|186 cows|10402 images + 301 videos|top down view of the cows body|oriented BB + identity + tracklet annotations|CC BY-NC-SA 4.0|
|[Dog Face Recognition](https://www.kaggle.com/datasets/wutheringwang/dog-face-recognition) ![dog](./dog.jpg)|1174 dogs|?? images|dog faces|identity annotations|CC0: Public Domain|
|[Happy Whale](https://www.kaggle.com/competitions/happy-whale-and-dolphin/data) ![happywhale](./happywhale.jpg)|15587 whales and dolphins|51033 images|30 species of whales and dolphins entierely or partly above the water surface|identity annotations|Competition, Academic, and Non-Commercial Use Only|
|[SealID](https://doi.org/10.23729/0f4a3296-3b10-40c8-9ad3-0cf00a5a4a53) ![seal](./seal.jpg)|57 seals|2080 images|seals in unconstrained poses on land|identity annotations|CC BY 4.0|
|[iPanda-50](https://github.com/iPandaDateset/iPanda-50) ![giantpanda](./giantpanda.jpg)|50 giant pandas|6874 images|pandas in unconstrained poses|identity annotations|??|
|[Animal-Identification-from-Video](https://github.com/LucyKuncheva/Animal-Identification-from-Video) ![idfromvideo](./idfromvideo.png)|26 pigs, 9 koi fish, 58 pigeons|5 videos resulting in 2379 frames| pigs (above/side view), koi fish (top down view) and pigeons on the ground (sideview) in unconstrained poses|BB + identity annotaions|pixabay license|
<!-- |[BirdIndividualID](https://github.com/AndreCFerreira/Bird_individualID)| 30 sociable weavers, 10 great tits, 10 zebra finches| unfortunately description of dataset unclear & dataset download currently not possible |coarse segmentation + identity annotations| license unclear|-->



### corresponding publications
|Year|Publication*|Species|Identifying Feature|Corresponding Dataset|
|--------|--------|--------|--------|--------|
|2022|[A Benchmark Database for Animal Re-Identification and Tracking](https://doi.org/10.1109/IPAS55744.2022.10052988)|Pigeon, Koi Fish, Pig|whole body|[Animal-Identification-from-Video](https://github.com/LucyKuncheva/Animal-Identification-from-Video)|
|2022|[SealID: Saimaa Ringed Seal Re-Identification Dataset](https://doi.org/10.3390/s22197602)|Saimaa Ringed Seal|pelage patterns|[SealID](https://doi.org/10.23729/0f4a3296-3b10-40c8-9ad3-0cf00a5a4a53)|
|2021|[Giant Panda Identification](https://doi.org/10.1109/TIP.2021.3055627)|Giant Panda|discriminative local patches - they found panda’s eyes play a critical role in panda identification|[iPanda-50](https://github.com/iPandaDateset/iPanda-50)|
|2021|[Individual dairy cow identification based on lightweight convolutional neural network](https://doi.org/10.1371/journal.pone.0260510)|Cows|unspecific|[Cow Dataset](https://doi.org/10.6084/m9.figshare.16879780)|
|2021|[Towards Self-Supervision for Video Identification of Individual Holstein-Friesian Cattle: The Cows2021 Dataset](https://www.researchgate.net/publication/351354662_Towards_Self-Supervision_for_Video_Identification_of_Individual_Holstein-Friesian_Cattle_The_Cows2021_Dataset)|Holstein-Friesian Cattle|coat pattern|[Cows2021](https://data.bris.ac.uk/data/dataset/4vnrca7qw1642qlwxjadp87h7)|
|2020|[ATRW: A Benchmark for Amur Tiger Re-identification in the Wild](https://doi.org/10.1145/3394171.3413569)|Amur Tiger|coat pattern|[ATRW](https://www.kaggle.com/datasets/quadeer15sh/amur-tiger-reidentification)|
|2020|[Re-Identification of Zebrafish using Metric Learning](https://doi.org/10.1109/WACVW50321.2020.9096922)|Zebrafish|stripes, body pattern|[AAU Zebrafish Re-Identification Dataset](https://www.kaggle.com/datasets/aalborguniversity/aau-zebrafish-reid)|


*be sure to check for an [ArXiv](https://arxiv.org/) version of any paper that is behind a paywall

### further publications on the topic where the dataset could not be found and might not be public OR is only available on request

|Year|Publication|Species|Identifying Feature|Note|
|--------|--------|--------|--------|--------|
|2022|[Honeybee Re-identification in Video: New Datasets and Impact of Self-supervision](https://jachansantiago.com/assets/pdf/VISAPP.pdf)|Honey Bees|abdomen||
|2021|[YakReID-103: A Benchmark for Yak Re-Identification](https://doi.org/10.1109/IJCB52358.2021.9484341)|Yak|fur, texture, horns||
|2021|[Robust Re-identification of Manta Rays from Natural Markings by Learning Pose Invariant Embeddings](https://doi.org/10.1109/DICTA52665.2021.9647359)|Manta Rays|belly markings||
|2021|[Dog Nose-Print Identification Using Deep Neural Networks](https://doi.org/10.1109/ACCESS.2021.3068517)|Dogs|nose||
|2021|[Assessing the performance of open-source, semi-automated pattern recognition software for harbour seal (P. v. vitulina) photo ID]()|Harbour Seal|body pattern||
|2020|[Deep learning-based methods for individual recognition in small birds](https://doi.org/10.1111/2041-210X.13436)|Sociable Weaver, Great Tit, Zebra Finch|body|a|
|2020|[Bumblebee Re-Identification Dataset](https://doi.org/10.1109/WACVW50321.2020.9096909)|Bumblebee|body|b|
|2020|[A study on giant panda recognition based on images of a large proportion of captive pandas](https://doi.org/10.1002/ece3.6152)|Giant Panda|face||
|2020|[Automated facial recognition for wildlife that lack unique markings: A deep learning approach for brown bears](https://doi.org/10.1002/ece3.6840)|Brown Bear|face||
|2020|[Image-based Individual Cow Recognition using Body Patterns](https://dx.doi.org/10.14569/IJACSA.2020.0110311)|4 Species of Cow|body pattern||
|2019|[ELPephants: A Fine-Grained Dataset for Elephant Re-Identification](https://doi.org/10.1109/ICCVW.2019.00035)|Elephants|tusks, body shapes, injury marks||
|2019|[Chimpanzee face recognition from videos in the wild using deep learning](https://doi.org/10.1126/sciadv.aaw0736)|Chimpanzee|face||
|2019|[Distinguishing Individual Red Pandas from Their Faces](https://doi.org/10.1007/978-3-030-31723-2_61)|Red Panda|face||
|2018|[Individual Common Dolphin Identification Via Metric Embedding Learning](https://doi.org/10.1109/IVCNZ.2018.8634778)|Common Dolphin|fin||
|2018|[Individual Minke Whale Recognition Using Deep Learning Convolutional Neural Networks](https://doi.org/10.4236/gep.2018.65003)|Dwarf Minke Whale|fin, scars, body||
|2018|[Multi-views Embedding for Cattle Re-identification](https://doi.org/10.1109/SITIS.2018.00036)|Cattle|face||
|2016|[Automated Visual Fin Identification of Individual Great White Sharks]( https://doi.org/10.1007/s11263-016-0961-y)|Great White Shark|fin|c|
|2013|[An automated chimpanzee identification system using face detection and recognition](https://doi.org/10.1186/1687-5281-2013-49)|Chimpanzee|face||
|2011|[Biometric animal databases from field photographs: identification of individual zebra in the wild](https://doi.org/10.1145/1991996.1992002)|Grevy’s Zebra + Plains Zebra|stripes|d|


[a] [GitHub](https://github.com/AndreCFerreira/Bird_individualID) available but dataset cannot be donwloaded

[b] please refer to data@apic.ai for early access

[c] to obtain a copy please directly contact: Michael C. Scholl, Save Our Seas Foundation (CEO), Michael@SaveOurSeas.com

[d] dataset can be downloaded [here](http://code.google.com/p/stripespotter/) but unfotunetely the .zip file cannot be extracted

### other resources
|Website|Dataset|Species|Identifying Feature|
|--------|--------|--------|--------|
|[Sarasota Dolphin Research Program](https://sarasotadolphin.org/)|[GoMDIS](https://sarasotadolphin.org/gomdis/)|bottlenose dolphins|dorsal fin|
|[Cascadia Research Collective](https://cascadiaresearch.org/)|[Photo-ID Project](https://cascadiaresearch.org/project/photo-id/)|humpback and blue whale|flukes (humpback whale), dorsal fin (blue whale)| 
|[OBIS-SEAMAP](https://seamap.env.duke.edu/content/about)|[various datasets](https://seamap.env.duke.edu/dataset/list)|[various species](https://seamap.env.duke.edu/species/list)|-|
|[Species 360](https://species360.org/)|[various data](https://conservation.species360.org/data-sharing/)|various species|-|
|[Bay Cetology](https://baycetology.org/)|Bigg’s killer whale photo-ID data|killer whale|-|

### further reading
I'd like to highlight this outstanding publication from 2021 which gives a great overview of the entire topic
[Perspectives on Individual Animal Identification from Biology and Computer Vision](https://doi.org/10.1093/icb/icab107)


[AIDE: Annotation Interface for Data-driven Ecology](https://github.com/microsoft/aerial_wildlife_detection) is a free tool from Microsoft for manually annotating images & also for training and running machine learning models. Both coupled in an active learning loop

Microsoft has also published the [MegaDetector](https://github.com/microsoft/CameraTraps/blob/main/megadetector.md) on GitHub. It detects animals, people, and vehicles in camera trap images
