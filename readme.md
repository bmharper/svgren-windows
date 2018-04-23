This is a "baked" build of svgren for Windows. It is included as a submodule inside
onetwotest/agent/third_party, so that we can link to svgren from a tundra build.

How to create this?
* Clone the latest svgren from github
* Open the VS solution file (last used was VS 2017)
* Build (it will appear to be doing nothing, but is actually downloading and building dependencies)
* Scrape the necessary files for this repo, out of the build artifacts from the above step.