##Model1

Datasets: 51 Segments

![image-20210511191123053](/Users/luoyaxiong/Library/Application Support/typora-user-images/image-20210511191123053.png)

These segments are in the same street section but in two direction:

> 14051, 14072
>
> 14052, 14071
>
> 14053, 14070
>
> 14054, 14069
>
> 14055, 14068
>
> 14056, 14067
>
> 14057, 14066
>
> 14058, 14065, 19416

`train`: 87 images from 24 segments

>  their street id are
>
>  (14053,14070),(14054,14069),(14055,14068),(14056,14067),(14057,14066),(14058,14065), 14064,16835,16836,16837,16839,16850,16852,16854,16855,16882,16884,16888

`val `: 18 images from 5 segments 

>  16853, 16878, 16879, 16948, 16949

`test`: 21 segments (19416 not be used)

> Set1 (Annalisa annotate builidng type)(80 images, 7 segments): 16858,16872,16873,16876,16877,16880,16889
>
> Set2 (Alireza  annotate building type)(14 segments): (14051,14072),(14052,14071),16838,16849,16851,16856,16857,16875,16881,16883,16885,16890



## Model 2

`train`: 279 images,

 167 from Basel (model1_train 87 imgs + 80  imags from 4 new segments),

 112 from Zruich (31 masonry, 29 m6, 52 rcw )

> Basel segment ids are
>
> (14053,14070),(14054,14069),(14055,14068),(14056,14067),(14057,14066),(14058,14065), 14064,16835,16836,16837,16839,16850,16852,16854,16855,16882,16884,16888
>
> 16858, 16872, 16873, 16876  (new)

`val `: 52 images,

27 from Basel 8 segments, 

25 from Zurich ( 7 masonry, 6 m6, 12 rcw)

>  Basel segment ids are
>
> 16853, 16877, 16878, 16879, 16880, 16889, 16948, 16949






