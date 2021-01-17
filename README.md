# Character in Story Identification Network (CiSIN)

This project hosts the code for our paper.

- [Youngjae Yu](https://yj-yu.github.io/home), Jongseok Kim, Heeseung Yun, Jiwan Chung and [Gunhee Kim](http://vision.snu.ac.kr/~gunhee/).
Character Grounding and Re-Identification inStory of Videos and Text Descriptions. In *ECCV* (spotlight), 2020.

This project is an Winning Solution in LSMDC 19 ["Fill-in the Characters"](https://sites.google.com/site/describingmovies/lsmdc-2019/challenge-details?authuser=0) task.
For more information about the LSMDC visit the [Large Scale Movie Description Challenge (LSMDC) 2019](https://sites.google.com/site/describingmovies/lsmdc-2019)

## Reference

If you use this code as part of any published research, please refer following paper,

```bibtex
@inproceedings{yu:2020:ECCV,
    title="{Character Grounding and Re-Identification inStory of Videos and Text Descriptions}",
    author={Yu, Youngjae and Kim, Jongseok and Yun, Heeseung and Chung Jiwan and Kim, Gunhee},
    booktitle={ECCV},
    year=2020
}
```

## System Requirements

The following dependencies should be installed:

- Python 3.6
- Pytorch 1.4.0
- torchvision 0.5.0
- CUDA 10.0 supported GPU with at least 12GB memory
- see [requirements.txt](requirements.txt) for more details

## Data Setup

Coming soon,

### CiSIN

To train our model,
```bash
python train.py
```

## Acknowledgement

We thank SNUVL lab members for helpful comments.
This research was supported by Seoul National University, Brain Research Program by National Research Foundation of Korea (NRF) (2017M3C7A1047860), and AIR Lab (AI Research Lab) in Hyundai Motor Company through HMC-SNU AI Consortium Fund.


## License

[LICENSE.md](LICENSE.md).
