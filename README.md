# 🤖 Android accept licenses

Accept Android licenses with [`sdkmanager`](https://developer.android.com/tools/sdkmanager#accept-licenses).

## Rationale

The following exception will be thrown when an SDK component cannot be installed if the licence was not accepted.

```
com.android.builder.sdk.LicenceNotAcceptedException: Failed to install the following Android SDK packages as some licences have not been accepted.
```

## Usage

See [action.yml](https://github.com/SimonMarquis/android-accept-licenses/blob/main/action.yml)

```yml
steps:
  - uses: SimonMarquis/android-accept-licenses@v1
```
