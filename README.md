Starter for deploying fast.ai models on Render
This repo can be used as a starting point to deploy fast.ai models on Render.

The sample app described here is up at https://fastai-v3.onrender.com. Test it out with bear images!

You can test your changes locally by installing Docker and using the following command:

docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use Render's fast.ai forum thread for questions and support.

