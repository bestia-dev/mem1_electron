# mem1_electron
Creating a desktop electron app from Rust Webassembly Virtual Dom memory game.  
Things are changing very fast. This is the situation as at 2019-04-05.  

The source code of the original app is here:  
[https://github.com/LucianoBestia/mem1](https://github.com/LucianoBestia/mem1)  
Learning to use Dodrio virtual DOM on a simple memory game for kids.  
The images are funny cartoon characters from the alphabet.  
The cards grid is only 4x4.  


# How to install Electron on Windows
1. install Nodejs 11 - the latest version. It will also install npm - the packet manager.   
It didn't work correctly for me with Nodejs version 10. I don't know why.    
[https://nodejs.org/en/](https://nodejs.org/en/)  

2. Install electron  
```
npm i -D electron@latest
```

# Clone and run mem1_electron example code
3. Clone mem1_electron code example. It will create a new folder.  
```
git clone https://github.com/LucianoBestia/mem1_electron
```
4. move to the new folder
```
cd mem1_electron
```
5. Install all needed referenced libraries  
```
npm install
```
6. build and start the new electron application  
```
npm start
```
# Create a package for distribution
7. install electron-packager
```
npm install electron-packager -g
```
8. create a folder with all files for distribution.
You can then zip it and publish it. 
```
electron-packager .
```

I hope it will work for you as it did for me.
