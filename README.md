# PatternRecognition_project


## Goal
- The Goal is to convey how and on what factors dynamic networks like instagram, facebook, linked_in suggest friends to a person.

## Explanation of project
- For example A, B, C are three people in a network.
- A is a friend to B and B is a friend to C. Here there is no connection between A and C but there is a common connection between A and C .i.e B.
- So a connection suggestion is sent to both A and C.

### Code flow
- First a directed graph is created using the given dataset.
- The directed graph is segregated into positive and negative samples. If the nodes are connected then we call them as positive samples, if not they are assumed as negative samples.
- Both positive and negative samples are appended to a saperate text files.
- Some of the necessary samples are extracted from the samples like jaccard coefficient, Adamic adar index, Common neighbour, Resource allocation index, Preferrential attachment index.
- Based on the above factors a social network decides to send suggestions or not. 

## Dependencies

- Install python
```sh
sudo apt update
sudo apt upgrade
sudo apt install python2.7
```
- As this project is based on graph theory install networkx python package using the following command

```sh
 pip install networkx
 ```
 
## Instructions

- Download the repo and simply run the main_code.py file

```sh
python main_code.py
```
- If you comfortable in using jupyter notebook there is .pynb file similar to maincode.py file
```sh
sudo jupyter notebook --allow-root
```
 
