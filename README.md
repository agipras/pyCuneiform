# pyCuneiform

This project aims to read fragmented and unfragmented cuneiform characters. There are a lot of excavated cuneiform tablets nowadays, however sometime we saw from these tablets the characters are broken or fragmented eroded by the nature, making them hard to read.

In this project, we are trying to build a model to automatically guess the reading of the fragmented characters. In the first phase of our project, we use Cuneiform Noto Sans as the base dataset for the training. The extracted characters are then damaged intentionally with various form of damages.

## Dataset

In this repository, we put 2 kinds of dataset, the normal characters inside `A1_cuneiform_complete.zip` file and the fragmented characters inside the rest of zip files. The complete list of the characters can be found below.

- A1_cuneiform_complete.zip
- A2_cuneiform_fragments_1.zip
- A2_cuneiform_fragments_2.zip
- B1_test_triangle_middle.zip
- B2_test_half_and_quarter_middle.zip
- B3_test_triangle_middle_q.zip
- B4_test_middles.zip 

We also try to extend our project with various form of characters from the artifacts so that our model can read broader form of cuneiform characters.
