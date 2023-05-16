# <img src="img/SnowFlow-Pokemon-Logo.jpg"  width="100"> SnowFlow

_**Goal**: We hope to couple a snow melt model with the OverlandFlow model to model snow melt runoff (discharge at outflow of watershed)._

For the snow melt model we will use the [Positive Degree Day model (PDD)](https://glaciers.gi.alaska.edu/sites/default/files/Lecture_energybal_Hock2012.pdf). The PDD model uses initial snow depth and density and temperature as inputs. We'll run this model under several different scenarios: a cool spring day, a warm spring day and a hot spring day. 

We use the melt rate as an input to the [Overland Flow Model](https://landlab.readthedocs.io/en/master/user_guide/overland_flow_user_guide.html). For our overland flow model, we use a workflow and study area from [Gan et al. (2023)](https://www.hydroshare.org/resource/bcbcfe823cc4432f8ce96c3048d4591f/). 

Next Steps:
- Assess Flood Risk (risk factor?)
- Add additional precipitation
- Switch to HexModelGrid for better overland flow?
- Make snow depth and density spatially variable

