# vPort

Objective - The main objective behind vPort is virtualisation of mobile phones. 
We used android virtual device as a virtual phone, whose screen can be seen through your physical phone.Not only that, when you perform any activity on your physical phone that will be recorded and send to your virtual phone and you will get the expected result of your activity.

Partitions :-

1. backend - Backend was built on Spring boot that basically make your pc a server, uses ADB (Android Debug Bridge) to interact with virtual device on the input provided from the physical device by frontend.

2. frontend - Frontend was built on Android Studio. It makes Http calls to the server, providing the inputs from the physical device.

Changes need to be done before running the project :-

1. There are some Http calls present in the frontend part which has hard coded URL's as an input. So, you need to set the URL's according to the IP assigned to your server.
2. You can also adjust the resolution part according to the resolution of your physical device.(optional)
