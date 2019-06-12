Predicting the potential maintenance opportunity of Machines

Problem Description
Predictive maintenance of machinery is very critical from both cost and safety perspectives. Cost of serving/replacing a perfectly working part can be significant and can add huge financial burden to manufacturers and customers besides causing machine down time. On the other hand, cost of notmaintaining a failed part can result in human safety disasters. Thus, predicting events related to maintenance based on past events till failure helps avoid breakdown and achieve full useful life and thus availability of systems. The data on failures or trends about degradation of a machine over time can help in predicting a potential failure based on patterns and helps estimate time to a failure based on the progression of identified faults. Working backwards the data can help develop early warning signals to plan for maintenance which includes corrective actions A locomotive manufacturing company observes failures in the engines of several locomotives of their fleet. The data captured through sensors and inspection of previous fleet is given. The data depicts the scheduled and unexpected services done for each machine component. Unexpected services include error, repair, replacement etc and related data is provided with time stamps. You are expected to create an analytical and modelling framework to predict the major possible future events/ action points for each MachineID ie., like any “ComponentRepair”(major), “ComponentReplacement”, “NoIssue” (Minor error or normal status) , in the next one month for each machine. 


About Data:
The data provides the information on the condition of the various components of the machine including the data collected through sensors. The data depicts the scheduled and unexpected services that took place for each machine as historical data.

Every single machine is observed at various time stamps, to record the details of its operating condition like any error, repair, scheduled maintenance, replacement etc for each component of that specific machine.

Objective:
You are expected to create an analytical and modelling framework to predict the future events/action points based on known past events/action points for each MachineID ie., what would be the possible major action point, like any “ComponentRepair”, “ComponentReplacement”, “NoIssue” ,in next one month for each machine. 



1. Train & Test Data:
• “Train.csv” & “Test.csv”
• These files consist of the MachineID & ActionPoint Which is the target attribute.
• Train.csv has the target attribute “ActionPoint” also, whereas Tes.csv doesn’t
have as it has to be predicted.

Note: the datasets cited below consists of the data related to train and test data MachineIDs
2. MachineDetails data :
• “MachinesDetails.csv”
• This file depicts the MachineID, model, it’s service period for both train and test
MachineIDs
3. Minor Error information:
• “ComplaintsLog.csv”
• This file consists of the details about minor errors that took place with each machine at
various time stamps. Machines are still operational though the errors occurred.
4. Different Services Details:
• “ComponentServiceLog.csv”
• This file depicts the timestamp, MachineID, ServiceType, ComponentAttended etc.
5. Replacement Details:
• “ComponentReplacementLog.csv”
• This file depicts the timestamp, MachineID and which component got replaced.
6. Operating Conditions Details:
• “OperatingConditionsData.csv”
• This file depicts the timestamp, MachineID, readings of different sensors at each point of
time.


Error Metric:
o “F1-statistic” for “ComponentReplacement” level of Target attribute as
error metric and tuned the model accordingly.


Refer to the PPT to view the visualizations, data insights, algorithms used to create various models along with results. 