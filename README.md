# gh-ost

- alter="noop", used for optimize table 
- alter="noop", where-str="id>5000";   optimize table also delete history data(id<=5000)



# example:
--where-str="id>5000"
--user=""
--password=""
--host="127.0.0.1"
--port="40001"
--database="testdb"
--table="test5"
--alter="noop"
--nice-ratio=0.1
--verbose
--assume-rbr
--postpone-cut-over-flag-file=/tmp/gh-ost.testdb.test2.postpone
--serve-socket-file=/tmp/gh-ost.testdb.test2.sock
--execute
--initially-drop-ghost-table
--initially-drop-old-table