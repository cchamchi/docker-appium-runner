# docker-appium-runner



docker build -t dockerrunner:0.1 .


sudo docker run -it --privileged -v /dev/bus/usb:/dev/bus/usb dockerrunner:0.1 /root/testskeleton/entry_point.sh
