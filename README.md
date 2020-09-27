# New_Workorder_alarm

When Covid forced us to work remotely, things in the facilities world got a bit slow. In order to keep track of my work, I wrote this program to notify me every time there was a new work order entered into the system. It queries the Maximo database for any work orders with the status of WAPPR, which means waiting for approval. When the work order is coded and moved along, the status is changed. If it finds new work orders, the program beeps to alert me that something is waiting.
