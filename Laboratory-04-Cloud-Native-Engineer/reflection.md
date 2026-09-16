# Mission Reflection

This laboratory activity helped me learn more about the differences between Virtual Machines and Docker containers. A Virtual Machine requires a full operating system to run, which means it can take more time and computer resources. On the other hand, Docker containers are lightweight and faster because they share the host operating system and only include the application and its required files. In this activity, I was able to run an Nginx web server using only a few Docker commands.

I also learned that port mapping is necessary when accessing a web server inside a container. The command -p 8080:80 connects port 8080 from the host computer to port 80 inside the container. Because of this, the Nginx server can be opened using localhost:8080. Without port mapping, accessing the web server from the host computer would not be as straightforward.

Another important thing I learned is that using the docker rm command removes the container. Files or data that are stored only inside that container may also be lost. Because of this, important information should be saved using Docker volumes or other storage methods so the data can remain even after the container is deleted.

Containerization also helps improve the way developers and IT teams work together. Developers can create an application together with its needed dependencies, while IT teams can use the same container in different environments. This helps make application deployment more consistent and can reduce issues caused by differences between development and production systems. It also supports the DevOps process by allowing both teams to use a common deployment method.

Overall, this laboratory activity also helped me improve my GitHub portfolio. I am learning how to properly organize my activities, record the commands I used, include screenshots, and write reflections about what I learned. Through this, my portfolio becomes more organized and shows my progress in learning cloud computing and cloud-native technologies.

