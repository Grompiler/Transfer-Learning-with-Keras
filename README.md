# Transfer-Learning-with-Keras

###Classification of glass vs platstic bottles using keras and python3.6+

## Installing requirements

```bash
pip install tensorflow
pip install keras
pip3 install pillow
```

## Example: train the model and classify an image

```python
'''we have only two functions in the code (train and classify) to make it easy to use'''
>>> train() # will train the model and save it to 'My_resNet50_weights.h5' by default
>>> classify('path/to/image') # just replace the path with one image of bottle you want to classify
```
