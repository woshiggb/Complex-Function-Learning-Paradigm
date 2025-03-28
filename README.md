# Complex Function Learning Paradigm

For multi-dimensional learning objectives, a new genetic learning method is provided.

### How to Use

To train with this model, follow these steps:

1. **Install Requirements**:
   Run the following command to install necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. **Test Methods**:
   - To simulate model dataset learning by drawing a line with the mouse in a row and training in a single round, use:
     ```bash
     python /your path/CODE/USE1.py
     ```
   - For input/output and guess generalization, run:
     ```bash
     python /your path/CODE/USE2.py
     ```
   - To compare the effect at various levels of the model with a small MLP layer using only coordinates, execute:
     ```bash
     python /your path/CODE/CODE_LIKE.py
     ```
   - Note: The model dataset's learning size is defined within a range of 0 to 5.

### Use in Code

Here is a sample of how to implement the model in code:

```python
import CODE.code__

# Initialize model
model = code__.Model(number, numeric_value)  # Generates a connection for a single dimension

#Be Like
x = 1
y = 1
# Forward and backward training
model.forward(x)  # Pass input vector x through the model
model.backward(x, y)  # Adjust model based on prediction vs expectation

#When modeldwo or Train2:
x = [0.1,0.2,0.3]
y = [0.3,0.1,0.111]
modeldwo.forward(x_i)
modeldwo.backward(y_i)
Train2.train_one(x,y,Epoch,1)


# Define model architecture
modeldwo = code__.ModelTypes(num_receptions, [size_layer1, size_layer2, ..., size_last_layer])

# Train multiple models
modelS = code__.Train2(num_models, [neurons_per_layer, num_receptions_per_model])

# Train and perform forward/backward propagation
modelS.forward(x)  # Vector input
modelS.backward(y)  # Vector expectation
```

### Additional Notes

- The same methodology applies for both `model` and `models`.
- Adjust the `number` and `numeric_value` to fit your specific requirements.
- Custom layers and neurons can be defined based on your learning objectives.
