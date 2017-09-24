# SMALLForce
This repository is home to the source code of the SMALLForce game engine developed by DuoCore Studios.

As of SMALLForce v0.0.0.0 the original CRYENGINE Getting Started guide is the same as the SMALLForce Guide.

Instructions on getting started with git can be found [here](http://docs.cryengine.com/display/CEPROG/Getting+Started+with+git), along with details on working with launcher projects and git source code.


## Building
In order to compile, you will need to download some thirdparty SDKs. They can be downloaded by running the *download_sdks.py* script.
Or on windows the *download_sdks.exe* can be used alternatively.

CMake must be used to compile the engine, see [here](http://docs.cryengine.com/display/CEPROG/CMake) for more information.


## Updates
Until a major split occurs, updates to CRYENGINE will be integrated into SMALLForce. In the event of a key development disagreement
such as a significant new feature of CRYENGINE conflicting with a significant feature of SMALLForce, a fork will occur leading to a
CRYForce fork (which incorporates CRYTEK changes) and a SMALLForce fork (which chooses not to incorporate CRYTEK changes/incorporates
DuoCore Changes). If this does occur both engines continue to receive updates both by CRYTEK and DuoCore as long as they do not conflict
with the present DuoCore code. Once SMALLForce is broken away from CRYENGINE completely and no updates from CRYTEK are used, CRYForce
(assuming it exists) will either cease development, or will be branched off to become a supported community effort.


## License
This code may not be used to produce any functioning games, or used by any other party except DuoCore Studios at this time.
This code is development only and will only be deemed "RELEASED" once permission has been obtained by CRYTEK to branch the 
engine out separately.
