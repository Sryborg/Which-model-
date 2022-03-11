# Which model should I use?
 
TL;DR;
 
- Tabular Data: XGBoost/LightGBM/RF
- Image Data: ResNet/EffNet
- Text Data: RoBERTa
- Audio Data: ResNet/EffNet
- Time series Data: XGBoost/LightGBM/RF
<hr>
 
Its been a while since I have been training ML/DL models and then I found [this tweet](https://twitter.com/marktenenholtz/status/1501905740813848582?t=P4VjLWug5yUcSG6sKhB5mQ&s=08) and I couldn't agree more!
 
For a lot of models/algorithms it is extremely difficult to tune them, sometimes its difficult to get results out of them.
 
The following is a list of the best models for each type of data
 
### Tabular data: XGBoost/LightGBM/RF
 
To most, no surprise here.
 
To everyone else, ensemble tree-based models are by far the best plug-and-play tabular models.
 
### Image Data: ResNet/EffNet
ResNet18 and EffNet-B0 are small, quick models that are effective for nearly any type of image data.
 
The best part?
 
Once you've squeezed all the juice out of those, you can scale up to their bigger versions and almost always get better accuracy.
 
### Text data: RoBERTa
 
I love starting text problems with a DistilRoBERTa model.
 
Sometimes, the combination of speed and accuracy is exactly what you need.
 
### Audio data: ResNet/EffNet
 
That's right -- image models for audio data.
 
My favourite way of starting audio problems is converting the audio to a spectrogram and throwing an image model at it. Don't believe? [have a look](https://github.com/Sryborg/make_some_noise) at my repo here.
 
Give it a shot!
 
### Time series data: XGBoost/LightGBM/RF
 
This I am yet to verify, but sounds like an interesting approach
