
# common pattern:

  - set the scope: asstes,policies,regulations,...
  - anayze target: via dfd
  - identify threates
  - rate threats

![image](https://user-images.githubusercontent.com/72389059/209300302-6927e6ea-08b5-4143-b4ec-7c6f1b948ca2.png)

`decide about level of details -> make a list -> document in scope and out of scope`


![image](https://user-images.githubusercontent.com/72389059/209307600-60cd47ed-d96a-46fd-bc7d-14d4f4c5ab67.png)
![image](https://user-images.githubusercontent.com/72389059/209307642-c155d1ad-b3ac-491f-9454-2f03da25be9c.png)

# DFD:


` dfd : shows how system works , problems follow data , simple , can be reused for docs `

![image](https://user-images.githubusercontent.com/72389059/209309006-dfd9e15d-63c0-417e-8667-2649c1da3abf.png)

---
![image](https://user-images.githubusercontent.com/72389059/209308454-e0819477-6413-4d12-a0c4-d778f52ce419.png)
  - web app
  - database not  the data itself
---
![image](https://user-images.githubusercontent.com/72389059/209308577-767ad81a-11a4-499b-8ae1-e916e1b188a4.png)

  - retrive data from some where
---
![image](https://user-images.githubusercontent.com/72389059/209308668-7c13068f-254b-4432-8e45-f1ebaa888d1e.png)

  - user data 
---
![image](https://user-images.githubusercontent.com/72389059/209308706-493d1e48-7c73-4c27-91f3-d510e4889854.png)

  - out of our control
---
![image](https://user-images.githubusercontent.com/72389059/209308751-d6af29cd-d43f-4612-a5db-fca16b4ff0a1.png)
 
 - entites with  diffrent permissions


# Decompose the app :

`security  profile: a statement of how the application handels various security-sensitive areas`

*write a  security profile*

```
- input validation
- authentication
- authorization
- configuration managment
- senstive data
- session management
- cryptography 
- parameter manipultaion (HTTP headers , cookies ,form filed,...)
- exception managmant
- auditing and logging
- ...
```
# identiying and documenting THREATS

**STRIDE**
6 classes:
  - spoofing : pretend to be someone else
  - tampering : modifing something to break integrity
  - repudiation : claim you didn't do something ( lack of audit)
  - informantion disclosure : provide information to someone how shouldn't see it ( get all email list)
  - denial of service : not allow others use the resource ( lack of throttling)
  - elevation of privilege : preforming action that they should not ( lack of authz)

**other techniques**
  - attack libraries : list of aviable attacks (MITRE CAPEC)
  - attack trees : goals and sub-goals of an attack
  - DESIST : like stride

**document the  threats**
```
- target :  web app
- attack technique : forging  a cookie
- countermeasure : use strong  value
```

# Rating:

available systems:
  -  DREAD
  -  OWASP  risk  rating methodology
  -  CVSS
--- 
**DREAD:**

![image](https://user-images.githubusercontent.com/72389059/209314264-2d3b71e6-12f0-495e-8ecf-471e15056af7.png)


