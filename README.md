# problem statement
creates an azure servicebus topic authorization rule (if it doesn't already exist)

# example usage

> note: in examples, VERSION represents a version of the azure.servicebus.topic.authrule.create pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.servicebus.topic.authrule.create#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.servicebus.topic.authrule.create#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/azure.servicebus.topic.authrule.create#VERSION }
    inputs: 
      subscriptionId:
      loginId:
      loginSecret:
      loginTenantId:
      name:
      namespace:
      topic:
      resourceGroup:
      rights:
      # begin optional args
      loginType:
      # end optional args
```

