## Directory structure

- `coco`: [coco API](https://github.com/pdollar/coco)
- `keypoint`: COCO keypoint dataset
    - `images`: tain and val datasets
        - `train2014`
        - `val2014`
    - `person_keypoints_train+val5k2014`: annotations (JSON files)
- `coco_annotations.json`: reformatted annotation generated by `./miscs/gen_coco.m`
