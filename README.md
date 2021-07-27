# This-Catgirl-Does-Not-Exist
AI generated anime illustrations using [StyleGAN2-ADA](https://github.com/NVlabs/stylegan2-ada-pytorch)! \
Site showcasing random generated results: https://edz543.github.io/This-Catgirl-Does-Not-Exist/

# Details
Trained on a custom dataset of >10k images for about 4 days on [Google Colab](https://research.google.com/colaboratory/) \
Data was scraped from the tag-based image archive Safebooru \
The model was transfer learned from the [anime portrait S2 model trained by Aaron Gokaslan](https://www.gwern.net/Faces#stylegan-2) to enhance a rare attribute (in this case, cat-like ears)

# Model Download
The site images and model are hosted on Amazon S3 \
You can download the custom model [here](https://catgirldataset.s3.amazonaws.com/network-snapshot-000000.pkl)
