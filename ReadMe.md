# Heroku buildpack: PortAudio

![logo](https://raw.githubusercontent.com/Galarius/heroku-buildpack-portaudio/master/build_pack_logo.png)

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [PortAudio](http://www.portaudio.com). 

## Usage

```
heroku create -b https://github.com/Galarius/heroku-buildpack-portaudio.git

# or if your app is already created
heroku config:add BUILDPACK_URL=https://github.com/Galarius/heroku-buildpack-portaudio.git

git push heroku master
```  
  
Installation directory for PortAudio is: `/app/vendor/portaudio`  

## PyAudio  

Follow [PyAudio buildpack](https://github.com/Galarius/heroku-buildpack-pyaudio) instructions to install [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/).
