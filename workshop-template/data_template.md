# Ideas for replication materials
Your repository should include relevant information for a student to reproduce the workflow. This could mean including a folder with relevant replication data. Or it could mean providing other clear guildeines for accessing data, such as using API calls to ingest data directly into a code template. 
<br>

## A data folder
If you decide to include datasets for the student to use, please:
- Include a narrative description of each file's contents and where it fits in the workflow.
- Use descriptive file names (`data.csv` isn't particularly helpful, but `data_forbarchart.csv` might be more useful)
- Number files if they are meant to be used in a particular order
- Use relative path structures and project-oriented workflows when possible (e.g., building relative paths with 'here' in R, rather than less replicable tools like `setwd()`)
<br>

## Data from APIs
There are potential benefits to structuring your data pipeline around API calls rather than data stored in a directory structure. If you choose this route, please remember to:
- Explain how to create accounts and generate API keys
- Include some instruction on how to interpet the data structure 
- Give a few examples of how to write a query, with an eye toward explaining how a student can customize 
<br>

## Potentially useful reading
- [Trisovic, Ana, et al. (2022) A large-scale study on research code quality and execution. Scientific Data 9: 60](https://drive.google.com/file/d/137ig_nDWtXIVwsFRoDvxZgDV1TV8oAXf/view?usp=sharing)

