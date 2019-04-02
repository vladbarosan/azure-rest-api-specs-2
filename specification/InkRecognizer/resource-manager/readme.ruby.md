## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_InkRecognizer
package-version: 2.5
azure-arm: true
```

### Tag: package-2.5 and ruby

These settings apply only when `--tag=package-2.5 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2.5' && $(ruby)
namespace: Microsoft.CognitiveServices
output-folder: $(ruby-sdks-folder)/InkRecognizer
```
