The **QHDP: QUT-HIA-DAF Polytunnel Dataset** was collected in Australia under direct sunlight in a field situation. All cultivars in the dataset consist of three classes: *green*, *mixed*, and *red*. 

Note, similar **QHDF: QUT-HIA-DAF Field Dataset** datasets are also available on the [DatasetNinja.com](https://datasetninja.com/):

- [BUP19: Sweet Pepper Dataset](https://datasetninja.com/bup19)
- [BUP20: Sweet Pepper Dataset](https://datasetninja.com/bup20)
- [QHDF: QUT-HIA-DAF Field Dataset](https://datasetninja.com/qutf)

## Motivation

The realm of agricultural robotics is swiftly advancing thanks to breakthroughs in computer vision, machine learning, and robotics, spurred on by the growing demands of agriculture. Yet, there remains a significant disparity between farming necessities and the technology currently available, largely due to the diverse nature of cropping environments. This underscores the urgent requirement for more universally applicable models.

The prominence of agricultural robotics continues to rise, driven by progress in robotics, computer vision, and machine learning. These advancements are propelled by the imperative for farmers to enhance both yield and quality while simultaneously reducing labor costs, a factor that has long been recognized as one of the most financially burdensome aspects of agriculture. Enhancing these key farming metrics necessitates automated technologies like weed management and harvesting. Within these domains, the integration of robotic vision and machine learning is poised to play a pivotal role in ensuring successful incorporation into existing agricultural processes.

## Dataset description

The authors explore the issue of generalisability by considering a fruit (sweet pepper) that is grown using different cultivars (subspecies) and in different environments (field vs glasshouse). To investigate these differences, they publicly release three novel datasets captured with different domains, cultivars, cameras, and geographic locations. The authors exploit these new datasets in a singular and combined (to promote generalisation) manner to evaluate sweet pepper (fruit) detection and classification in the wild. The authors complete an analysis of sweet pepper detection in the wild, employing three datasets which they
release publicly. Each dataset used in this evaluation represents a different domain. They exploit datasets collected in two unique geographical locations: Australia and Germany; and in three different set ups: field, polytunnel, and a glass house. The two QHD sets were collected in Australia by the Queensland University of Technology (QUT) with Horticulture Innovation Australia (HIA) and the Department of Agriculture and Fisheries (DAF). The final dataset (BUP) was collected in Germany by the University of Bonn.

<img src="https://github.com/dataset-ninja/qutf/assets/120389559/97397b48-4e02-41d1-930a-1192c639f87e" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Example images from each of the three datasets: (left column) QHDF field dataset; (middle column) BUP glass house dataset; and (right column) QHDP protected extended dataset.</span>

| Dataset | T   | V   | E   | Height | Width | Camera       |
|---------|-----|-----|-----|--------|-------|--------------|
| QHDF    | 509 | 604 | 470 | 640    | 480   | RealSense 200|
| QHDP    | 345 |  86 | 256 | 640    | 480   | RealSense 200|
| BUP     | 114 |  84 |  88 | 1280   | 720   | RealSense 435i|

<span style="font-size: smaller; font-style: italic;">The number of images contained in each of the datasets used in this paper, where ’T’, ’V’, and ’E’ represent the training, validation, and evaluation sets respectively.</span>

| Dataset   | Subset     | Green | Mixed | Red |
|-----------|------------|-------|-------|-----|
| QHDF      | training   | 1215  | 89    | 609 |
|           | validation | 1389  | 94    | 716 |
|           | evaluation | 1131  | 73    | 458 |
| QHDP      | training   | 782   | 170   | 718 |
|           | validation | 208   | 34    | 155 |
|           | evaluation | 956   | 190   | 528 |

<span style="font-size: smaller; font-style: italic;">Distribution of sweet pepper in each of the QHD datasets.</span>

The QHDP dataset was collected in a polytunnel, providing some protection from the sun. It consists of two cultivars, Warlock and SV6947, each cultivar was planted in a single- and double-row plant configuration in outdoor field conditions. Annotation of the extra data was completed by a single individual with verification by a second. Slight variations exist between the original data and this super set, primarily due to the manual removal of foliage by farmers to make manual crop counting more efficient.

<img src="https://github.com/dataset-ninja/qhdp/assets/120389559/202a4f51-2009-4586-af44-5d94db8a195d" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Four example images with their respective bounding boxes from the QHDP dataset.</span>



