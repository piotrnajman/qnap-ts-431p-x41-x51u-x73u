## QNAP TS-431P-X41-X51U-X73U Template

__Zabbix 5.0LTS SNMP template for monitoring QNAP TS-431P / TS-x41 / TS-x51U / TS-x73U network storage devices.__

1. Items System
   - CPU Usage
   - Firmware upgrade 
   - Free memory
   - Memory usage
   - System temperature
   - Total memory
2. Volumes (discovery)
   - Item prototypes
     - Free size
     - Status
     - Total size
     - Used size
     - Usage
   - Trigger prototypes
     - Free space is critically low
     - Free spase is low
     - Not Ready status
     - Volume is full
   - Graph prototypes
     - Volume space
4. Hard disks (discovery)
   - Item prototypes
     - SMART status
     - Temperature
   - Trigger prototypes
     - SMART status isn't good
5. Fans (discovery)
   - Item prototypes
     - Speed
   - Trigger prototypes
     - Speed to low
6. Triggers
   - Firmware upgrade available
   - High CPU utilisation
   - High memory utilisation
7. Graphs
   - Resources Utilisation

