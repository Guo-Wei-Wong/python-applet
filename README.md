# python-applet
Some useful programs help training TensorFlow and Keras.

1.Auto_delete_useless_keras_weight_hdf5_files_after_training

when we use callback 'checkpoint' via keras during training, we expect only stored best weight files(h5/hdf5...).
but checkpoint callback was save each best weight files if better then the last weight files.
after training, there is many files, and we don't wanna delete them by manual.
this program can auto delete useless weight file and save history plot.
