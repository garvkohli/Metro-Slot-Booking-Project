 A Slot booking App for the Delhi Metro for easy and safe travel post-Pandemic
 [***Deployment***](https://dmrc.herokuapp.com/)

---
### Requirements :
* NodeJS :  **v12.16.3**
* npm    :  **v6.14.4**
* MongoDB or an online Cluster on MongoDB
---

### How to run on Local System:
1-Clone the repo. /n
2-run the command to install all the dependencies required /n
npm i
3-Create a MonogDB Cluster and Paste its connection link into the ClusterURI variable in the config/default.json file.
Note : The default value will create a cluster itself but it requires mongoDB to be installed in the system prior to it.
4-Edit the values of Various other parameters in the config/default.json according to yourself.
5-Now run the command to start the server
node server
The App Shall now be running on PORT = 5555(default)
