### Static Docker  ###
### Thanks you Ko Phyo Min Htun ###

![alt text](./image.png "Static Website Deployment")

Content reference from [Stranger Things Wiki Page](https://strangerthings.fandom.com/wiki/Stranger_Things_Wiki)

#### Let's Build It!
* Download the source folder
    > #git clone https://github.com/th3lolipop/nginxstatic.git

* Build image from Dockerfile 
    > #docker build -t image_name . 

* Run static web content with docker run command 
    > #docker run -d -p 8080:8080 image_name 

* On Web Browser 
    > http://localhost:8080

