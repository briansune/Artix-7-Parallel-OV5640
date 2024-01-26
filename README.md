# Artix-7-OV5640-fpga-parallel-camera

This is a renew revision of OV5640 Camera Demonstration from ALINX.

## If this project is constructive, welcome to donate a drink to PayPal.

<img src="https://github.com/briansune/FPGA-Camera-MIPI-DVP-Verilog/assets/29487339/75ccc568-4f17-48a1-b2af-20211f98896c" style="height:20%; width:20%">

# A cheap and verified OV5640: <a href="https://item.taobao.com/item.htm?_u=e10quk0k218a&id=747353997633&spm=a1z09.2.0.0.77362e8d8Nq7isa" target="_blank">Camera Supplier</a>

<img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/e834ee1d-6a3a-48b0-9a1b-ce9001672ac4" style="height:35%; width:35%">

# If you need the EVB - Email me

<img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/45cd2f58-d7d1-4216-8cf3-8c5b0ee9c6d4" style="height:35%; width:35%">

### It is recommanded to use I/O @ 1.8V or 2.8V and ALINX board only support 3V3 so this example is demo purpose only!!!

<img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/f5beb537-d379-4f6e-a1e5-2e391437b7b5" style="height:35%; width:35%">


# Hardware Setup - OV5640 (EVB OV5640)

<img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/0a652685-1a1f-4712-9fe3-5e0925c2de81" style="height:45%; width:45%">

## Preview

| Resolution | Preview |
|:---------------:|:----------------------------------------------------------------:|
| XGA - 1024x768 | <img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/fd2e3413-281b-47c8-96b0-4db7ecfcb4c1" style="height:45%; width:45%"> |
| WQVGA - 480x272 | <img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/0a79e799-715a-4406-af66-6bf90f17737b" style="height:45%; width:45%"> |
| 720P - 1280x720 | <img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/38489da4-0c58-470a-820e-6f2b9f98e22b" style="height:45%; width:45%"> |
| QuadVGA - 1280x960 | <img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/f700f459-ef60-42ff-8128-1ce464a0c697" style="height:45%; width:45%"> |
| 1080p - 1920x1080 Gray | <img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/d277faa2-46ce-415e-8b8c-5bb7f330ae35" style="height:45%; width:45%"> |
| 1080p - 1920x1080 Debayer | <img src="" style="height:45%; width:45%"> |

# Vivado Resources

<img src="https://github.com/briansune/Artix-7-Parallel-OV5640/assets/29487339/6bff728f-4fad-461a-bd23-077f95a8b43c">

The timing of one node is not met but this is normal as cross-clock-domain ignore is not set in XDC which can be include or use CDC library to remove such warning.
