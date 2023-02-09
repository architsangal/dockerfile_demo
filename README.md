#copy_add

docker build -f Dockerfile -t copy_add:latest .

docker run -it --name copy_add_cnt copy_add:latest

#run

docker build -f Dockerfile1 -t run1:latest .
docker build -f Dockerfile1 -t runn:latest .

docker run -it --name run1_cnt run1:latest

#cmd_entrypnt

docker build -f Dockerfile -t cmd_entry:latest .

docker run -it --name cmd_cnt cmd_entry:latest
docker run -it --name cmd_cnt1 cmd_entry:latest biswa
