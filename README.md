# fetal_subplate

## Final structure

```shell
fetal_sp
├── scripts
│   ├── sp_pred.sh
│   ├── sp_surf.sh
│   └── sp_tidy.sh
├── weights
│   ├── att
│   │   ├── axi.h5
│   │   ├── cor.h5
│   │   └── sag.h5
│   └── noa
│       ├── axi.h5
│       ├── cor.h5
│       └── sag.h5
├── subjects
│   ├── 01920
│   │   └── recon_segmentation
│   │       └── recon_to31_nuc.nii
│   ├── 29320
│   │   └── recon_segmentation
│   │       └── recon_to31_nuc.nii
│   └── ...
├── input
├── output
└── surfaces
    ├── 01920
    │   ├── lh.innersp.asc
    │   ├── rh.innersp.asc
    │   ├── lh.wm._81920.asc
    │   ├── rh.wm._81920.asc
    │   ├── 01920_nuc.nii
    │   └── 01920_nuc_deep_subplate_dilate.nii
    └── ...

```
