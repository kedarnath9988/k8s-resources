# for the scereats we need to keep the value in the form of ENCODED FORMATE 
 echo admin | base64  -> commands to het the Encoded value of the user name 
 echo admin@123 |base64 -> commands to het the Encoded value of the user name 

 # Service -> to comunicate with one to another pod 
 

 # how can we access a container from the out side the K8s or internet 4
 Ans: by using the nodeport or loadbalaner 
    node port will open the perticuler port in the node with the help of the pubic ip of the perticular node and port 
    by using the loaddbalancer 
    direcctly we can acess the container by using loadbalancer DNS 