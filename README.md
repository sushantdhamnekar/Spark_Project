# Spark_Project
Spark Project

Installations: https://medium.freecodecamp.org/how-to-set-up-pyspark-for-your-jupyter-notebook-7399dd3cb389

Path setups:
# User specific aliases and functions
export SPARK_HOME=/usr/lib/spark-2.4.0-bin-hadoop2.7
export PATH=$PATH:/usr/lib/spark-2.4.0-bin-hadoop2.7/bin

export PYSPARK_DRIVER_PYTHON=jupyter
export PYSPARK_DRIVER_PYTHON_OPT='notebook'
export PYSPARK_PYTHON=python2
export PYTHONPATH=$SPARK_HOME/python:$PYTHONPATH

export JAVA_HOME=/usr/lib/jvm/java-8-oracle
export JRE_HOME=/usr/lib/jvm/java-8-oracle/jre
export PATH=$SPARK_HOME:$PATH:~/.local/bin:$JAVA_HOME/bin:$JAVA_HOME/jre/bin
