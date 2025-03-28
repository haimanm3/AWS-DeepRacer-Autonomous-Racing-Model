# 🏎️ AWS DeepRacer Autonomous Racing Model

Developed an AWS DeepRacer model using Python and the Proximal Policy Optimization (PPO) algorithm, leveraging TensorFlow to train and fine-tune a deep reinforcement learning model. Designed a custom reward function and optimized hyperparameters to improve policy learning and navigation performance. Utilized AWS infrastructure for scalable training and deployment.

---

![AWS](https://img.shields.io/badge/Built%20With-AWS-orange)
![Reinforcement Learning](https://img.shields.io/badge/Reinforcement%20Learning-PPO-blue)
![TensorFlow](https://img.shields.io/badge/Powered%20By-TensorFlow-brightgreen)
![Status](https://img.shields.io/badge/Status-Always_Improving-yellow)

---

## 🚀 Features

- **Custom Reward Function** – Designed to incentivize optimal racing strategies and improve lap times.
- **Hyperparameter Optimization** – Fine-tuned parameters to enhance model convergence and performance.
- **AWS Integration** – Leveraged AWS services for scalable training and deployment of the reinforcement learning model.
- **Simulation and Real-World Deployment** – Trained in a simulated environment with deployment capabilities to the AWS DeepRacer car for real-world testing.

---

## 🛠️ Technologies Used

| Component                | Technology                                      |
|--------------------------|-------------------------------------------------|
| Programming Language     | Python                                          |
| Machine Learning Library | TensorFlow                                      |
| Algorithm                | Proximal Policy Optimization (PPO)              |
| Cloud Services           | AWS SageMaker, AWS RoboMaker, Amazon S3         |
| Deployment               | AWS DeepRacer Console                           |

---

## ▶️ How to Use

### Prerequisites

- **AWS Account** – Access to AWS services such as SageMaker, RoboMaker, and the DeepRacer console.
- **AWS DeepRacer Vehicle** – Optional, for deploying and testing the model in a physical environment.

### Training the Model

1. **Access AWS DeepRacer Console**: Navigate to the AWS DeepRacer console to create and manage your models.

2. **Define the Reward Function**: Utilize the custom reward function provided in the `notebooks/aws_deepracer_part_2.ipynb` notebook to guide the agent's learning process.

3. **Configure Hyperparameters**: Set the hyperparameters as detailed in the notebook to optimize training performance.

4. **Initiate Training**: Start the training job in the AWS DeepRacer console, monitoring progress and performance metrics.

### Evaluating and Deploying the Model

1. **Evaluate Performance**: After training, assess the model's performance within the simulated environment provided by AWS RoboMaker.

2. **Download the Model**: Once satisfied with the performance, download the trained model files.

3. **Deploy to AWS DeepRacer Vehicle**: Upload the model to the physical AWS DeepRacer car for real-world testing and validation.

---

## 🎥 Demo

[![Watch the AWS DeepRacer Demo](aws%20deepracer%20part%202/demo-thumbnail.png)](aws%20deepracer%20part%202/aws%20deepracer%20part%202.mp4)

> Click the image above to watch a short demonstration of the AWS DeepRacer model navigating the track.


## 🙌 Acknowledgments

- **AWS DeepRacer Community** – For resources and support in developing and refining reinforcement learning models.
- **OpenAI** – For advancements in reinforcement learning algorithms, including the development of PPO.
- **TensorFlow** – For providing a robust platform for implementing and training deep learning models.
- **AWS Educate Program** – For access to cloud resources and services that facilitated the development of this project.
