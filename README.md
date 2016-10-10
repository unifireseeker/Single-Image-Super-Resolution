# Single-Image-Super-Resolution
A list of resources for example-based single image super-resolution, inspired by [Awesome-deep-vision] (https://github.com/kjw0612/awesome-deep-vision).

By Yapeng Tian.

##Important Papers
###External example-based methods
[1] Freeman, William T and Pasztor, Egon C and Carmichael, Owen T, Learning low-level vision, IJCV, 2000. [[Paper]](http://people.csail.mit.edu/billf/papers/TR2000-05.pdf) ([Freeman](billf.mit.edu) et al. first presented example-based or learning-based method super-resolution framework - learn relationships between low-resolution image pathes and its high-resolution counterparts.)

[2] Freeman, William T and Jones, Thouis R and Pasztor, Egon C, Example-based super-resolution, IEEE Computer graphics and Applications, 2002.    [[Paper]](http://www.merl.com/publications/docs/TR2001-30.pdf) 

[3] Chang, Hong and Yeung, Dit-Yan and Xiong, Yimin, Super-resolution through neighbor embedding, CVPR, 2004. [[Paper]](http://repository.ust.hk/ir/bitstream/1783.1-2284/1/yeung.cvpr2004.pdf) [[Code]](http://www.jdl.ac.cn/user/hchang/publication.htm) (The idea that low-resolution patches and corresponding high-resolution patches share similar local geometries highly influences the subsequent coding-based or dictionary-based methods.)
####Sparsity-based methods
[4] Yang, Jianchao and Wright, John and Huang, Thomas S and Ma, Yi, Image super-resolution via sparse representation, IEEE trans. image processing 2010. [[paper]](http://ieeexplore.ieee.org/document/5466111/?arnumber=5466111) [[Code]](http://www.ifp.illinois.edu/~jyang29/) (SCSR: Classical sparsity-based SISR method - use sparse coding technique to learn low-resolution and high-resolution dictionaries.)

[5] Zeyde, Roman and Elad, Michael and Protter, Matan, On single image scale-up using sparse-representations, International conference on curves and surfaces, 2010. [[Paper]](http://www.cs.technion.ac.il/~elad/publications/conferences/2010/ImageScaleUp_LNCS.pdf) [[Code]](http://www.cs.technion.ac.il/~elad/software/)  (Low dimension feature speeds up the algorithm. Many sparsity-based image restoration techniques can be found in Prof. [Elad](http://www.cs.technion.ac.il/~elad/index.html)'s Website!) 

[6] Weisheng Dong, Lei Zhang, Guangming Shi, and Xiaolin Wu, Image Deblurring and Super-resolution by Adaptive Sparse Domain Selection and Adaptive Regularization, TIP, 2011. [[Website]](http://www4.comp.polyu.edu.hk/~cslzhang/ASDS_AReg.htm) (Clustering is a very effective trick and local and nonlocal regularization terms are very powerful! Other good sparsity-based super-resolution methods can be found in Prof. [Lei Zhang](http://www4.comp.polyu.edu.hk/~cslzhang/)'s and [Weisheng Dong](http://see.xidian.edu.cn/faculty/wsdong/)'s Website!)

[7] Peleg, Tomer and Elad, Michael, A statistical prediction model based on sparse representations for single image super-resolution, TIP, 2014. [[Paper]](http://www.cs.technion.ac.il/~elad/publications/journals/2013/SingleImageSR_TIP.pdf) [[Code]](http://www.cs.technion.ac.il/~elad/software/) (Predict the relationships between Low-resolution and high-resolution representation coefficients.)

####Locally Linear Regression

[1] Gu, Shuhang and Sang, Nong and Ma, Fan, Fast Image Super Resolution via Local Regression, ICPR, 2012. [[Paper]](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6460827) (Kmeans clusetering + ridge regression)
