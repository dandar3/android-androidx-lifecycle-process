## androidx-lifecycle-process

Eclipse library project based on:<br/>
https://maven.google.com/androidx/lifecycle/lifecycle-process/2.0.0/lifecycle-process-2.0.0.aar

**Import:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-androidx-lifecycle-process/2.0.0/.projectset

**Notes:** <img src="https://raw.githubusercontent.com/google/material-design-icons/master/alert/1x_web/ic_error_outline_black_24dp.png" align="top" />
- _Tag **&lt;provider&gt;** attribute **authorities** has invalid character '$'._<br/>
  Replace `${applicationId}` with your own application package in this `AndroidManifest.xml`<br/>
  See [&lt;provider android:authorities&gt;](https://developer.android.com/guide/topics/manifest/provider-element.html#auth) tag documentation for more details.

**Requires:**
- `Android 9 (API 28) SDK Platform`

**References:**
- https://developer.android.com/jetpack
- https://developer.android.com/jetpack/androidx
- https://developer.android.com/jetpack/androidx/releases/lifecycle