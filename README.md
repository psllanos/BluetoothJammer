# BluetoothJammer (WIP)
Jam/DoS your neighbour's bluetooth speaker/devices for peace!

# Preview
<table style="padding:10px">
  <tr>
    <td>
        <img src="./assets/attack.png" alt="1">
    </td>
   </tr>
</table>

# TODO
- [X] Material UI
- [X] Thread Option
-  [ ] Devices List (bug)
- [X] Log Switch
- [ ] Start/Stop button (bug stop, thread doesn't killed. Need restart app)
- [X] Auto randomize UUID
- [X] Optimize Attack Thread

# Build and releases

The Android workflow builds and tests the project on pushes and pull requests.
Pushing a tag such as `v1.0.1` also creates a GitHub Release containing the
release APK.

To sign release APKs with a project keystore, add these repository secrets:

- `ANDROID_KEYSTORE_BASE64`: the keystore encoded as base64
- `ANDROID_KEYSTORE_PASSWORD`: the keystore password
- `ANDROID_KEY_ALIAS`: the signing key alias
- `ANDROID_KEY_PASSWORD`: the signing key password

# Special Thanks
- ChatGPT-4o