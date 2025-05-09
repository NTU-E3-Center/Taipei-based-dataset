# Taipei-based-dataset

## HDF5 File Structure

The dataset used in this project is stored in a single HDF5 (.h5) file, organized as follows:

```text
/train
    /images_log   # Sky images for training 
    /pv_log       # Corresponding PV output values for training (in Watts)

/test
    /images_log   # Sky images for testing
    /pv_log       # Corresponding PV output values for testing
