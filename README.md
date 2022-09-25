# DepressoMeter  


The project is deployed on Docker. Use following commands to run it:  

### Building Image:  

1. ```docker image build -t depressometer .```  

### Run the container  

1. ```docker run -p 5000:5000 -d depressometer```  


## Using `docker-compose`:  

The appliction can be run just using the single commnd as well with the help of `docker-compose.yml`, as given below:  

```docker-compose up```  

---  



\* Use [this source](https://stackoverflow.com/questions/32302379/could-not-find-a-version-that-satisfies-the-requirement-package) to generate the `requirements.txt`.  