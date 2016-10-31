# esp32-aws-iot
ESP32 template for connecting to the AWS IoT platform

https://aws.amazon.com/iot/getting-started/

https://github.com/aws/aws-iot-device-sdk-embedded-C

main/main.c:
```
#define WIFI_SSID "WIFI SSID"
#define WIFI_PASS "WIFI PASSWORD"
```

main/include/aws_iot_config.h:
```
#define AWS_IOT_MQTT_HOST              "something.amazonaws.com"
#define AWS_IOT_MQTT_PORT              8883
#define AWS_IOT_MQTT_CLIENT_ID         "SomeClientID"
#define AWS_IOT_MY_THING_NAME          "SomeThingName"
```

main/certs/README.txt:
```
  root-CA.crt
  certificate.pem.crt
  private.pem.key
```
