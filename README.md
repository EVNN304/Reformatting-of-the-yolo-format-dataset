# Reformatting-of-the-yolo-format-dataset
This repository helps to transform your dataset to a different dimension of the input layer of the yolo neural network
1. In the first position of the Rebild_Data class, write the path with the dataset
2. In the second position, write the path where the converted dataset will be saved
3. In the third position, write the directory where unsorted dataset files will be mixed
4 and 5. write the desired size for which the dataset is reformatted

In the set_pix_x_indent and set_pix_y_indent methods of the Rebild_Data class, specify the required x and y indents so that the converted box does not go beyond them

Specify the offset from the center in the set_x_rand_left, set_x_rand_right, set_y_rand_left, set_y_rand_right methods of the Rebild_Data class
