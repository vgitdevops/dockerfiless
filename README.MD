### FROM 
FROM  is the first Instruction in the dockerfiles concept

### RUN
RUN  is used for any packages installations

### CMD
CMD runs at the time of container creation. It should run in the foreground and also runs for infinite times.
In case - if we give multiple CMD instructions , only the latest will be considered.

### RUN - CMD
RUN instruction executes at the image creation
Image is a static file and Container is a runtime Instance of an image
IF we have one docker image, we can create and run any number of containers

### LABEL
LABEL instruction is used to give some metadata information. LABELS are the key - value pair very useful to filter the information from lakhs of records.
In any technology this LABEL concept is very useful.#   d o c k e r f i l e s  
 