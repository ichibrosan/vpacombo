# vpacombo
CLion project with c++ main and c++ library

This configuration has the library code in the same folder with the application. The benefit of this is not having to keep multiple IDE windows open while making changes that affect both sections. In a much more mature code base, these might want to be separated and maintained individually. But for now it is easier to it this way. It also simplifies the cmake file.

I am currently using CLion (from JetBrains) as my IDE.

![image](https://user-images.githubusercontent.com/12984900/183300440-de7db7a1-2578-4d01-b465-70f55af23f6a.png)

Note: my cmake.yml workflow is experimental and broken at the moment TBD
