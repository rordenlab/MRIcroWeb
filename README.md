# NIfTI WebGL Volume Rendering

[Try the demo](https://rordenlab.github.io/).

This project allows users to open and view NIfTI format images, which are popular for scientific neuroimaging. One can convert the complicated DICOM format popular in medical imaging to the simpler NIfTI format using free tools like [dcm2niix](https://github.com/rordenlab/dcm2niix).

By using webGL 2, these renderings can be viewed with web browsers on any computer, including tablets and smart phones (though be aware that Apple's iOS does not yet support WebGL 2). The idea for this project is to provide a web-based tool with similar functions to tools like [MRIcroGL](https://www.nitrc.org/plugins/mwiki/index.php/mricrogl:MainPage) that is available for [Windows, Linux and MacOS](https://github.com/rordenlab/MRIcroGL12/releases).

# Components

 - Will Usher's [WebGL Volume rendering](https://github.com/Twinklebear/webgl-volume-raycaster).
 - Will Usher's [WebGL utilities](https://github.com/Twinklebear/webgl-util).
 - RII-UTHSCSA's [NIFTI-Reader](https://github.com/rii-mango/NIFTI-Reader-JS).
 - [glMatrix](http://glmatrix.net/) for matrix/vector operations.
 - [pako](https://github.com/nodeca/pako) for GZip decompression.

# Alternatives
 - [AMI supports volume rendering](https://github.com/FNNDSC/ami)
 - Leandro Roberto Barbagallo's [volume renderer](http://www.lebarba.com/)
 - [med3web](https://github.com/epam/med3web) has an [elegant interface](https://med3web.opensource.epam.com/)
 - [Roland Rytz's volume rendering](https://github.com/RolandR/VolumeRayCasting)
 - [ShareVol](https://github.com/OKaluza/sharevol) by [Owen Kaluza](http://owen.kaluza.id.au/sharevol/)
 - [three.js](https://threejs.org/examples/webgl2_materials_texture3d_volume.html) can read NRRD format images
 - [vtk-js](https://kitware.github.io/vtk-js/examples/VolumeViewer.html)
 - [XTK](https://github.com/xtk/X)


## Images

![Screenshot](web_render.png)


