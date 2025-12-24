# FluidCPS

This is a Fusion 360 post processor for Autodesk's Fusion 360 CAM.

Based on the [GRBL Post Processor](https://cam.autodesk.com/hsmposts?p=grbl) whose history can be found on the
[grbl_cps branch](https://github.com/ajmirsky/FluidCPS/tree/grbl_cps).


## Getting Started

1. Download the zip file or clone the repository.
2. Go to Fusion 360 and open the Manufacturing view.
3. Right-click on the Setup and select "Create NC Program"

![NC Program](https://github.com/ajmirsky/FluidCPS/blob/main/imgs/fusion360_screen1.png)

4. In the 'Machine and Post' section, click the folder icon next to the 'Post' setting. 

![Post Setting](https://github.com/ajmirsky/FluidCPS/blob/main/imgs/fusion360_screen2.png)

5. And click the import icon. Select the `fluidnc.cps` file.

![Post Import](https://github.com/ajmirsky/FluidCPS/blob/main/imgs/fusion360_screen3.png)

## Additions

- [ ] plasma machine support
- [ ] laser cutting support
- [ ] waterjet support
- [ ] probe operations
