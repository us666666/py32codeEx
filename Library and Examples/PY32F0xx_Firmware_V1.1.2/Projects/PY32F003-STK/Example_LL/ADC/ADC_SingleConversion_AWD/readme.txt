================================================================================
                                样例使用说明
================================================================================
功能描述：
此样例演示了ADC的模拟看门狗功能，PA4为模拟输入，当PA4的电压值不在设定的上下限中，
会进入看门狗中断。

================================================================================
测试环境：
测试用板：PY32F003_STK
MDK版本： 5.28
IAR版本： 9.20
================================================================================
使用步骤：
1. 编译下载程序到MCU，并运行；
2. PA4的电压值小于1.65V(供电电压为3.3V),LED灯熄灭；
3. PA4的电压值大于1.65V(供电电压为3.3V),LED灯会一直闪烁。

================================================================================
注意事项：


================================================================================