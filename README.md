<h3 align="center">
    <p>State-of-the-art Vision Transformer 🤗 for image classification, High Accuracy 🚀</p>
</h3>

### Fashion Product Images Dataset [Link](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)
44k products with multiple category labels, descriptions and high-res images.


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
[{'test_loss': 0.03034268133342266, 'test_accuracy': 0.9954722872755659, 'test_runtime': 102.7551, 'test_samples_per_second': 62.333, 'test_steps_per_second': 15.59}
]
```

