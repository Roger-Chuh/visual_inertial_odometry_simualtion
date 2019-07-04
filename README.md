# (Mono) Visual [ Inertial | Wheel ] Odometry Simualtion
MATLAB simulation of (Mono) visual-inertial odometry (VIO) & visual-wheel odometry

These are MATLAB simulations of (Mono) Visual [ Inertial | Wheel ] Odometry
These simulations provide the ideal case with **some noises** which can be turned off and on.

* You can use this simulation belong your need
* I checked all the demo files whether it can be runned without any amendation, but the MATLAB version can be critical 
* I made this simulations on MATLAB 2019a

## Code Description 
(Each SIMx-files are in a group)
1. **SIM1_w2Dfeat_demo.m** 
> SIM1 is a simple 2D simulation of camera. Using features with angle and distance constraint.

2. **SIM2_w3Dfeat_demo.m** 
> SIM2 is a 3D simulation of camera with features and optical flow.
> SIM2 apply 3D position and attitude in world, body, camera frame.
> SIM2 selects features with distance, camera heading, intrinsic matrix constraint. 
> SIM2 visualize the **camera-robot in 3D** dimension and **projected camera view**
> SIM2 describe the **Ideal Case** with on-off camera error model (ex. distortion, pixel error, miss tracking)

3. (*not yet*) **SIM3_IMU_demo.m** 
> ~~SIM3 is a simulation of inverse INS(path2IMUdata), INS(IMUdata2path) and IMU error model~~ 
4. (*not yet*) **SIM4_WheelOdo_demo.m** 
> ~~SIM4 is a simulation of inverse WheelOdometry and WheelOdometry with error model~~
5. (*not yet*) **SIM5_Visual_odometry_demo.m** 
> ~~SIM5 is a simulation of visual odometry using the camera in SIM2 ~~

6. (*Editing*) **SIM6_Visual_inertial_odometry_demo.m** 
> SIM6 is a simulation of visual-inertial odometry using the camera in SIM2 and ~~IMU in SIM3~~
> SIM6 visualize as same as SIM2
> ~~SIM6 makes feature Tracks on image plane~~
> ~~SIM6 calculate epipoar constraint cost to with matched features~~

## Liscence
GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007

*****

### ���� ���� (Guidelines in Korean)
* (���) ���־� [ ���� | �� ] ������Ʈ���� ���� ��Ʈ�� �ùķ��̼� �Դϴ�. 
* ����� ���� �̻����� ���̽��� �����Ǹ�, ������� �ʿ信 ���� ����ϰų� ������� �ʵ��� ������ �� �ֽ��ϴ�.
* ���̼����� GNU ����3�� �����ϴ�. �̴� �����Ӱ� ����ϵ�, ���� ���̼���(GNUv3)�� ����ϰ� �� ������� �����ؾ� �Ѵٴ� ���� �ǹ��մϴ�.
* ��� �ùķ��̼� ������ �������� �ٷ� ���� �����ϵ��� üũ�ϰ� �ø��ϴٸ�, ������ ���� ��� �������ּ���.
* Ȥ�� �۵��� ���� �ʴ´ٸ�, ���� ������ �� �ֽ��ϴ�. �� �ڵ�� ��Ʈ��2019a���� �ۼ��Ǿ����ϴ�.

## �ڵ� ���� (Code Description in Korean)
(���� ���� ���ڸ� ������ SIM���ϵ��� ���� �׷쿡 ���մϴ�.)
1. **SIM1_w2Dfeat_demo.m** 
> SIM1�� ������ 2Dȯ�濡���� ī�޶� �ùķ��̼� �Դϴ�. 
> ����� �þ߹����� ������ ���� ������ ���� �ڵ带 �ۼ��Ͽ����ϴ�.

2. **SIM2_w3Dfeat_demo.m** 
> SIM2�� 3D ȯ�濡���� Ư¡���� ī�޶� ���� �ùķ��̼��Դϴ�.
> SIM2������ Ư¡������ �Ÿ�, ī�޶� ����, ���� �Ķ���� ������ ����ؼ� Ư¡���� ���ϴ�.
> SIM2������ **ī�޶�κ��� �ִ� 3Dȯ��**�� Ư¡������ **ī�޶� ���� ȭ��**�� �����ݴϴ�.
> SIM2�� ����� Ű�� �� �� �ִ� �̻����� ��Ȳ������ �ùķ��̼��Դϴ�. (�ְ�, �ȼ� ����, ���� ���� ��)

3. (*����*) **SIM3_IMU_demo.m** 
> ~~SIM3�� �� INS�� INS, IMU ���� �𵨿� ���� �ùķ��̼��Դϴ�.~~ 
4. (*����*) **SIM4_WheelOdo_demo.m** 
> ~~SIM4�� �� �� ������Ʈ���� ���� ���� ����� �� ������Ʈ���� ���� �ùķ��̼��Դϴ�.~~
5. (*����*) **SIM5_Visual_odometry_demo.m** 
> ~~SIM5�� SIM2�� ī�޶� �̿��� ���־� ������Ʈ���� ���� �ùķ��̼��Դϴ�.~~

6. (*������*) **SIM6_Visual_inertial_odometry_demo.m** 
> SIM6�� SIM2�� ī�޶�� SIM3�� IMU�� �̿��� ���־�-���� ������Ʈ���� ���� �ùķ��̼��Դϴ�.
> SIM6�� SIM2�� ���� �ð�ȭ�� �մϴ�.
> ~~SIM6�� ������ Ư¡������ �׾Ƽ� Ʈ���� ����ϴ�~~
> ~~SIM6�� ��Ī�� Ư¡���� ���� �������� ���ǿ� ���� ����Լ��� ����մϴ�.~~


