# lab3-binaryCalculator

here is the video link:
https://youtu.be/Ix2tSyZ20iE

answer to discussion questions:
- I learned what docker and kubernetes was and how to use them, creating container images, pushing them, using cloud services, a little bit about dns. but almost all of that had to be learned on my own with help from friends or ChatGPT, I wish the lectures had covered at least some of this.
- advantages vs disadvantages: docker lets you containerize code which makes things like dependancies and version control really nice. but for a project like this where there were no versions, we had no idea what we were doing, and docker was poorly explained, it was really hard to try and figure out what to do and how to do it and why you were doing it. tldr: good if you know what you're doing

  instructions:
  - git clone the code
  - mvn package
  - do the artifact registry stuff
  - docker build the thing
  - docker push the thing
  - kubectl create deployment
  - kubectl expose deployment
