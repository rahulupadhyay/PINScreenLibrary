#### PIN SCREEN library for Android
Easy to use library for implementing 4-digit pin lock for your apps

**Simple implementation**
> Approx 10 lines of code

> Themable views

> Animated visual cues

> Vibrate on error

-----------------------------------------------------------------------------------
##### How to implement

1. Add PinView to your layout
<pre>
&lt;com.kbeanie.pinscreenlibrary.views.PinView
    android:id="@+id/pinView"
    android:layout_width="match_parent"
    android:layout_height="wrap_content" /&gt;
</pre>

2. Initialize and Setup Modes
<pre>
pinView.setModeSetup(PinEntrySetupListener);
</pre>
<pre>
pinView.setModeAuthenticate(PinEntryAuthenticationListener)
</pre>

3. Handle callbacks

-----------------------------------------------------------------------------------

<div style="text-align: center;">
    <img src="demo.gif" width="200"/>
</div>

##### Maven
<pre>
<code>
&lt;dependency&gt;
    &lt;groupId&gt;com.kbeanie&lt;/groupId&gt;
    &lt;artifactId&gt;pinscreenlibrary&lt;/artifactId&gt;
    &lt;version&gt;1.0.0&lt;/version&gt;
&lt;/dependency&gt;
</code>
</pre>

##### Configuring on Android Studio
> compile 'com.kbeanie:pinscreenlibrary:1.0.0@aar'

##### License
-----------------------------------------------------------------------------------

Copyright 2013 Kumar Bibek

Licensed under the Apache License, Version 2.0 (the "License");<br />
you may not use this file except in compliance with the License.<br />
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software<br />
distributed under the License is distributed on an "AS IS" BASIS,<br />
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.<br />
See the License for the specific language governing permissions and<br />
limitations under the License.

-----------------------------------------------------------------------------------