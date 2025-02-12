---
name: Bug report
about: Use this template if something is not working correctly or to report errors in existing device config files.
title: ''
labels: bug
assignees: 

---

<!--
  🚨🚨🚨 STOP! STOP! STOP! 🚨🚨🚨

  Before opening an issue, please read and follow these steps:

  1. Are you using HomeAssistant?
  If yes, please open your issue at https://github.com/home-assistant/core/issues
  UNLESS a developer told you to come here.

  2. Are you using ZWaveJS2MQTT?
  If yes, please open your issue at https://github.com/zwave-js/zwavejs2mqtt/issues
  UNLESS a developer told you to come here.

  3. Check the troubleshooting section if your problem is described there:
  https://zwave-js.github.io/node-zwave-js/#/development/troubleshooting
  
  4. Check the changelog if your problem was already fixed recently.
  https://github.com/zwave-js/node-zwave-js/blob/master/CHANGELOG.md
  We cannot provide support if you are not using the latest version.

  5. Also make sure to provide the necessary information, as described here:
  https://zwave-js.github.io/node-zwave-js/#/development/troubleshooting?id=providing-the-necessary-information-for-an-issue

  If you are using zwavejs2mqtt, this is how you create the logfiles:
  * Go to Settings, Z-Wave section
  * select log level DEBUG
  * enable "log to file"

  For HomeAssistant, this is how you do it:
  Home Assistant -> settings -> Integrations -> Z-Wave JS -> Configure -> Create dump -> zip the json file and post it here.

  🙏🏻🙏🏻🙏🏻 Thanks, now onto your issue:
-->

**Checklist:**

- [ ] I am **not** using HomeAssistant. **Or:** a developer has told me to come here.
- [ ] I am **not** using ZWaveJS2MQTT. **Or:** a developer has told me to come here.
- [ ] I have checked the troubleshooting section and my problem is **not** described there.
- [ ] I have read the changelog and my problem was **not** mentioned there.

**Describe the bug**

A clear and concise description of what the bug is. Describe what causes the bug, what you observe, and what happens as a result.

**Device information**

Which device(s) is/are affected (make/model)?  
What are the node IDs?

**Did you change anything?**
- [ ] **Yes**: *(please describe)*
- [ ] **No**

**Did this use to work before?**
- [ ] **Don't know**, this is a new device
- [ ] **No**, it never worked anywhere
- [ ] **Yes**, in: *(specify application with versions)*
    
**How are you using `node-zwave-js`**
- [ ] `zwavejs2mqtt` (latest) docker image
- [ ] `zwavejs2mqtt` (dev) docker image
- [ ] `zwavejs2mqtt` Manual Docker build
    - `node-zwave-js` branch: <!-- fill in -->
    - `zwavejs2mqtt` branch: <!-- fill in -->
- [ ] ioBroker.zwave2 adapter
- [ ] `HomeAssistant` version XYZ
- [ ] Pkg
- [ ] Manual Docker build
    - `node-zwave-js` branch: <!-- fill in -->
    - `zwavejs2mqtt` branch: <!-- fill in -->
- [ ] `node-red-contrib-zwave-js`
    - Module version (double click node): <!-- fill in -->
- [ ] Manually built (as described in the [docs](https://zwave-js.github.io/node-zwave-js/#/development/installing-from-github)) 
- [ ] Other: <!-- Please describe: -->

**To Reproduce**

Steps to reproduce the behavior:
1. Go to '...'
2. Click on '...'
3. Scroll down to '...'
4. See error

**Additional context**

Add any other context about the problem here.

**Logfile:**
<!--
  ATTACH(!) `zwave-js` logfile with DEBUG or VERBOSE loglevel here. Please no links or gists or embedded logs.
  Please make sure to upload the correct log. If you're unsure, the correct one is called `zwave-<number>.log` and starts with

  ███████╗ ██╗    ██╗  █████╗  ██╗   ██╗ ███████╗             ██╗ ███████╗
  ╚══███╔╝ ██║    ██║ ██╔══██╗ ██║   ██║ ██╔════╝             ██║ ██╔════╝
    ███╔╝  ██║ █╗ ██║ ███████║ ██║   ██║ █████╗   █████╗      ██║ ███████╗
   ███╔╝   ██║███╗██║ ██╔══██║ ╚██╗ ██╔╝ ██╔══╝   ╚════╝ ██   ██║ ╚════██║
  ███████╗ ╚███╔███╔╝ ██║  ██║  ╚████╔╝  ███████╗        ╚█████╔╝ ███████║
  ╚══════╝  ╚══╝╚══╝  ╚═╝  ╚═╝   ╚═══╝   ╚══════╝         ╚════╝  ╚══════╝

-->
