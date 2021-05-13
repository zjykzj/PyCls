
# Benchmark - ResNet

## Convert

The torchvision pretraining model can be transformed into zcls by script

```
$ cd /path/to/ZCls
$ python tools/converters/torchvision_resnet_to_zcls_resnet.py
```

## Benchmark

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-uzvj{border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-7btt{border-color:inherit;font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-uzvj">arch</th>
    <th class="tg-uzvj">framework</th>
    <th class="tg-uzvj">top1</th>
    <th class="tg-uzvj">top5</th>
    <th class="tg-7btt">input_size</th>
    <th class="tg-7btt">dataset</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-9wq8">resnet18</td>
    <td class="tg-9wq8">zcls</td>
    <td class="tg-9wq8">69.224</td>
    <td class="tg-9wq8">88.808</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet18</td>
    <td class="tg-9wq8">torchvision</td>
    <td class="tg-9wq8">69.222</td>
    <td class="tg-9wq8">88.808</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet34</td>
    <td class="tg-9wq8">zcls</td>
    <td class="tg-9wq8">72.821</td>
    <td class="tg-9wq8">91.071</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet34</td>
    <td class="tg-9wq8">torchvision</td>
    <td class="tg-9wq8">72.817</td>
    <td class="tg-9wq8">91.073</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet50</td>
    <td class="tg-9wq8">zcls</td>
    <td class="tg-9wq8">75.692</td>
    <td class="tg-9wq8">92.768</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet50</td>
    <td class="tg-9wq8">torchvision</td>
    <td class="tg-9wq8">75.690</td>
    <td class="tg-9wq8">92.770</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet101</td>
    <td class="tg-9wq8">zcls</td>
    <td class="tg-9wq8">76.965</td>
    <td class="tg-9wq8">93.526</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet101</td>
    <td class="tg-9wq8">torchvision</td>
    <td class="tg-9wq8">76.967</td>
    <td class="tg-9wq8">93.528</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet152</td>
    <td class="tg-9wq8">zcls</td>
    <td class="tg-9wq8">78.141</td>
    <td class="tg-9wq8">93.946</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnet152</td>
    <td class="tg-9wq8">torchvision</td>
    <td class="tg-9wq8">78.139</td>
    <td class="tg-9wq8">93.946</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnext50_32x4d</td>
    <td class="tg-9wq8">zcls</td>
    <td class="tg-9wq8">77.353</td>
    <td class="tg-9wq8">93.610</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnext50_32x4d</td>
    <td class="tg-9wq8">torchvision</td>
    <td class="tg-9wq8">77.353</td>
    <td class="tg-9wq8">93.612</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnext101_32x8d</td>
    <td class="tg-9wq8">zcls</td>
    <td class="tg-9wq8">79.075</td>
    <td class="tg-9wq8">94.540</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-9wq8">resnext101_32x8d</td>
    <td class="tg-9wq8">torchvision</td>
    <td class="tg-9wq8">79.063</td>
    <td class="tg-9wq8">94.538</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
  <tr>
    <td class="tg-c3ow">sknet50</td>
    <td class="tg-c3ow">zcls</td>
    <td class="tg-c3ow">78.343</td>
    <td class="tg-c3ow">93.944</td>
    <td class="tg-c3ow">224x224</td>
    <td class="tg-c3ow">imagenet</td>
  </tr>
</tbody>
</table>