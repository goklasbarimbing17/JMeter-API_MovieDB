# Test Performance API movieDB

### Thread Group
![alt text](ListenerResults/Thread%20Group.png "Thread Group")
+ *Number of Threads (users)* **100**
+ *Rump-up period seconds* **50**
+ *Loop Count* **10**

### HTTP Header Manager
![alt text](ListenerResults/HTTP%20Header.png "HTTP Header Manager")
Add HTTP Header, name : *__Content-Tipe__* and value : *__application/json__* 

### 1. HTTP Request - Get Popular Movie
![alt text](ListenerResults/Get%20Popular%20Movie.png "Get Popular Movie")
+ Protocol [http] : **https**
+ Server Name or IP : **developers.themoviedb.org**
+ Http Request : **GET**
+ Path : **/3/movie/popular**

### Results Listener
**View Result In Table**
![alt text](ListenerResults/View%20Result%20In%20Table%20-%20get%20popular%20movie.png "Result Listener Get Popular 1")

**View Result Tree**
![alt text](ListenerResults/View%20Result%20Tree%20-%20get%20popular%20movie.png "Result Listener Get Popular 2")

### 2. HTTP Request - Get Now Playing
![alt text](ListenerResults/Get%20Now%20Playing.png "Get Now Playing")
+ Protocol [http] : **https**
+ Server Name or IP : **developers.themoviedb.org**
+ Http Request : **GET**
+ Path : **3/movie/now_playing**

### Results Listener
**View Result In Table**
![alt text](ListenerResults/View%20Result%20In%20Table%20-%20get%20now%20playing.png "Result Listener Get Now Playing 1")

**View Result Tree**
![alt text](ListenerResults/View%20Result%20Tree%20-%20get%20now%20playing.png "Result Listener Get Now Playing 2")
