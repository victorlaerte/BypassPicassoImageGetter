# BypassPicassoImageGetter
Loads images for Bypass using Picasso

# Usage
```java
textView.setText(bypass.markdownToSpannable(response.body().string(), 
    new BypassGlideImageGetter(textView, Glide.with(MainActivity.this))));
```
See the sample project for a comprehensive example.

Original credits: http://stackoverflow.com/a/25530488/504611
Fork from: https://github.com/Commit451/BypassPicassoImageGetter

License
--------

    Copyright 2016 Commit 451

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
