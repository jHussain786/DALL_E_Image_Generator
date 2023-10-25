# DALL_E_Image_Generator

1. The project is created via Django framework.
2. It uses openai's Dall E for image generation
3. The openai Dall e model give response in the form url.
4. The get request to these endpoints returns images
5. These url are read by urllib pacage in python 
6. OpenCV is used to resize the image as openai are compitable with only a few sizes
7. Instructions to run the project:
    a. Open terminal and move into the folder containing manage.py file
    b. Run python manage.py runserver in terminal to run server
    c. Open any browser and type localhost:8000
    d. On front give prompt and number of images you want to generate against that prompt
    e. Each image can be download in of these sizes 1080 x 1080, 1080 x 1920 and 1200 x 628