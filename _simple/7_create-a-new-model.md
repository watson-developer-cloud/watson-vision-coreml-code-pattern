---
title: Creating a model
date: 2018-01-07
---

The next part of the process is creating your own custom visual recognition model. Please follow **only one** of the below steps, depending on which flavor of the workshop you are doing.

1. [7A -- Creating a model for the Connectors data](#7a)
2. [7B -- Creating a model for the Arduino data](#7b)
3. [7C -- Creating a model for your own data](#7c)

---

<a name="7a"></a>
## 7A -- Creating a model for the Connectors data

You can create a model by either going to assets and pressing **New visual recognition model** under **Visual recognition models**.

Or by pressing the **Add to project** dropdown from anywhere in your project and choosing **Visual recognition model**.

![](https://cdn-images-1.medium.com/max/6208/1*bFq2m7N_GV7ahJhb640WPw.png)

When you create a new model you should automatically be directed to the models training area.  If you need to find your way back to this page you can do so by navigating to your project *(Projects > My First Project)* then under the **Assets** tab click on your model under the **Visual recognition models** section.

![](https://cdn-images-1.medium.com/max/6208/1*wptStjboOq4k_9xrt5qeFA.png)

Create a new class for each *type* of connector.

![](https://cdn-images-1.medium.com/max/6208/1*-AJ7d3V8DNKCGDqB3Uww8Q.png)

Then drag and drop the zip files from the side panel onto the corresponding class.

![](https://cdn-images-1.medium.com/max/6208/1*icXxT4vrw9mZFQKgXY0pMA.png)

![](https://cdn-images-1.medium.com/max/6208/1*-7NPuCWFQFI30QXgvx4cgg.png)

After all your classes are complete, you are ready to train your model. Just press the **Train Model** button.

![](https://cdn-images-1.medium.com/max/6208/1*p1Q5JyTMQvUSa78Z1gtYhg.png)

---

<a name="7b"></a>
## 7B -- Creating a model for the Arduino data

You can create a model by either going to assets and pressing **New visual recognition model** under **Visual recognition models**.

Or by pressing the **Add to project** dropdown from anywhere in your project and choosing **Visual recognition model**.

![](assets/data_assets_add_model.png)

When you create a new model you should automatically be directed to the models training area.  If you need to find your way back to this page you can do so by navigating to your project *(Projects > My First Project)* then under the **Assets** tab click on your model under the **Visual recognition models** section.

![](assets/add_assets_screen.png)

Create a new class for each *type* of Arduino part. Specifically, create a class for "Mega", then "Uno", and finally create a "Negative" class.

![](assets/add_assets_screen_empty_classes.png)

Then drag and drop the zip files from the side panel onto the corresponding class.

![](assets/add_images_to_class.png)

![](assets/images_added_to_class.png)

After all your classes are complete, you are ready to train your model. Just press the **Train Model** button.

![](assets/train_model_part.png)

Repeat the above steps for the second model of Arduino faults. Specifically, create a class for "Capacitor Failed", then "Normal", and finally create a "Negative" class.

![](assets/train_model_fault.png)

---

<a name="7c"></a>
## 7C -- Creating a model for your own data

Follow the above steps, substituting your own classes and model(s) from the data you collected.

---

## After kicking off the training jobs (all workshop versions)

Training time can vary depending on the amount of training data. A good rule of thumb is a few seconds per image. Since we have a smaller number of images, we can expect the model to take about 5–10 minutes to train.

In the meantime we can start preparing the iOS app.
