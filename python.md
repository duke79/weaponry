# [Python](https://www.tutorialspoint.com/python/)

logging
```python
logging.basicConfig(level=logging.WARNING) # This has to be called, for unknown reasons
logging.getLogger().setLevel(logging.INFO) # INFO only works once basicConfig is set
log = logging.getLogger(__name__)
log.info("hey there!")
```

environment
```python
os.environ["key"] = "val"
```

path
```python
path = os.path.join("a", "b") # Join paths
if not os.path.exists(path):  # Check if the file/dir exists
    os.makedirs(path)         # Create dirs
path = os.path.abspath(path) # Absolute path of file/dir
for file in os.listdir(path): # List files in dir    
    filename = os.path.basename(file) # Absolute path of file/dir
    filename_no_ext = os.path.splitext(filename)[0] # Filename without extension
    os.remove(os.path.join(path, file)) # Detele the file
```

subprocess
```python
process = subprocess.Popen(command, shell=True,
                                   stdout=subprocess.PIPE,
                                   stderr=subprocess.PIPE)
# wait for the process to terminate
for line in process.stdout:
    print(line)
errcode = process.returncode
```

#### [decorators](https://github.com/lord63/awesome-python-decorator)
[@property](https://www.programiz.com/python-programming/property)

[type checking?](https://stackoverflow.com/questions/35230635/type-hinting-in-python-2)

[to_explore](https://www.codingame.com/playgrounds/500/advanced-python-features)  
[check glossary](https://docs.python.org/2/glossary.html#term-duck-typing)
