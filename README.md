# nipolib-python
Nipo library for python


## sample

```console
import nipo 

#Create initial config 
nipo.CreateConfig("TOKEN", "IP", PORT)

#call ping function 
#result must be Pong 
result,ok=nipo.Ping()
if ok == True:
  print(result)

#set key and value in database 
result,ok=nipo.Set("KEY" , "VALUE")
if ok == True:
  print(result)

#get value of specefic key 
nipo.Get("KEY")

```
