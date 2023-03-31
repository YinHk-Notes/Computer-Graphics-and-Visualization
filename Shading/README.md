## Shading


### Shader
In computer graphics, a **shader** is a **computer program** that calculates the **appropriate levels of light**, **darkness**, and **color** during the **rendering of a 3D scene** - a process known as **shading**.

Shaders have evolved to perform a variety of specialized functions in computer graphics special effects and video post-processing, as well as general-purpose computing on graphics processing units.

Shader is code that controls the color of each pixel on the screen and usually run on the graphics processor.


A program used to **render different pixels**. Shaders in games are used when **detailing shadows**, **lighting**, **texture gradients, and more**.

電腦圖學領域中，著色器（英語：shader）是一種電腦程式，原本用於進行圖像的濃淡處理（計算圖像中的光照、亮度、顏色等），但近來，它也被用於完成很多不同領域的工作，比如處理CG特效、進行與濃淡處理無關的影片後期處理、甚至用於一些與電腦圖學無關的其它領域。

目前大多數著色器是針對GPU開發的。GPU的可程式化繪圖管線已經全面取代傳統的固定管線，可以使用著色器語言對其編程。構成最終圖像的像素、頂點、紋理，它們的位置、色相、飽和度、亮度、對比度也都可以利用著色器中定義的演算法進行動態調整。呼叫著色器的外部程式，也可以利用它向著色器提供的外部變數、紋理來修改這些著色器中的參數。


在電影後期處理、電腦成像、電子遊戲等領域，著色器常被用來製作各種特效。除了普通的光照模型，著色器還可以調整圖像的色相、飽和度、亮度、對比度，生成模糊、高光、有體積光源、失焦、卡通彩現、色調分離、畸變、凹凸貼圖、色鍵（即所謂的藍幕、綠幕摳像效果）、邊緣檢測等效果。




### What Can Shaders Do?
Sometimes games use simple shaders; other times, they may seem extremely complicated. The finished product of a shader program is often impressive, showing in-game assets or environments with proper lighting and shading applied to them.

Through their coding language, shaders transform dull and dreary environments that may have lacked a cohesive look to staggeringly beautiful works of art. You will see the difference if you turn your graphics settings all the way down in a visually impressive game. Without the shaders and other aspects, the game probably looks pretty flat.

Shaders bypass hard coding and allow for customizable, programmable shading in game design. Shaders add a certain sense of realism and artistic nuance to games that didn’t exist decades ago. It causes breathtaking visual generation on the fly, in real-time.

- Base color
- Reflectance
- Surface normal
- Metallicity
- Roughness
- Diffuse light
- Light reflections
- Shadows
- Ambient Occulusion
- Environment reflections

### Programming
The language in which shaders are programmed depends on the target environment. The official **OpenGL** and **OpenGL ES** shading language is **OpenGL Shading Language**, also known as **GLSL**, and the official **Direct3D** shading language is High Level Shader Language, also known as **HLSL**.



### ref
https://learnopengl.com/Getting-started/Shaders

https://en.wikipedia.org/wiki/Shader

https://www.youtube.com/watch?v=uQG0SWv5lbw&list=PL78XDi0TS4lFlOVKsNC6LR4sCQhetKJqs

Writing a Shader in OpenGL \
https://www.youtube.com/watch?v=71BLZwRGUJE

A Beginner's Guide to Coding Graphics Shaders \
https://gamedevelopment.tutsplus.com/tutorials/a-beginners-guide-to-coding-graphics-shaders--cms-23313

Modern OpenGL C++ Shader Programming \
https://www.youtube.com/watch?v=l7RwXnVPAW4

