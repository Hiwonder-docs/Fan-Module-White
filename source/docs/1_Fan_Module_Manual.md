# 1. Fan Module Manual

<img class="common_img" src="../_static/media/chapter_1/section_1/media/image2.png" style="width:500px" />

## 1.1 Fan Module Description

### 1.1.1 Sensor Introduction

This fan module features an adjustable speed and can operate without an external motor driver. You can combine the fan module with a temperature sensor to create a smart fan that automatically adjusts its speed based on temperature.

Additionally, it features LEGO-compatible mounting holes, allowing for more creative DIY designs.

### 1.1.2 Working Principle

The fan sensor controls rotation direction using two-way PWM signals, and you can adjust the fan speed by changing the PWM duty cycle.

## 1.2 Notice

1.  Do not exceed the rated voltage range during use.

2.  Do not touch or block the fan blades during operation to prevent motor damage.

## 1.3 Specifications

For more information, you may refer to "**[Fan module(white) schematic](https://drive.google.com/drive/folders/1zsZ_WIlIAVwMXkaNothLat2LdmjEHYYP?usp=sharing)**."

### 1.3.1 Pin Instruction

| **Pin** | **Instruction**                   |
| :------ | :-------------------------------- |
| 5V      | Power Input                       |
| GND     | Ground                            |
| M+      | Clockwise PWM signal input        |
| M-      | Counterclockwise PWM signal input |

### 1.3.2 Specifications

<table class="docutils-nobg" border="1">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr>
<td colspan="2" style="text-align: center;">
<p><strong>Fan Module</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Parameter</strong></p>
</td>
<td style="text-align: center;">
<p><strong>Specification</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Power Supply</strong></p>
</td>
<td style="text-align: center;">
<p><strong>DC 5V</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Indicator Light (PWR) Description</strong></p>
</td>
<td style="text-align: center;">
<p><strong>The PWR LED lights up when powered.</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Connector Type</strong></p>
</td>
<td style="text-align: center;">
<p><strong>5264-4AW</strong></p>
</td>
</tr>
<tr>
<td style="text-align: center;">
<p><strong>Product Dimensions</strong></p>
</td>
<td style="text-align: center;">
<p><strong>50mmx20mm</strong></p>
</td>
</tr>
<tr>
<td colspan="2" style="text-align: center;">
<p><strong>Modular installation, compatible with Lego series.</strong></p>
</td>
</tr>
</tbody>
</table>

## 1.4 Project Outcome

You can refer to the case tutorials and programs for different platforms in the same directory as this tutorial. This section will demonstrate the testing effect using Arduino IDE as an example.

The fan module cycles through the following sequence, each lasting 2 seconds: full-speed clockwise rotation, stop, half-speed clockwise rotation, and half-speed counterclockwise rotation.