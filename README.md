# gaustudio_0_main_requirements
## Main requirements

### 

Python >= 3.8
torch1.12.1+cu113 and torch2.0.1+cu118




# Folder requirement
- output_dir
    - cameras.json (necessary)
    - point_cloud 
        - iteration_xxxx
            - point_cloud.ply (necessary)
         


# Running the Mesh Extraction
## To extract a mesh from the input data, run the following command:
**Python:**
```markdown
gs-extract-mesh -m ./data/1750250955326095360_data/result -o ./output/1750250955326095360_data


# sample

**Python:**
```markdown
# This is Python code
def greet(name):
    print(f"Hello, {name}!")

greet("Jacky")
