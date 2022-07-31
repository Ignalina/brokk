# Brokkr's baremetall pre-built-tools 
A fine Selection of various software that can be executed either within the container or pluck from the container directory /brokkr for a closer to the "metal" experience. 

## Currently included/built
| Software | Rhel8|Alpine3.16|Build| Description |Source|
|:---------|:-|:-|:-|------------:|:-| 
|trubka    |y|y|norm|Kafka client|https://github.com/xitonix/trubka|  
|pqrs     |y|y|norm|Rust Parquet tools|https://github.com/manojkarthick/pqrs|
|datafusion-cli |y|y|Nightly|Process |https://github.com/apache/arrow-datafusion| 
|tantivy-cli |y|y|norm|Text indexing |https://github.com/quickwit-oss/tantivy-cli| 

[Docker hub space](https://hub.docker.com/repository/docker/ignalina/brokkr)

## Plan to add
xnvme  
 

## Licenses:
All above tools are fetched from source at build time and their respective License applies for each of them.
Look up their respective license from their git/source or in this git repo under /licences

## Brokkr's software Criterion
* Near or baremetal such as Rust/C/C++/Golang  
* Not based on VM or interprenter  (Java/JS/Python) except languange bindings from those  
* Superb functionality  

In Norse mythology, Brokkr (Old Norse: [ˈbrokːz̠], "the one who works with metal fragments  ,https://en.wikipedia.org/wiki/Brokkr
![This is an image](https://upload.wikimedia.org/wikipedia/commons/4/4c/The_third_gift_—_an_enormous_hammer_by_Elmer_Boyd_Smith.jpg)

