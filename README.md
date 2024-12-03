## U-Net Architecture

<div align="center">
  <p>
    <img width="100%" src="assets/image.png" alt="U-Net Architecture"></a>
  </p>


The U-Net architecture achieves very good performance on very different biomedical segmentation applications. U-net architecture (example for 32x32 pixels in the lowest resolution) as presented in Figure 1. Each blue box corresponds to a multi-channel feature map. The number of channels is denoted on top of the box. The x-y-size is provided at the lower left edge of the box. White boxes represent copied feature maps. The arrows denote the different operations. This work is based on [Ronneberger et al](https://arxiv.org/pdf/1505.04597).

</div>

## HOW TO INSTALL
```sh
conda create -n torch python==3.9
conda activate torch

git clone https://github.com/brain-facens/u-net-template.git
cd u-net-template
pip install -r requirement.txt
```

You can find the notebook in ```./notebooks/UNet_seg.ipynb```.

## 🤝 Collaborators

We would like to thank the following people who contributed to this project:

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/64169072?v=4" width="100px;" alt="Foto do Natanael Vitorino no GitHub"/><br>
        <sub>
          <b>Natanael Vitorino</b>
        </sub>
      </a>
    </td>
  </tr>
</table>


## 📝 License

This project is under license. See the file [LICENSE](LICENSE) for more details.

---
