# Shape Classifier (Team 10)

Image classification model that predicts Circle, Square, or Triangle.

## Dataset
- 1500 synthetic images (500 per class), generated in Python with PIL
- Image size: 128 x 128
- Split: 80% training, 20% testing

## Model
- Small CNN built with TensorFlow/Keras
- Trained for 25 epochs

## Result
- Test accuracy: 92.0%

## Files
- Team10_Shape_Classifier.ipynb: dataset generation, training, evaluation
- dataset.zip: generated dataset
- shape_model.keras: exported model (class order: 0 = Circle, 1 = Square, 2 = Triangle)

## Limitations
- The model was trained on computer-generated shapes, so it may perform worse on real photos from a webcam.
