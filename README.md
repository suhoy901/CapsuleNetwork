# CapsuleNetwork
pytorch, CapsNet
- [Capsule_Network_Jupyter](https://github.com/suhoy901/CapsuleNetwork/blob/master/CapsuleNetwork.ipynb)
<br>

A PyTorch implementation of CapsNet based on NIPS 2017 paper [Dynamic Routing Between Capsules](https://arxiv.org/abs/1710.09829).


<table>
  <tr>
    <td>
     <img src="caps_result/train_loss.png"/>
    </td>
    <td>
     <img src="caps_result/test_loss.png"/>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
     <img src="caps_result/train_accuracy.png"/>
    </td>
    <td>
     <img src="caps_result/test_accuracy.png"/>
    </td>
  </tr>
</table>

정오분류표

<img src="caps_result/confusion_matrix.png"/>

<table>
  <tr>
    <td style="text-align: middle;">Ground Truth</td>
    <td style="text-align: middle;">Reconstruction</td>
  </tr>
  <tr>
    <td>
     <img src="caps_result/ground_truth.jpeg"/>
    </td>
    <td>
     <img src="caps_result/reconstruction.jpeg"/>
    </td>
  </tr>
</table>

## Credits
Primarily referenced this implementation:
- [PyTorch implementation by @Gram.AI](https://github.com/gram-ai/capsule-networks)
- [PyTorch implementation by @leftthomas](https://github.com/leftthomas/CapsNet)
