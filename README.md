OttawaCityJobs
======================================================

Yet another city jobs scrapper

##Installation
		[sudo] pip install ottawacityjobs

##Usage

```python
import ottawacityjobs as p

results = p.get_website_content() #Retrieves the full jobs description
results  = p.get_jobs(results) #retrieve all the jobs title and their url
```

