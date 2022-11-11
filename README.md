# ELE510 Project - Hand gesture detection

## HaGRID - HAnd Gesture Recognition Image Dataset
![](https://github.com/hukenovs/hagrid/blob/master/images/hagrid.jpg?raw=true)
Website: https://www.kaggle.com/datasets/kapitanov/hagrid <br />
Github: https://github.com/hukenovs/hagrid <br />

Since the full dataset is **716GB** we use the some subsample sets. <br />
Train and validate sets: 500 Images for each class from HaGRID test set where used for training and validating the model <br />
Train images download: https://sc.link/zlGy <br />
Train annotation download: https://sc.link/DE5K <br />

Test set: HaGRID subsambple set where used for testing our model <br />
Test images download: https://sc.link/AO5l <br />
Test annotation download: https://sc.link/EQ5g <br />
<br />

## Folder structure
Since the combined image files are so large we could not add them to the repository. The only folders that has to be added are under images. <br />
```bash
├───manual_test
│   ├───grayscale
│   └───rgb
├───test_original
│   ├───call
│   ├───dislike
│   ├───fist
│   ├───four
│   ├───like
│   ├───mute
│   ├───ok
│   ├───one
│   ├───palm
│   ├───peace
│   ├───peace_inverted
│   ├───rock
│   ├───stop
│   ├───stop_inverted
│   ├───three
│   ├───three2
│   ├───two_up
│   └───two_up_inverted
├───test_preprocessed
│   ├───call
│   ├───dislike
│   ├───fist
│   ├───four
│   ├───like
│   ├───mute
│   ├───ok
│   ├───one
│   ├───palm
│   ├───peace
│   ├───peace_inverted
│   ├───rock
│   ├───stop
│   ├───stop_inverted
│   ├───three
│   ├───three2
│   ├───two_up
│   └───two_up_inverted
├───train_original
│   ├───call
│   ├───dislike
│   ├───fist
│   ├───four
│   ├───like
│   ├───mute
│   ├───ok
│   ├───one
│   ├───palm
│   ├───peace
│   ├───peace_inverted
│   ├───rock
│   ├───stop
│   ├───stop_inverted
│   ├───three
│   ├───three2
│   ├───two_up
│   └───two_up_inverted
└───train_preprocessed
    ├───call
    ├───dislike
    ├───fist
    ├───four
    ├───like
    ├───mute
    ├───ok
    ├───one
    ├───palm
    ├───peace
    ├───peace_inverted
    ├───rock
    ├───stop
    ├───stop_inverted
    ├───three
    ├───three2
    ├───two_up
    └───two_up_inverted
```
