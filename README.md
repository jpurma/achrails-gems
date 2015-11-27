# achrails-gems

This is a dockerfile for prebuilding gems required by achrails-server. The purpose is to speed setting up achrails development boxes, as now the gems can be prebuilt when the actual rails code is in local folder.  

If you use Layers Box development environment for achrails and want to change installed gems, this is the place to do it. Make a local copy of this, run 'docker build -t achrails-gems' on it and as long as you have this image in your local machine, it will be used instead of downloading from hub.docker.com.    

Jukka Purma (2015), use quite freely: see LICENSE.

