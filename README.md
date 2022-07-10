# Jerry
Ways to add music in c++ codes

I will list the codes you need in here:
3 files to include
'''#include<windows.h>
#include<Mmsystem.h>
#pragma comment(lib,"winmm.lib")'''
open the file:
'''mciSendString("open gameMusic.mp3 alias music",NULL,0,NULL);'''
play and turn off the music:
'''mciSendString("play music repeat",NULL,0,NULL);
mciSendString("close music",NULL,0,NULL);'''
