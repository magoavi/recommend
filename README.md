<center>

**[Abstract](#abstract)** |
**[License](#license)** 

</center>

[![Packagist](https://img.shields.io/badge/license-GNU%20GPL-blue.svg)](#license)
[![Packagist](https://img.shields.io/badge/author-avimago-green.svg)](https://github.com/magoavi)

# ![alt text](https://raw.githubusercontent.com/magoavi/recommend/master/viz/result_rmse.png)


#### Abstract

The `surprise` package was used for this exercise since that allowed for much faster calculations. The methodology for this question was inspired from (Jahrer, Töscher and Legenstein, 2010). The picture below briefly explains the methodology that was adopted for this part of the question. Some essential details missing from the picture below include:

# ![alt text](https://raw.githubusercontent.com/magoavi/recommend/master/viz/code_plan.png)

* The eight algorithms were trained on the whole training set for the final predictions which would be blended.
* The blender was trained on the full probe set after recording the rmse. This was only done after the model was selected
