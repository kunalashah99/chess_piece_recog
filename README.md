# Chess Piece Recognition

The goal of this project is to create a ML model in order to enable Baxter robot to recognise chess pieces.
For this a kaggle dataset was initially used. 
I decided to create my own dataset which would be more usefull for this paticular use case because of the following reasons:
- Watermarks and inconsistent number of pictures
- The existime framework of the Baxer robot enables the baxter to differenciate between already occupied squares and empty squares only from the top. hence creating a datset with pictures taken from the top would enable me to intentionally overfit the model.
