# wavelength-keyboard
A custom ortholinear bluetooth mechanical keyboard with a left-sided numpad. Supports low-profile Kalih Choc(olate) switches and has additional dev-connectors for accessing the MCU for other projects such as the [analog gauge based task manager](https://github.com/420Ayan420/analog-task-manager), etc.

![image](https://github.com/user-attachments/assets/310631fc-8799-4e38-b15b-945bce652cf2)
![image](https://github.com/user-attachments/assets/d672d21a-5d56-4626-9b86-4e8cd095f721)

# keyboard layout
I am using ortholinear as it is more comfortable and natural to type on, I am also using a left-sided numpad making mouse positionining more comfortable. Using [KLE](http://www.keyboard-layout-editor.com/) (keyboard layout editor) you can open the `layout.json` file to edit/view it to your needs.

![image](https://github.com/user-attachments/assets/8db4bec3-948b-410b-a899-ad370aeb1f0f)

# hardware
I have chosen the nrf52840 MCU as it has abundant GPIO pins for all the rows and columns in my switch matrix, it also has built-in bluetooth support. Regarding the I have also chosen the [Choc v1](https://chosfox.com/products/kailh-chocs) switches as they are low profile and have hot-swap sockets.
