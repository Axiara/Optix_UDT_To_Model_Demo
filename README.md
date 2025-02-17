# Optix_UDT_To_Model_Demo
Demo using a PLC UDT as a Model For a Datagrid / Listbox / Combo Box in FT Optix

-The Modal property of Data Grids, List Boxes, and Comboboxes do not directly support a UDT array from the PLC.
-The lightweight Netlogic script in this example converts the UDT array into a object model that can be used in Optix.
-Models generated directly reference the the PLC tags with node pointers, they don't copy the values. So updates to variables are fast and are bidirectional.

**To Use**

-Add the UDT Model Builder to the Data Grid

![image](https://github.com/user-attachments/assets/11d6182b-dc4c-47e2-acc7-59fde3c26de1)


-PLC tag for the UDT Array is linked to the TagArray Variable of the Netlogic Object
![image](https://github.com/user-attachments/assets/8abdf775-6c37-41d6-8fb1-26a57107fc14)


-Then, the Model of the DataGrid is linked to the GridModel variable of the Netlogic object
![image](https://github.com/user-attachments/assets/d59b74d1-9138-454c-a76c-3e8b8aecdbf1)


-Attached is the sample Optix program with a sample PLC program that pairs with the demo. Configure the comms driver in Optix and go online with the plc to see it in action!

![image](https://github.com/user-attachments/assets/5d5ad579-dc00-4a16-8e9c-180fde88217c)

![image](https://github.com/user-attachments/assets/db0490da-2497-4f86-8dd8-e4c6b5effc9b)

![image](https://github.com/user-attachments/assets/714fcfa5-e8e8-471f-a054-78d08d3dd6d9)



