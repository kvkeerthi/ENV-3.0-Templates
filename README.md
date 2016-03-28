# Contrail Heat 3.0

# ENV Templates 

contrail-left-nw-policy.env   

          - Will allow to add NW Policy to the exiting Virtual Network

contrail-right-nw-policy.env  

          - Will allow to add NW Policy to the exiting Virtual Network

contrail-nw.env	             

          - Will allow to create Virtual Network

contrail-sc-v1.env            

          - Will create Service Template V1
          - Will create Service Instance
          - Will attach static route prefix

contrail-vm-sc-template-V2.env 

          - Will create 2 VM's using exiting Virtual Network
          - Will create Service Template V2
          - Will create Port Tuple based SI
                                 
contrail-vm-si-left-subnet-V2.env 

          - Will create 2 VM's using exiting Virtual Network and bringing up left port on a specific Subnet using UUID
          - Will create Service Template V2
          - Will create Port Tuple based SI

contrail-vm-si-v2-template.env  

          - Will create a VM using exiting Virtual Network
          - Will create Service Template V2
          - Will create Port Tuple based SI

contrail-vn-policy-v0.1.env     

          - Will create a NW policy

vn-with-policy.env              

          - Will create Virtual Network with Network Policy

contrail-vm-port-mirror.env

          - Will creates 2 nova VM using existing VN’s 
          - Will enables port mirroring for left interface to and existing analyzer as SI with shared IP

contrail-mirror-sc-template-V2.env

          - Will creates nova vm using existing VN's
          - Will creates v2 template
          - Will creates SI with shared IP using v2 Template for Left interface
