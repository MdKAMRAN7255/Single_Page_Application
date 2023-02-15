# Single_page_application

I have completed **Single Page Application** which contains four tabs Home, work (in which i have Use Image Slider), Blog, About.

This is the work tab in which I used image slider which is not in demo website i added it by myself because it is mentioned in LMS.
![Screenshot from 2023-02-15 13-41-25](https://user-images.githubusercontent.com/122250114/218970386-56e3192b-0581-4f0e-9c60-cd0fd5430a97.png)

In About page I used scrolltoview, so that if I click on any of the sidebar option like (about, modus operandi, experience, etc.) the page will scroll down to partiular section of the page.
<img src="https://github.com/MdKAMRAN7255/SPA_practise/blob/fa43aadf4cf9415a1635a8970deb1b03e5f10685/Screenshot%20from%202023-02-15%2013-56-25.png">


I used haschange method and location.hash method to in javascript to make single page application

By default location.hash point to home page that is **Alex Turnwall** page.

As haschange is call whenever we click on anchor tag and location.hash will get that url of anchor tag. so apart navbar's anchor tag all the anchor tag is blank. so if we click on any other anchor tag it will redirect to home page because bydeafult location.hash will point to home page.
<img src="https://github.com/MdKAMRAN7255/SPA_practise/blob/fa43aadf4cf9415a1635a8970deb1b03e5f10685/Screenshot%20from%202023-02-15%2014-44-09.png">

As if(!location.hash) is empty it will point to the home page.

I have also included css on anchor tag like before hover image tag will be look like this...
<img src="https://github.com/MdKAMRAN7255/SPA_practise/blob/fa43aadf4cf9415a1635a8970deb1b03e5f10685/Screenshot%20from%202023-02-15%2014-48-45.png">

And after hover it will be look like this with transition effect ...
<img src="https://github.com/MdKAMRAN7255/SPA_practise/blob/fa43aadf4cf9415a1635a8970deb1b03e5f10685/Screenshot%20from%202023-02-15%2014-51-12.png">

I also apply grey-scale effect at work page in the last-second section so that it will black & white first and after hover it will change to color.
<img src="https://github.com/dipak2811/testing/blob/1d29b36b9b020b153e2399a484b0b29061aa83a1/Screenshot%20from%202023-02-15%2015-29-19.png">
Just like here,I have hover on third div that's why it is in color and all the other div in black&white.

I have also added effect on navbar such that if we scrolldown navbar is not visible but if we scrollup navbar is visible.

And I have used semantic element such as for image I use figure tag and for paragraph I use article tag and header and footer tag also.
By default in bootstrap section tag is used in class. so I have not used section tag separately.
