# First
1. ssh into the given account\
`ssh cs15lwi23amh@ieng6.ucsd.edu`

2. memorize the current server:\
`ieng6-203.ucsd.edu`

3. git clone

4. cd to the cloned repo

5. run junit test\
`javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`\
`java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore FileServerTests`

6. cd out

7. clone the other repo

8. find how many txt\
`find ./skill-demo1-data -name "*.txt" > num.txt`\
`wc num.txt`

9. search txt containing Lucayans\
`grep -r -l "Lucayans" skill-demo1-data > luca.txt`\
`wc luca.txt`\
`cat luca.txt`

10. memorize the name of the file containing lucayans

11. cd to the first repo

12. start the server\
`javac Server.java FileServer.java`\
`java FileServer 5555 ../skill-demo1-data`

13 find lucayans
`http://ieng6-203:5555/search?q=Bahamas-Histroy`

14 find 4 files
`http://ieng6-203:5555/search?q=Bahama`

