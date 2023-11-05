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

Note: DALL E work is still pending and we are waiting for DALL E 3 api release. 

# Working of image resize
1. The app will run and a resize button will be displayed on frontend.
2. It will take images from uploads folder and download these files into downloads folder
3. The output image format will always be in jpg