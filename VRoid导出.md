# VRoid导出方法

1. VRroidStudio中选择摄影导出页点击导出，填写title，其他项选填。
   
   ![image](pic/1.png)

2. 如果你想在Unity中使用，推荐使用UniVRM插件，将Vroid.vrm直接拖入unity中即可。在unity中可以使用UnityFBXExport插件导出模型。

3. 如果想转成FBX，将Vroid.vrm重命名为Vroid.glb,然后使用Win10自带的`画图3D`软件打开。
   
   ![image](pic/2.png)

4. 在画图3D中导出fbx。
   ![image](pic/3.png)

   
**使用画图3D导出可以保留材质数量，贴图会包含在fbx中，但是材质会变为standard，材质和贴图的关联可能会丢失。**

   ![image](pic/4.png)

**使用UniVRM插件和UnityFBXExport插件导出Fbx会合并mesh和材质。**

根据用途选中导出方式。

**注意，重命名glb后的Win10默认打开方式是3DBuilder,这个只能导出obj。**

![image](pic/5.png)

