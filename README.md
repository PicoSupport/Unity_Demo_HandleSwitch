
## Unity_Demo_SwitchPicoNeoControllers

## Unity Versions：
- 2017.1.0f3 and later

## Description：

-  This demo implement the functions of switching Pico Neo main and secondary controllers
-  Judge handle button response event
-  Please refer to **ChangeHand.cs** script for detail. Call **Pvr_ControllerManager.SetControllerServiceBindStateEvent** delegate method first and then call **Controller.UPvr_GetMainHandNess()** to judge the main and secondary of the current controller.

## Usage：
- Scene： Assets -> Scene -> PicoNeoHandleSwitch

- Click the button "switch handle" to switch the main and secondary handles
- Switch function requires two controllers connected at the same time

## Note:
- If you have any questions/comments, please raise requests at [**PicoDevSupport Portal**](https://picodevsupport.atlassian.net/servicedesk/customer/user/login?
