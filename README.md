# cs205youtubeteam.github.io
cs205_spring19_final_project
Dylan Randle, Filip Michalsky, Tommy Shay Hill, Paxton Maeder-York

Final project for CS205 - Youtube video classification at scale using distributed computing and bi-LSTM.

We propose Youtube video classification at scale, leveraging a dataset of over 8 million videos with high throughput computing and large data handling system design. The project requires training on terabytes of video and audio files to then predict a video type from several thousand labels. Our solution uses two bidirectional-LSTM networks, one for audio and one for video, trained on a spark based distributed file system enabled by Elephas: Distributed Deep Learning with Keras & Spark. The infrastructure used consists of a custom cluster of m4.xlarge instances on AWS using amazon machine images to spin-up compatible nodes. We found this approach produced reliable systemic performance and effective classification with our final model.
