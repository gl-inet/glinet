## What is this?  

This repo is an official ipks for GL.iNet's router, which includes the UI and background ipks. You can integrate into imagebuilder.  

## How can I use it?  

I assume that you already have a working on imagebuilder, and then add the following line into "repositories.conf" which you can be found under the top directory of your imagebuilder workspace. It has been integrated if using GL.iNet's imagebuilder.  

```  
src glinet file:glinet/ar71xx
```  

Note that *ar71xx* is the board you use. **ar71xx/ramips** are supported.  

Finally, downloading this repo to your imagebuilder top directory.  

```  
$ git clone https://github.com/gl-inet/glinet glinet
```  

Now you can build an image which is integrated with GL.iNet's UI and background
ipks via PACKAGES variable likes *PACKAGES=ipk-name...*.  

Sunshine!
	https://www.gl-inet.com
