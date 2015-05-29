# StudyNote
```
cd $KAFKA_HOME
bin/kafka-run-class.sh kafka.tools.ConsumerOffsetChecker --group $group --zkconnect $zookeeper_qurom --topic $topic

Group           Topic                          Pid Offset          logSize         Lag             Owner
hbase.register  regservice_register            0   54832934        54991706        158772          hbase.register_pa9.et2-1432276263755-72dba4de-0
hbase.register  regservice_register            1   54234235        54390860        156625          hbase.register_pa9.et2-1432276263755-72dba4de-0
hbase.register  regservice_register            2   54183999        54332829        148830          hbase.register_pa9.et2-1432276263755-72dba4de-1
hbase.register  regservice_register            3   54597971        54754927        156956          hbase.register_pa9.et2-1432276263755-72dba4de-1
hbase.register  regservice_register            4   54180114        54324350        144236          hbase.register_pa9.et2-1432276263755-72dba4de-2
hbase.register  regservice_register            5   54619896        54771490        151594          hbase.register_pa9.et2-1432276263755-72dba4de-2
hbase.register  regservice_register            6   54225082        54379197        154115          hbase.register_pa9.et2-1432276263755-72dba4de-3
hbase.register  regservice_register            7   54110222        54265687        155465          hbase.register_pa9.et2-1432276263755-72dba4de-3
hbase.register  regservice_register            8   54227126        54380862        153736          hbase.register_pa9.et2-1432276263755-72dba4de-4
hbase.register  regservice_register            9   54274212        54424862        150650          hbase.register_pa9.et2-1432276263755-72dba4de-4
hbase.register  regservice_register            10  54244742        54399167        154425          hbase.register_pa9.et2-1432276263755-72dba4de-5
hbase.register  regservice_register            11  54199072        54347985        148913          hbase.register_pa9.et2-1432276263755-72dba4de-5

```


