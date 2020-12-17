# parameters

``` yaml
extrinsicRotation: !!opencv-matrix
    rows: 3
    cols: 3
    dt: d
    data: [0.0,-1.0,0.0, 
        -1.0,0.0,0.0, 
        0.0, 0.0, -1.0]
        #Translation from camera frame to imu frame, imu^T_cam
extrinsicTranslation: !!opencv-matrix
    rows: 3
    cols: 1
    dt: d
    data: [-0.028, -0.020, 0.0]
```

![F7A71E89-7DFD-4FCC-A19A-BB01883D984F](https://tva1.sinaimg.cn/large/0081Kckwly1gkz6u9hw6cj30jq0uiwqw.jpg)

ARKit uses world and camera coordinate systems following a **right-handed** convention: the y-axis points upward, and (when relevant) the z-axis points toward the viewer and the x-axis points toward the viewer’s right



![916B8FA0-BE07-47C1-987D-8006179E06AA](https://tva1.sinaimg.cn/large/0081Kckwly1gkz6uqctdkj31660o61im.jpg)



![0614E6A0-578F-4E90-8F0F-3DDAB0ADB2F2](https://tva1.sinaimg.cn/large/0081Kckwly1gkz6v1o5vdj30ig0ykauo.jpg)



---

## SC

![](https://tva1.sinaimg.cn/large/0081Kckwly1glrlauwm3gj31440u0kjn.jpg)

----

## L515

![L515_gt](https://tva1.sinaimg.cn/large/0081Kckwly1glrlcbcu3zj30w80rw44t.jpg)

