# Oracle_Tablescpaces_Scripts
Tablescpaces_Scripts

### Tablespaces et segments d'une Base de données Oracle
Une base peut être décomposée en tablespaces : partitions logiques contenant un ou plusieurs fichiers.
Un fichier appartient à 1 et 1 seul tablespace.
Un tablespace peut s'étendre soit par ajout (on-line) d'un fichier, soit par auto-extension DU fichier du
tablespace.
Par défaut il existe toujours un tablespace baptisé SYSTEM qui contient le dictionnaire de données et
le rollback segment SYSTEM (dans le cas ou il n'existe pas d'UNDO tablespace).
On peut également stocker les datas et les index dans ce même tablespace, et obtenir ainsi une base
minimale peu structurée, peu performante et peu sécurisée :
![image](https://user-images.githubusercontent.com/101791324/204169989-18d80ba0-9cdb-4815-84a2-6ae13512c029.png)
CREATE TABLESPACE 👍 
![create table](https://user-images.githubusercontent.com/101791324/204170004-9ac2b9a5-435a-412d-ae0e-f62413f9f7f5.PNG)
### **Update Tablespace by adding  a new file** 
![modifier_ajou_file](https://user-images.githubusercontent.com/101791324/204170119-54b85920-26e4-43e0-8041-c0a090a03d0d.PNG)
### **Add file Auto-extensible**
![Auo_extend_on](https://user-images.githubusercontent.com/101791324/204170168-8392cce9-f5a4-4516-b959-696e9b17a599.PNG)
### **READ  AND Write tablespaces**
![read_write](https://user-images.githubusercontent.com/101791324/204170252-3dfc3f2a-136b-4503-acf6-3b4e690dbf11.PNG)
### **Temporary Tablespace**
![image](https://user-images.githubusercontent.com/101791324/204170288-b0c68bdc-9f03-4e7c-8ff1-d8eb3ce67edb.png)
### **TABLESPACE OFFLINE :**
![image](https://user-images.githubusercontent.com/101791324/204170353-f404787f-9db6-4e37-81e2-0b9f5228ed3e.png)
**### Tablespace ONLINE :**
![image](https://user-images.githubusercontent.com/101791324/204170370-3c14fb62-359a-4edf-b0dc-508700727548.png)
### **Drop Tablespace**
![image](https://user-images.githubusercontent.com/101791324/204170406-1f1197a7-ccfb-49de-9d31-4079600e557b.png)







