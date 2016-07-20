#RenderContextImp.cs

####Location: *FuseeRoot/src/Engine/Imp/Graphics/Android/*


Found a small bug that slowed us down quite a bit:</br>
In line 675

    GL.GetShaderInfoLog(vertexObject, 512, out length, info);
should be

    GL.GetShaderInfoLog(fragmentObject, 512, out length, info);
  

We had a bug in our fragment shader and just got the error message: **Success**
