# Dask (Effective Scale Out Techniques) HATS@LPC 2024

The original notebooks are taken from [PyHEP 2021](https://indico.cern.ch/event/1027094/) and [PyHEP 2024](https://github.com/ikrommyd/pyhep2024-coffea-dask) Dask tutorials.

A short introductory talk is available [here](https://indico.cern.ch/event/1027094/contributions/4312696/attachments/2239462/3796674/pyhep-dask.pdf) and a recording is available on [youtube](https://www.youtube.com/watch?v=BmmVmKHEcsc&list=PLKZ9c4ONm-VnFUD0XX2DmfP1JA8VIRhXP)

In case of any questions/issues please post on the Mattermost channel.

# Prerequisites

## 1. Purdue Analysis Facility

Before the live session, please make sure that you can access Purdue Analysis Facility using the instructions below. 

1. Navigate to the [Purdue AF website](https://analysis-facility.physics.purdue.edu/) and click “Login to Purdue Analysis Facility”.
2. On the CILogon page, choose CERN account to log in (using Fermilab or Purdue credentials is also possible).
3. You will be redirected to the “Server Options” page. The default resource selection (4 CPUs, 16 GB RAM) is enough for the HATS exercises, but you can select more resources if needed. **Do not add GPUs to your session – there are not enough GPUs for all participants.**
4. Click “Start” to create your Analysis Facility session. It may take a couple of minutes to load.
5. Done! Your session is ready.
6. To upload the Grid certificate to Purdue AF, you can drag-and-drop the .p12 file from your laptop/PC into  JupyterLab file browser, use Bash terminal in JupyterLab interface to move it to ~/.globus, and then run the [standard setup commands](https://twiki.cern.ch/twiki/bin/view/CMSPublic/WorkBookStartingGrid).

<details>
  <summary>Additional details</summary>
  
- As a CMS member, you can continue using Purdue AF for your work after HATS is over.
- Your Purdue AF session will keep running even if you close your web browser tab, so you can reconnect to it at any time. Idle sessions are terminated after 14 days.
- When you log in for the first time, we create a 25 GB private directory for you at `/home/<username>`, and a shared `/work/users/<username>` directory with 100 GB quota. These directories will persist for 6 months after your last activity at Purdue AF.
- Browse the [documentation](https://analysis-facility.physics.purdue.edu/) to learn more about available functionality.
  
</details>

## 2. Tutorial setup

1. Open **Terminal** in the Purdue AF JupyterLab interface.
2. `git clone git@github.com:kondratyevd/hats-2024-dask`
3. Open the downloaded repository in the JupyterLab file browser on the left.
4. Make sure that all Jupyter Notebooks in the tutorial use **HATS 2024** kernel.




