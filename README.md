根目录执行

g++ -m64 -pthread -o MAV_RAK_Server -I ./Source -I ./MAV_Include/common ./Demo/Server.cpp ./Source/*.cpp  -fpermissive



g++ -m64 -pthread -o MAV_RAK_Client -I ./Source -I ./MAV_Include/common ./Demo/Client.cpp ./Source/*.cpp  -fpermissive
