# Blue-Render-Desk 

Plugins written with Python and Max Script automatically upload the scene to be rendered to the render farm, thanks to Blue Render Desk, after exporting it. Blue Render Desk finds your file to be rendered, finds the texture and similar files you used in the file and sends it to the render farm. All files are zipped to reduce the size of the file. Blue render desk receives the data from the render farm in real time and shows it to you. and it works in real time. After you log in, the desk automatically makes things easier with its auto login feature. You can see render jobs and uploaded files as a list in the render desk. It receives data from the gRPC service via API and runs.

# DevExpress Compunents 
The components used are Devexpress components and are of very high quality. These types of components are the ones chosen by large companies.

# Security 
For the security of files and data, Blue Render Farm itself has developed a special encrypt of data and uses these algorithms in both Blue Render Desk and Blue Render Farm.

# gRPC API Service
The reason I use gRPC is water. In render farms, it is possible for servers to run at once, for example, 1000 servers can suddenly run.
I set up a gRPC service to receive their data, analyze it well, and send it to both the website and window software. To speed things up

# Video
The processes in the video are a sample rendering process and are carried out thanks to the blue render desk.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/k3y5qdSlahw/0.jpg)](https://www.youtube.com/watch?v=k3y5qdSlahw)
