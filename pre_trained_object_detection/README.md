# TensorFlow Object Detection - *WIP*

## Status:
- [x] - Code development and test
-  [x] - Environment Variable files 
-  [x] - Dockerfile
-  [ ] - Instruction documents


### Setup:

```
git clone https://github.com/jasmeetsb/ml_demos.git
```

**Setup:**
```
  pip install -r requirements.txt
```

  OR

```
  conda env create --name {Environment_Name} --file conda-env.txt 
```

**Docker Container:**

```
 git clone {repository_url}
 cd into the demo folder with Dockefile
 docker build . -t obj_detection_trained
 docker run --name object_detection -p 3389:3389 obj_detection
```
