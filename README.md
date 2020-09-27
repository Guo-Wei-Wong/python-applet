# python-applet

I wrote these programs.
Some useful programs help training when using TensorFlow and Keras.

1.Auto_delete_useless_keras_weight_hdf5_files_after_training

when we use callback 'checkpoint' via Keras during training, we expect only stored best weight files(h5/hdf5...). 
but checkpoint callback was saved each best weight files if better then the last weight files. after training, 
there are many files, and we don't wanna delete them by manual. this program can auto delete useless weight file and save history plot.
