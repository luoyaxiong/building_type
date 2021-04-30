# building_type



## Load annotation of opening and building

1. Open via/via.html
2. Click Project => Load => train/train_detected.json
3. Add local file / Add file => Select all the images on the folder 'train'
4. Finish, annotations are shown on the screen

For more details, please read the [VIA Tool Instruction.pdf](https://github.com/luoyaxiong/building_type/blob/main/VIA%20Tool%20Instruction.pdf)





## Folders

Dataset has 51 streets (idSegment)

`train`: select 87 images having good quailty from 24 streets

>  their street id are
>
>  14053,14054,14055,14056,14057,14058,14064,14065,14066,14067,14068,14069,14070,16835,16836,16837,16839,16850,16852,16854,16855,16882,16884,16888

`val `: select 18 images having good quailty from 5 streets 

>  16853, 16878, 16879, 16948, 16949

`test`: plan to select images from 8 street (not done yet)

> 16883, 14052, 16849, 16875, 14051, 16885, 14072, 16881

`new_train` :  select  80 new  images from the remaining 13 streets (Expand the train dataset) (need do annotation) 

`val_predict_4category`: prediction result of mask rcnn model with 4 categoties (opening, masonry, m6 ,rcw)

`val_predict_2category`: prediction result of mask rcnn model with 2 categoties (opening, building)

`via`:   the annotation tool  via applicaiton 

`train85`: move 2 images( rcw building type) ''16837_82101_19_4.jpg'', "16852_82116_15_1.jpg" to `val dataset

`val20`: reveive 2 images form `train`

