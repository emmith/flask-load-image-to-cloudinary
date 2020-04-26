Cloudinary Flask sample project
===============================

A simple Flask application that performs image upload and generates on the transformations of the uploaded image.一个简单的falsk应用，上传图片到cloudinary并获得图片的https链接。

## Installing and running

1. Install [Python](http://www.python.org/getit/)   
2. Install [Cloudinary python egg](https://github.com/cloudinary/pycloudinary#setup)  
    `pip install cloudinaty`
3. Get [a cloudinary account](https://cloudinary.com/users/register/free)
4. Copy the `cloudinary configuration` environment variables from the [Management Console](https://cloudinary.com/console):
5. Add the cloudinary configuration to the app.py file as following:

		# Cloudinary Configuration:
		cloudinary.config(cloud_name='your cloudname', api_key='your api key',
		                  api_secret='your api secret')

1. Run the server:

        $ python app.py
1. Browse to http://127.0.0.1:5000/
![](https://res.cloudinary.com/emmith/image/upload/v1587870424/ml6zh4p5a8y4hamk9jso.jpg )

Good luck!


## thanks
[dr-montasir/flask-cloudinary](https://github.com/dr-montasir/flask-cloudinary)