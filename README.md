# Exam_2420

# Author 
Dennis Phan  

## Answers

### Part 1 

Run the commands below to check for update and upgrade your software on Ubuntu OS

```
sudo apt update  
sudp apt upgrade 
```

### Part 2

Use 'vim <filename>
Use 'x' to delete single characters  
Use 'r' to replace single characters  
Use ':%s/before/after/g' where before is 'eco' and after is 'echo'   
  
![unedited](./Images/unedited_file.png)  
    
![edited](./Images/edited_file.png)  
  
### Part 3

![man](./Images/man_journalctl.png)   

![search](./Images/current.png)   

![b](./Images/b_option.png)  

![json](./Images/json.png)  

![output](./Images/output.png)  
  
![priority](./Images/priority.png)  
  
Final command  

![journal](./Images/command_journalctl.png)  
  
  
### Part 6
  
  ```
[Unit]
Description=starts 1 min from boot for find_user.service

[Timer]
OnBootSec=1min
OnUnitActiveSec=24h
Unit=find_user.service

[Install]
WantedBy=timers.target
```
  

  
 
  
 
