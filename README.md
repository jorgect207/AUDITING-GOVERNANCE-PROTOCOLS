# AUDITING-GOVERNANCE-PROTOCOLS

 Common vulnerabilitys in governance protocol, This repo is update just with finding that i found or i participate in a contest with it (mostly on code4arena)

 ### 📜 Disclaimer

Takes this vulnerabilitys or points to check to a guide when you are auditing governance protocol, there are a lot more complex vulnerabilitys in governance protocol that i dont write in this repo, Always do your on research.

 ### USER CAN VOTE SEVERAL TIMES DELEGATIN HIS VOTE TO A OTHER ADDRESS AND REDELEGATING AGAIN.
There are cases where protocols allow redelagate (delegate his votes to another address) his vote, if the protocol doesn´t have enough validation user can delegate his vote, vote with the delegatee address, redelegate to another address and vote again, and do this the times that he want.

### USER CAN NOT UNDELEGATE
The protocol have to ensure that the user can undelegate his votes at the time that he can (this depend on the logic of the protocol), sometimes user are unenable to undelegate his votes due errors in the logic or action that the delegatee (user who the votes was delegated) can perform to block a delegator (user who delegate his votes) to undelegate his votes.

### USER(DELEGATOR) CAN BE FRONT RUN
There are cases where the delegator can be front runt unable to withdraw his delegate votes.

### REMOVING GAUGE
Pay atention whit this function, Make a sure that user can recover his votes




 

