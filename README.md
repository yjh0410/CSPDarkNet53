# CSPDarkNet53
CSPDarkNet53

I train my cspdarknet53 on ImageNet with 224 input size rather than 256 input size.

Attention, my CSPDarkNet-53 uses LeakyRelu rather than Mish. I tried Mish but failed. I have no idea how to get better performance with Mish on ImageNet.

<table><tbody>
<tr><th align="left" bgcolor=#f8f8f8> </th>     <td bgcolor=white> size </td><td bgcolor=white> acc1 </td></tr>

<tr><th align="left" bgcolor=#f8f8f8> cspdarknet53</th><td bgcolor=white> 224 </td><td bgcolor=white> 75.7 </td></tr>

<tr><th align="left" bgcolor=#f8f8f8> cspdarknet53-448 </th><td bgcolor=white> 448 </td><td bgcolor=white> 76.9 </td></tr>

</table></tbody>

<table><tbody>
<tr><th align="left" bgcolor=#f8f8f8> </th>     <td bgcolor=white> size </td><td bgcolor=white> acc1 </td></tr>

<tr><th align="left" bgcolor=#f8f8f8> cspdarknets_slim</th><td bgcolor=white> 224 </td><td bgcolor=white> 72.4 </td></tr>

<tr><th align="left" bgcolor=#f8f8f8> cspdarknet53_slim-448 </th><td bgcolor=white> 448 </td><td bgcolor=white> - </td></tr>

</table></tbody>

# Model
Everyone can download the pretrained model from my BaiDuYunDisk:

link: https://pan.baidu.com/s/1-_-CkNDTG-UMtWY2bE-Zjw 

password: pg4o 
