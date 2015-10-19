# PhotoViewCropper
This is a combination of [uk.co.senab.photoview](https://github.com/chrisbanes/PhotoView) and [com.edmodo.cropper](https://github.com/edmodo/cropper). 
Both of these two projects are excellent, so I can put them together so easy with only tiny modification in cropper.
Now the Image can be zoomed and dragged by fingers pointed outside the selecting zone, and roatated by Api as same as PhotoView, before being cropped.

Since the package names of PhotoView and Cropper are not changed, include this project equals include both the two projects, original codes relate to them don't need any modification.

The version of this project follows the version of PhotoView. PhotoView.version + myVersionCode

[download demo](http://fir.im/PhotoViewCropper)

# Usage

### Gradle

As same as edmodo's cropper, except

```groovy
dependencies {
    compile 'io.github.wangeason:PhotoViewCropper:1.2.4.1'
}
```

### eclipse
![GO HOME](https://github.com/wangeason/MultiPhotoPicker/blob/master/pic/5e9a81dbgw1eu90m08v86j20dw09a3yu.jpg)

---


# License

    Copyright 2015 Wang Yansong

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

