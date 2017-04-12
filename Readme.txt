Document author: Nikhilesh Kshirsagar

Following are the steps to run the Bully algorithm for election in distributed systems

- Transfer the file bullyLeaderElection.java to glados servers 

- Compile the file on the server using command
	java bullyLeaderElection.java

- Execute the file with following command 
	java bullyLeaderElection <server number> <leader number>

the server number is used as a ranking denomination in the algorithm and the leader number signifies the current leader of the distributed system.