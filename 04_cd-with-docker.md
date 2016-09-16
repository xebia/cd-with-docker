<!-- .slide: data-background="#6B205E" -->
#Continuous Delivery with #Docker

!SUB
# Docker workflow

- Build, Ship, Run

<center><div style="width: 75%; height: auto;"><img src="img/docker-basic-components.png"/></div></center>

!NOTE
No unit tests (for now)
No deployment to production (for now)

!SUB
Explain why Docker is a good fit for Continuous Delivery

# Docker advantages
for
# Continuous Delivery

!SUB
## Faster
- Slow one-time events happen only once on _image_ creation, not on _instance_ creation
- Creating instances is fast/cheap

!NOTE
One-time example initialisation of the app has to happen just once. Fort example for test and production, same artifact is started which had it's initialization done @ build time

!SUB
## Better
- Same images used for development and production
- Isolation
- Consistent and reproducible results
- Portable/host-independent
- Scalability

!SUB
## And more:
- Encourages collaboration between Dev and Ops
- Version control of your Docker images
- Share your images using the Docker Hub


!SUB
Explain how/where we're going to use Docker to create a CD pipeline

# Continuous Delivery Pipeline

with

![Docker logo](img/docker-logo-no-text.png) <!-- .element: class="noborder" -->

!SLIDE
<!-- .slide: data-background="#6B205E" -->
# Exercises

!SUB
# Exercises to create parts of the pipeline here?

!SUB
# Exercises to create a complete pipeline here?