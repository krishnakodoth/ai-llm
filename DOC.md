
[Installing Anaconda Distribution](https://www.anaconda.com/docs/getting-started/anaconda/install)

After installation Open Anaconda PowerShell

cd to the root project folder 
- C:\CodeBase\AI-LLM\ai-llm

Create anaconda environment
``` 
conda env create -f environment.yml
```

To activate the environment
```
conda activate <name of the env>
```
in this case env name is `llms` (As mentioned in the environment.yml)


To dectivate the environment
```
conda deactivate
```

To see the python version `python --version` - which will list the python version as per the environment.yml file

To open jupyter enviormrnt, execute the below command

```
jupyter lab
```