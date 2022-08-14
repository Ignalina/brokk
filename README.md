# Brokkr's baremetall pre-built-tools 
A fine Selection of various software that can be executed either within the container or plucked out from the container directory /brokkr for a closer to the "metal" experience. 

# Why
I found myself recompiling some of these tools over and over for sometimes old/airgapped production system either for error search or single fix/demo/performance test. Now I'm adding software that I want to explore or utilize. 



# DISCLAIMER
DO NOT USE MY BUILDS FOR YOUR PRODUCTION· Altough the respective software project is the finest  of sorts , it doesnt mean my builds/build scripts make them justice. You must also check that respective License.

## Currently included/built 
| Software | Rhel7 | Rhel8|Alpine3.16|Build| Description |Source|
|:---------|:-|:-|:-|:-|------------:|:-| 
|trubka    |n|y|y|norm|Kafka client|https://github.com/xitonix/trubka|  
|pqrs     |n|y|y|norm|Rust Parquet tools|https://github.com/manojkarthick/pqrs|
|datafusion-cli |n|y|y|Nightly|Process |https://github.com/apache/arrow-datafusion| 
|tantivy-cli |n|y|y|norm|Text indexing |https://github.com/quickwit-oss/tantivy-cli| 

[Docker hub space](https://hub.docker.com/repository/docker/ignalina/brokkr)

## Plan to add
xnvme  
 

## Licenses:
All above tools are fetched from source at build time and their respective License applies for each of them.
Look up their respective license from their git/source or in this git repo under /licences. For non free Redhat/Rhel builds im using UBI which is/was most permissive.

## Brokkr's software Criteria
* Baremetal or nearmetal such as Rust/C/C++/Golang  , Not based on VM or interprenter  
* Single or minimal dependencies , the less the merrier 
* Superb functionality

# This means
* NO Java/RubJS/Python/perl except languange bindings (Callable from)  
* NO or minimal dependency on Kubernetes or OS distribution/package and its tools.  
* NO or not locked in dependencies on OS, Kubernetes,or cloud functionality (Bizzare yes reality 2022 for)  
* YES should depend on widely accessible hardware (Intel/AMD CPU i.e)  
* YES please depend upcoming superb performing hardware (NVME)


In Norse mythology, Brokkr (Old Norse: [ˈbrokːz̠], "the one who works with metal fragments  ,https://en.wikipedia.org/wiki/Brokkr
![This is an image](https://upload.wikimedia.org/wikipedia/commons/4/4c/The_third_gift_—_an_enormous_hammer_by_Elmer_Boyd_Smith.jpg)

