# assignment-1.4
QN 1.CHARACTERISTICS OF BIG DATA
1.Volume
The quantity of generated and stored data. The size of the data determines the value and potential insight- and whether it can actually be considered big data or not. 
The volume of data is usually interms of tera byte.
2.Velocity
In this context, the speed at which the data is generated and processed to meet the demands and challenges that lie in the path of growth and development.
Real time data which is highly volatile
3.Variety
heterogenous and unstructured that cant be handled by conventional RDBMS.
4.Veracity
Trustworthiness of data in terms  of reliability and  accuracy.
5.Value
In this context ,Data must be capable of conversion into a value that can be used for analysis


  QN 2.The possible solutions to handle Big data.
  1.SCALE UP
  2.SCALE OUT
SCALE UP
  1 Increase the configuration of a single system, like disk capacity, RAM, data transfer 
  2 Relatively cheap
  3 Less reliable
  SCALE OUT
  1 Use multiple commodity (economical) machines and distribute the load of storage/processing
  2 economical
  3 but need coordination among distributed system.
 
 QN 3. differences between scaling up and scaling out.
 Costs Scale up adds capacity but not the controller or infrastructure costs.  If the measure is dollar per GB, scale-up will be less expensive.

Capacity. Either solution can meet capacity requirements but there may be a limit on the scale-up capacity based on how much capacity or how many devices an individual storage controller can attach.

Performance. Scale out has the potential capability to aggregate IOPS and bandwidth of multiple storage controllers. Representing the nodes as a single system may introduce latency, but this is implementation specific. 

Management. Scale up would have a single storage system management characterization. Scale-out systems typically have an aggregated management capability but there may be variations between vendor offerings. 

Complexity. Scale-up storage is expected to be simple, while scale-out systems may be more complex because they require elements to manage. 

Availability. Additional nodes should provide greater availability in case one element fails or goes out of service. This depends on the particular implementation.
