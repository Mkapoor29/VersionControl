Different version control systems available. 
* Subversion
* Perforce
* AWS Code Commit
* Mercurial
* Git


### TYPES OF VC

* CENTRALIZED VC
  * contain a server and a client.
  * The server contains the main repository that houses the full history of versions of the code base.
  *  Developers working on projects using a centralized system need to pull down the code from the server to their local machine.
  *  This gives the user their own working copy of the code base.
  *  The server holds the full history of changes.
  *  The client has the latest code, but every operation needs to have a connection to the server itself.
  *  In a centralized version control system, the server is the central copy of the project.
  *  After making changes to the code, the developer needs to push the changes to the central server so that other developers can see them.
  *  This essentially means that viewing the history of changes requires that you are connected to the server in order to retrieve and view them.
* DISTRIBUTED VC
  * You still need to pull code down from the server to view the latest changes.
  * The key difference is that every user is essentially a server and not a client.
  * This means that every time you pull down code from the distributed model, you have the entire history of changes on your local system.

### Advantages and disadvantages of CVCS
* considered easier to learn than their distributed counterparts.
* They also give more access controls to users.
* The disadvantage is that they can be slower given that you need to establish a connection to the server to perform any actions.

### Advantages and disadvantages of DVCS
* you don't need to be connected to the server to add your changes or view a file's history.
* It works as if you are actually connected to the server directly but on your own local machine.
* You only ever need to connect to the server to pull down the latest changes or to push your own changes.
* It essentially allows users to work in an offline state.
* Speed and performance are also better than its CVCS counterpart.
* DVCS is a key factor in improving developer operations and the software development life cycle.
