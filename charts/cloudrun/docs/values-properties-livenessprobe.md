## livenessProbe Type

`object` ([Details](values-properties-livenessprobe.md))

# livenessProbe Properties

| Property                                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                             |
| :------------------------------------------ | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [failureThreshold](#failurethreshold)       | `integer` | Optional | can be null    | [CloudRun Helm Chart](values-properties-livenessprobe-properties-failurethreshold.md "https://github.com/serverless-helm/serverless-helm/charts/cloudrun#/properties/livenessProbe/properties/failureThreshold")       |
| [httpGet](#httpget)                         | `object`  | Optional | cannot be null | [CloudRun Helm Chart](values-properties-livenessprobe-properties-httpget.md "https://github.com/serverless-helm/serverless-helm/charts/cloudrun#/properties/livenessProbe/properties/httpGet")                         |
| [initialDelaySeconds](#initialdelayseconds) | `integer` | Optional | can be null    | [CloudRun Helm Chart](values-properties-livenessprobe-properties-initialdelayseconds.md "https://github.com/serverless-helm/serverless-helm/charts/cloudrun#/properties/livenessProbe/properties/initialDelaySeconds") |
| [periodSeconds](#periodseconds)             | `integer` | Optional | can be null    | [CloudRun Helm Chart](values-properties-livenessprobe-properties-periodseconds.md "https://github.com/serverless-helm/serverless-helm/charts/cloudrun#/properties/livenessProbe/properties/periodSeconds")             |

## failureThreshold

Number of consecutive failures before considering the container unhealthy.

`failureThreshold`

* is optional

* Type: `integer`

* can be null

* defined in: [CloudRun Helm Chart](values-properties-livenessprobe-properties-failurethreshold.md "https://github.com/serverless-helm/serverless-helm/charts/cloudrun#/properties/livenessProbe/properties/failureThreshold")

### failureThreshold Type

`integer`

## httpGet

HTTP GET probe configuration.

`httpGet`

* is optional

* Type: `object` ([Details](values-properties-livenessprobe-properties-httpget.md))

* cannot be null

* defined in: [CloudRun Helm Chart](values-properties-livenessprobe-properties-httpget.md "https://github.com/serverless-helm/serverless-helm/charts/cloudrun#/properties/livenessProbe/properties/httpGet")

### httpGet Type

`object` ([Details](values-properties-livenessprobe-properties-httpget.md))

## initialDelaySeconds

Number of seconds to wait before starting probe checks.

`initialDelaySeconds`

* is optional

* Type: `integer`

* can be null

* defined in: [CloudRun Helm Chart](values-properties-livenessprobe-properties-initialdelayseconds.md "https://github.com/serverless-helm/serverless-helm/charts/cloudrun#/properties/livenessProbe/properties/initialDelaySeconds")

### initialDelaySeconds Type

`integer`

## periodSeconds

How often to perform probe checks.

`periodSeconds`

* is optional

* Type: `integer`

* can be null

* defined in: [CloudRun Helm Chart](values-properties-livenessprobe-properties-periodseconds.md "https://github.com/serverless-helm/serverless-helm/charts/cloudrun#/properties/livenessProbe/properties/periodSeconds")

### periodSeconds Type

`integer`
