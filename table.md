| Number of Hidden Layers | Neurons in hidden layer | Lowest Test loss | Number of epochs trained | Notes                                         |
| ----------------------- | ----------------------- | ---------------- | ------------------------ | --------------------------------------------- |
| 1                       | 1                       | 0.443            | 166                      | Pretty much a linear                          |
| 1                       | 2                       | 0.270            | 49                       | Classification is a 2d space                  |
| 1                       | 3                       | 0.01             | 340                      | Classification is now a polygon               |
| 1                       | 4                       | 0.004            | 372                      | Also polygon                                  |
| Using more complex data |                         |                  |                          |                                               |
| 1                       | 4                       | 0.475            |                          |                                               |
| 2                       | 4,2                     | 0.472            |                          | Not much better and quickly starts to overfit |
| 2                       | 4,3                     | 0.475            |                          |                                               |
| 3                       | 4,3,2                   | 0.478            |                          |                                               |
| 5                       | 7,5,2                   | 0.200            |                          |                                               |