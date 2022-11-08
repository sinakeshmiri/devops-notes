
# registry:
![image](https://user-images.githubusercontent.com/72389059/200490071-2d6e426e-eef6-4037-9fd9-0cfa55e588cf.png)

# arch:
![image](https://user-images.githubusercontent.com/72389059/200495497-33b60de2-0fc7-4c82-900d-05d78ba73760.png)


# container issue:

‍‍`deterministic system is a system in which no randomness is involved in the development of future states of the system.`

*sample dockerfile*


![image](https://user-images.githubusercontent.com/72389059/200500410-405d1013-336f-4821-8306-890fd0f344d0.png)

Deterministic Images?
  - Base image ubuntu:latest could be changed between builds
  - ubuntu:14.04 could also be changed due to patching
  - apt-get (curl, wget..) does not guarantee identical packages
  - ADD depends on the build time environment to add files

***harbor solution:***
![image](https://user-images.githubusercontent.com/72389059/200501297-f4b42e76-4aa4-4682-b220-46cf344df648.png)


source:  https://www.youtube.com/watch?v=Rs3zByxI8aY
https://www.cncf.io/wp-content/uploads/2020/08/harbor-cncf-webinar-1.pdf
