## Fast.ai 
* TLDR: deep learning course using the [fastai](https://docs.fast.ai/) package
* [fastai website](https://www.fast.ai/)
* Not supported on Mac (read the docs). Did run some of the examples but training was going to take hours on the Mac CPU vs minutes on a GPU, so Mac is not feasible.
* Next version is https://github.com/fastai/fastai2

## In production
* Equivalent to Tensorflow serving but simpler -> https://github.com/developmentseed/fastai-serving
* Host apps on Render -> https://github.com/render-examples/fastai-v3
* [A production-grade Machine Learning API using Flask, Gunicorn, Nginx, and Docker](https://medium.com/technonerds/a-production-grade-machine-learning-api-using-flask-gunicorn-nginx-and-docker-part-1-49927238befb)

## Visual UI
* Visual UI adds a graphical interface to fastai allowing the user to quickly load, choose parameters, train and view results without the need to dig deep into the code.
* https://github.com/asvcode/Vision_UI

## course v3
* Course (v3) videos online late Jan 2019
Course components:
1. Seven [full video lessons](https://course.fast.ai/lessons/lessons.html) of a little over 2 hours each, plus two shorter introductory videos
2. A set of [detailed notebooks](https://github.com/fastai/course-v3) showing how to complete the steps demonstrated in each video.
3. The [forums](https://forums.fast.ai/), which should be your first step for asking questions not answered by the wiki or course notes.

## Book
* https://github.com/fastai/fastbook
* [On Amazon](https://www.amazon.co.uk/Deep-Learning-Coders-fastai-PyTorch/dp/1492045527/ref=sr_1_2?keywords=Deep+Learning+for+Coders+with+fastai+and+PyTorch&qid=1583046954&sr=8-2)

## Free GPU - Colab
* Free GPU (shared, not always available), but some setup of the env required for each notebook, and need to make data available.
* [Getting started with Colab and fast.ai](https://course-v3.fast.ai/start_colab.html) -> a little bit of prep is required before using each notebook. Use the Github repo to get the latest course notebooks entering the source repo as `fastai/course-v3` and in the first cell of a notebook run `!curl https://course-v3.fast.ai/setup/colab | bash`

## Paid GPU
* Overview of paid options -> https://course-v3.fast.ai/index.html
* I've been using Floydhub which has a nice ecosystem but isn't the cheapest, but hace nice ecosystem and UI, and good integration with the course, also pre-paid which is more reassuring ($1.20/hour + $9.00/month (100GB storage))
* Significantly cheaper checkout Onepanel $0.29 per hour + storage with fast.ai signup URL