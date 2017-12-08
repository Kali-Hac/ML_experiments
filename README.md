# ML 第一次实验

## 实验目的 
- 进一步理解线性回归和梯度下降的原理。
	* 在小规模数据集上实践。
	* 优化和调参的过程。
	* 数据集以及数据分析：
- 进一步理解线性分类和梯度下降的原理。
	* 在小规模数据集上实践。
	* 优化和调参的过程。

## 对比线性回归和线性分类的异同点：
* 1.Linear SVM和LR都是线性分类器
* 2.Linear SVM不直接依赖数据分布，分类平面不受一类点影响；LR则受所有数据点的影响，如果数据不同类别strongly unbalance一般需要先对数据做balancing。
* 3.Linear SVM依赖数据表达的距离测度，所以需要对数据先做normalization；LR不受其影响
* 4.Linear SVM依赖penalty的系数，实验中需要做validation
* 5.Linear SVM和LR的performance都会收到outlier的影响