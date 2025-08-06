# Docker & Containers - Notes

## What is Docker?  
- A platform to build, run, and share applications inside containers.  
- Helps developers package everything an app needs (code + dependencies + configs) in one place.  

---

## What is a Container?  
- A way to **package an application** with all necessary dependencies and configurations.  
- A **portable artifact** – easy to share and run on different environments (like other developers’ machines or servers).  
- Makes **development and deployment faster and more consistent**.  

---

## Where do Containers live?  
- Containers are stored in **Container Repositories** (special storage).  
- Can be **private** (internal company use) or **public** (like **Docker Hub**).  

---

## How Containers improved the development process?  
- Before containers, installing an app was different depending on the OS → many steps, more chances to break something.  
- With containers:  
  - No need to install dependencies directly on your OS.  
  - Container runs in its **own isolated environment**.  
  - You can download and run with **just one command**.  

  ## How Containers improved the deployment process?  
-----------------


- Layers of images
- Mostly Linux Base Image, because small in size
- Application image on top


Docker vs Virtual Machine

OS has two layers, Applications Layer and OS Kernel Layer, docker virtualizes the 'applications layers', VM has the app layers and os kernel layer 



