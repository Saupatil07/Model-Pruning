### Readme
The following files are submitted with this report:
  1. Train_full_model.ipynb : This is the jupyter notebook which trains and saves the uncompressed
model to 300 iterations. We use this to save the uncompressed model weights which gives around
76.71% validation accuracy. Saved weights can be loaded into python scripts for pruning.
  2. Uncompressed_model_weights.h5: Weights for uncompressed model with 0 sparsity and 76.71%
accuracy.
  3. Global_thres_weights.h5: Weights for pruned model through global thresholding which yields best
challenge score.
  4. Layerwise_thre_weights.h5: Weights for pruned model through global thresholding which yields best
challenge score.
  5. Method1&2.ipynb: Jupyter notebook for pruning weights using methods Global Thresholds &
Layerwise Thresholds. Also used for creating Pareto charts for all 3 methods.
  6. Freeze_layer_retraining_method.ipynb: Jupyter notebook for pruning weights by freezing layers and
retraining the weights.
  7. Freeze_layer_training_weights.h5: Weights for pruned model through freezing and retraining
weights which yields best challenge score.
  8. my_model_weights.h5: Best challenge score weights
  9. Masking_method.ipynb: Implementation of Method 4.
