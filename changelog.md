Changelog:
- The file `detectron2/data/datasets/coco.py` was modified.
- The function `register_coco_instances` was updated to include a check for the existence of the dataset in `DatasetCatalog` before registering it. This change was made between lines 507 and 508.
- The registration of the dataset with `DatasetCatalog` is now conditional on the dataset not already being registered. This change was made between lines 507 and 508.
- No other changes were made to the file.
