# RUN vs CMD vs ENTRYPOINT

What are the differences between these three options ?
- RUN: executes when BUILDING the image - building or running when the image is being built
- CMD & ENTRYPOINT: execute when the container starts

What is the difference between CMD and ENTRYPOINT ?
- ENTRYPOINT: determines the main process to run, so whatever we want that process ID number one to be, that's when we'll use entrypoint
- CMD: is like additional parameters we want to pass into ENTRYPOINT and we can override these.
