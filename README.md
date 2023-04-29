
## AWS SageMaker

Amazon SageMaker is a fully managed machine learning service. With SageMaker, data scientists and developers can quickly and easily build and train machine learning models, and then directly deploy them into a production-ready hosted environment. It provides an integrated Jupyter authoring notebook instance for easy access to your data sources for exploration and analysis, so you don't have to manage servers. It also provides common machine learning algorithms that are optimized to run efficiently against extremely large data in a distributed environment. With native support for bring-your-own-algorithms and frameworks, SageMaker offers flexible distributed training options that adjust to your specific workflows. Deploy a model into a secure and scalable environment by launching it with a few clicks from SageMaker Studio or the SageMaker console [read more here](https://aws.amazon.com/sagemaker/) or [here](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html). ň

## Lets get started with notebook instance

You are probably familiar with jupyter noteeboks. If not Jupyter Notebook is an open-source web application that allows you to create and share documents containing live code, equations, visualizations, and narrative text. It supports many programming languages, including Python, R, Julia, and others, and allows you to combine code, text, and multimedia elements in a single document. 

Pick Amazon SageMaker from services on aws. You can ither use Amazon SageMaker Studio or Notebook instance to build your code. First, select the option "Notebook instance" from the menu, within which we will create a new jupiter notebook. 

1. Click on "Create notebook instance"
2. Give a notebook a name (e.g StartingWithML)
3. Select instance type "ml.t2.medium"
4. Leave other options as defualt and select "create notebook instance"

It will take some time to launch notebook instances. Once it showed status as "InService" you can click on "Open jupyter" option which will launched a new jupyter notebook instance. Create new python script by clicking on new->conda_python3. You can also use upload button to upload existing files from your computer. Play a bit with your fresh notebook before next step. Dont forget to add screenshots from your path into readme!

![Take some photo](gifs/giphy.gif)

## Build machine learning model
