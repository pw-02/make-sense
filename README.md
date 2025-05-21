

<h1 align="center">HDFRS Labelling Tool</h1>

<p align="center">
    </br>
    <img width="100" src=".//public/favicon.png" alt="make sense logo">
    </br>
</p>
Leverage our bounding box labeling functionality to prepare a data set and use it to train your first state-of-the-art object detection model. 

## 💻 Local Setup

```bash
# clone repository
git clone https://github.com/pw-02/make-sense.git

# navigate to main dir
cd make-sense

# install dependencies
npm install

# serve with hot reload at localhost:3000
npm start
```
To ensure proper functionality of the application locally, npm `8.x.x` and node.js `v16.x.x` versions are required. 

## 🐳 Docker Setup

```bash
# Build Docker Image
docker build -t hdrfs-labelling -f docker/Dockerfile .

# Run Docker Image as Service
docker run -dit -p 3000:3000 --restart=always --name=hdrfs-labelling hdrfs-labelling

# Get Docker Container Logs
docker logs hdrfs-labelling

# Access hdrfs-labelling: http://localhost:3000/
```

## Optional: Pull and run the image from Docker Hub

```bash
# Pull the latest hdrfs-labelling image from Docker Hub
docker pull pwatters991/hdrfs-labelling:latest
# Run the pulled image as a detached container,
# mapping container port 3000 to host port 3000
docker run -dit -p 3000:3000 --restart=always --name=hdrfs-labelling pwatters991/hdrfs-labelling:latest
```




## 🔐 Privacy

We don't store your images, because we don't send them anywhere in the first place.

## 🚀 Tutorials

If you are just starting your adventure with deep learning and would like to learn and create something cool along the way, [makesense.ai][1] can help you with that. 


## 🏆 Contribution

<p align="center"> 
    <a href="https://github.com/SkalskiP/make-sense/graphs/contributors">
      <img src="https://contrib.rocks/image?repo=SkalskiP/make-sense" />
    </a>
</p>

## 💬 Citation

Please cite Make Sense in your publications if this is useful for your research. Here is an example BibTeX entry:

```BibTeX
@MISC{make-sense,
   author = {Piotr Skalski},
   title = {{Make Sense}},
   howpublished = "\url{https://github.com/SkalskiP/make-sense/}",
   year = {2019},
}
```

## 🪧 License

This project is licensed under the GPL-3.0 License - see the [LICENSE][2] file for details. Copyright &copy; 2019 Piotr Skalski.

[1]: http://makesense.ai
[2]: ./LICENSE
[3]: https://twitter.com/PiotrSkalski92
[4]: https://github.com/SkalskiP/make-sense/issues/16
[5]: https://gitter.im/make-sense-ai/community?utm_source=share-link&utm_medium=link&utm_campaign=share-link
[6]: https://github.com/SkalskiP/make-sense/wiki/Road-Map
[7]: https://github.com/SkalskiP/make-sense/wiki/Supported-Output-Formats
[8]: https://arxiv.org/abs/1512.02325
[9]: http://cocodataset.org
[10]: https://www.tensorflow.org/js
[11]: https://www.tensorflow.org/lite/models/pose_estimation/overview
[12]: https://towardsdatascience.com/chess-rolls-or-basketball-lets-create-a-custom-object-detection-model-ef53028eac7d
[13]: https://github.com/SkalskiP/ILearnDeepLearning.py/tree/master/02_data_science_toolkit/02_yolo_object_detection
[14]: https://skalskip.github.io/make-sense/
[15]: https://github.com/SkalskiP/make-sense/issues
[16]: https://github.com/ultralytics/yolov5
[17]: https://github.com/SkalskiP/yolov5js
[18]: https://github.com/SkalskiP/yolov5js-zoo
[19]: https://github.com/ultralytics/yolov5/blob/master/export.py
