<h3 align="center">
    <p>State-of-the-art Vision Transformer 🤗 for image classification, High Accuracy 🚀</p>
</h3>

## Fashion product images dataset
44k products with multiple category labels, descriptions and high-res images. [Link](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)

#### Training result
|           Epoch            |   Training Loss  | Validation Loss | Accuracy |
|:-------------------------:|:-------------------------------:|:------:| :------:|
|       1        |         0.082200          |  0.059544   | 0.992506 |
|       2        |         0.042800	         |  0.035637   | 0.995316 |
|       3        |         0.033300          |  0.030343   | 0.995472 |


```python
>>> trainer.train()

# Evaluate the model on the test set
>>> outputs = trainer.predict(test_data)
>>> outputs.metrics
[{'test_loss': 0.03034268133342266, 'test_accuracy': 0.9954722872755659, 'test_runtime': 102.7551}]
```

## 5 Flower types classification dataset
Flower Images for Classification (1k images for each flower types) [Link](https://www.kaggle.com/datasets/kausthubkannan/5-flower-types-classification-dataset)

#### Training result
|           Epoch            |   Training Loss  | Validation Loss | Accuracy |
|:-------------------------:|:-------------------------------:|:------:| :------:|
|       1        |         No log	          |  0.349625   | 0.974667 |
|       2        |         No log		         |  0.184932  | 0.984000 |
|       3        |         No log	          |  0.137928   | 0.989333 |
|       4        |         0.369800          |  0.122166  | 0.988000 |
|       5        |         0.369800          |  0.117171   | 0.988000 |


```python
>>> trainer.train()

# Evaluate the model on the test set
>>> outputs = trainer.predict(test_data)
>>> outputs.metrics
[{'test_loss': 0.13792766630, 'test_accuracy': 0.98933333, 'test_runtime': 12.5379}]
```

## Brain MRI Images dataset
It conists of MRI scans of two classes: NO - no tumor, encoded as 0  YES - tumor, encoded as 1
  [Link](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

#### Training result
|           Epoch            |   Training Loss  | Validation Loss | Accuracy |
|:-------------------------:|:-------------------------------:|:------:| :------:|
|       1        |         No log	          |  0.533956  | 0.769231 |
|       2        |         No log		         |  0.454096  | 0.876923 |
|       3        |         No log	          |  0.389601   | 0.969231 |
|       4        |         0.369800          |  0.347400  | 0.984615 |
|       5        |         0.369800          |  0.336078   | 0.984615 |


```python
>>> trainer.train()

# Evaluate the model on the test set
>>> outputs = trainer.predict(test_data)
>>> outputs.metrics
[{'test_loss': 0.347400099, 'test_accuracy': 0.984615384, 'test_runtime': 0.8473}]
```
