1. ������Ҫ���µ����ݰ����¶�Ӧ�ļ�������SD����

(1). ���������ļ���robin_nano35_cfg.txt
(2). ����ͼƬ��    mks_pic
(3). �����ֿ⣺    mks_font
(4). ����TFT�̼��� Robin_nano35.bin
(5). ����Wifi�̼���MksWifi.bin

2. V2.0.0 �޸����⣺
(1). �������ߵ��������ܣ�
(2). ����cura������������ļ���������;
(3). �����Ի�����滽��֮����ʾ����������;
(4). �Ż���λ��ͨ��wifiģ���ӡ����;

3. V2.0.1 �޸����⣺
(1). ����Babystep����;
(2). ����Z_SAFE_HOMING����;

4. V2.0.2 �޸����⣺
(1). �����Ի��򱳾���ɫ��������ɫ��ʾ��������;
(2). ����corexy���͵�ƽ����������������;
(3). ����BLTOUCH3.1;

5. V2.0.3 �޸����⣺
(1). ���ӿ�����ͣ����;
(2). ֧��mks upsģ��;

6. V2.0.3.1 �޸����⣺
(1). �޸������ࡱ������ʾ����;
(2). �޸�����ʱͣ������;

7. V2.0.3.2 �޸����⣺
(1). ������ͣλ�ÿ��������ù���;

8. 2.0.3.3 �޸����⣺
(1). �������߷���gcodeָ���;
(2). ����BL_TOUCH 3.1��ƽ���ɹ�����;

9. V2.0.3.4 �޸����⣺
(1). ���ߵ��ι��ܿ�����;
(2). ������ӡ������淵�ذ�ť����ɫ����;
(3). ������ť����ƫ�Ʋ���������;
(4). ��������ػ�����������;

10. V2.0.3.5 �޸����⣺
(1). �޸�Ԥ��û���¶ȱ�������;
(2). ���ӵ������;
(3). �޸ĵ������ʱ��Ϊ20����;

11. V2.0.3.6 �޸����⣺
(1). BootLoader���̼�������ILI9486��Ļ����;
(2). ����Z����㷽��Ϊ���ֵʱ˫Z˫��λ���ܲ���������;
(3). ���԰�������̼��Ż�;

//////////////////////////////////////////////////////////////

1. According to the content that needs to be updated, copy the following file to the SD card:

(1). update the config file��robin_nano35_cfg.txt
(2). update images��         mks_pic
(3). update font��           mks_font
(4). update TFT firmware��   Robin_nano35.bin
(5). update Wifi firmware��  MksWifi.bin

2. V2.0.0 Modifications:
(1). Add online parameter adjustment function;
(2). Fix the garbled characters of Chinese files transmitted by cura plugin
(3). Correct the abnormal display problem after the dialog interface wakes up;
(4). Optimize the printing function of the pc software through the wifi module;

3. V2.0.1 Modifications:
(1). Add Babystep function;
(2). Add Z_SAFE_HOMING function;

4. V2.0.2 Modifications:
(1). Fix the problem that the background color and font color of the dialog box are displayed incorrectly;
(2). Fix the problem that the leveling parameters of corexy models do not work;
(3). Compatible with BLTOUCH3.1;

5. V2.0.3 Modifications:
(1). Add quick pause function;
(2). Support mks ups module;

6. V2.0.3.1 Modifications:
(1). Fix the display problem of "More" interface;
(2). Fix the problem of print pause when awakening;

7. V2.0.3.2 Modifications:
(1). Increase the pause position can be configured online;

8. V2.0.3.3 Modifications:
(1). Added the function of sending gcode commands online;
(2). Fix BL_TOUCH 3.1 unsuccessful leveling problem;

9. V2.0.3.4 Modifications:
(1). Online tuning can be configured;
(2). Fix the background color of the return button in the print more interface;
(3). Fixed the problem that the button font offset is not saved;
(4). Fixed the problem of not saving after shutting down;

10. V2.0.3.5 Modifications:
(1). Repair the problem of no temperature protection in preheating;
(2). Add German and Japanese;
(3). Modify the motor unlocking time to 20 minutes;


11. V2.0.3.6 Modifications:
(1). BootLoader and firmware newly add ILI9486 screen driver;
(2). Fixed the problem that the double Z double limit function is abnormal when the Z-axis zero return direction is at the maximum value;
(3). Firmware optimization for the white screen problem;
