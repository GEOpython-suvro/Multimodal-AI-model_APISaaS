### **Train and Deploy a Multimodal AI Model- PyTorch, AWS, SageMaker, Next.js 15, React, Tailwind:** ###

We'll learn how to train and deploy a multimodal AI model from scratch using PyTorch. The model will accept a video as its input, and predict its sentiment and emotion. When training the model, you'll build features like text, video, and audio encoding, multimodal fusion, and emotion and sentiment classification. After training and deploying the model, you'll build a SaaS around your trained model, where users can run inference on their videos through your API. You'll set up invocation of the deployed model with SageMaker Endpoints, and manage the monthly quotas users have. The SaaS will be built with technologies such as Next.js, React, Tailwind, and Auth.js and is based off of the T3 Stack. You'll be able to build along with me from start to finish.


### **Features** ###
🎥 Video sentiment analysis
📺 Video frame extraction
🎙️ Audio feature extraction
📝 Text embedding with BERT
🔗 Multimodal fusion
📊 Emotion and sentiment classification
🚀 Model training and evaluation
📈 TensorBoard logging
🚀 AWS S3 for video storage
🤖 AWS SageMaker endpoint integration
🔐 User authentication with Auth.js
🔑 API key management
📊 Usage quota tracking
📈 Real-time analysis results
🎨 Modern UI with Tailwind CSS

### **💲Costs + How to follow along for free** ###
One full training job run costs ~15 USD. When deploying the endpoint it’s ~1.5 USD per hour of uptime. S3 is really cheap. IAM roles, users etc are free.

### **If you want to not use money:** ###
-Don’t create the S3 bucket
Then you also won’t need the EC2 instance for downloading the dataset
-Don’t start a training job, but download my provided model from Google Drive to play around with locally
-Don’t deploy the endpoint. When building the SaaS part, use the dummy data I write in the video before calling the actual endpoint
-You can look into using free tier instances from AWS, so you can play around AWS
-You can of course still follow the video, learn the concepts and code along
