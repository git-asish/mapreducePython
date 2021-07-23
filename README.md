# mapreducePython
getting started with Map-Reduce in python


#if using HDP sandbox, run below command to excute the map-reduce job

hadoop jar /usr/hdp/current/hadoop-mapreduce-client/hadoop-streaming.jar \
-input  <input_text_file_path_in_hdfs> \
-output <output_directory_path_in_hdfs> \
-mapper <mapper_script_name> \
-reducer <reducer_script_name> \
-file <mapper_script_file_path_in_local> \
-file <reducer_script_file_path_in_local> 