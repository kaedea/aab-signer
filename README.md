## Sign AAB
Jar tool that helps signing an aab file with given keystore, see [.circleci/config.yml](#.circleci/config.yml).
<br>
Inspired by [AabResGuard](https://github.com/bytedance/AabResGuard).

## Usage
```bash
java -jar dist/aabresguard_*.jar sign-aab \
    --bundle=<input_aab_path> \
    --output=<output_path_require_not_exist> \
    --storeFile=<keysotre_file> \
    --storePassword=<storePassword> \
    --keyAlias=<keyAlias> \
    --keyPassword=<keyPassword>
```

