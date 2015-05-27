05-26 16:41:26.622: D/BluetoothGatt(31147): setCharacteristicNotification() - uuid: 0000ff03-0000-1000-8000-00805f9b34fb enable: true							开启notify notify
05-26 16:41:26.637: D/BluetoothGatt(31147): writeDescriptor() - uuid: 00002902-0000-1000-8000-00805f9b34fb
05-26 16:41:26.732: D/BluetoothGatt(31147): onDescriptorWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff03-0000-1000-8000-00805f9b34fb



05-26 16:41:26.752: D/BluetoothGatt(31147): setCharacteristicNotification() - uuid: 0000ff06-0000-1000-8000-00805f9b34fb enable: true							开启 REALTIME_STEPS notify
05-26 16:41:26.762: D/BluetoothGatt(31147): writeDescriptor() - uuid: 00002902-0000-1000-8000-00805f9b34fb
05-26 16:41:26.827: D/BluetoothGatt(31147): onDescriptorWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff06-0000-1000-8000-00805f9b34fb



05-26 16:41:26.837: D/BluetoothGatt(31147): setCharacteristicNotification() - uuid: 0000ff07-0000-1000-8000-00805f9b34fb enable: true							ACTIVITY_DATA notify
05-26 16:41:26.847: D/BluetoothGatt(31147): writeDescriptor() - uuid: 00002902-0000-1000-8000-00805f9b34fb
05-26 16:41:26.922: D/BluetoothGatt(31147): onDescriptorWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff07-0000-1000-8000-00805f9b34fb



05-26 16:41:26.932: D/BluetoothGatt(31147): setCharacteristicNotification() - uuid: 0000ff0c-0000-1000-8000-00805f9b34fb enable: true							电量 notify
05-26 16:41:26.942: D/BluetoothGatt(31147): writeDescriptor() - uuid: 00002902-0000-1000-8000-00805f9b34fb
05-26 16:41:27.022: D/BluetoothGatt(31147): onDescriptorWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff0c-0000-1000-8000-00805f9b34fb



05-26 16:41:27.047: D/BluetoothGatt(31147): setCharacteristicNotification() - uuid: 0000ff0e-0000-1000-8000-00805f9b34fb enable: true							SENSOR_DATA  notify
05-26 16:41:27.057: D/BluetoothGatt(31147): writeDescriptor() - uuid: 00002902-0000-1000-8000-00805f9b34fb
05-26 16:41:27.172: D/BluetoothGatt(31147): onDescriptorWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff0e-0000-1000-8000-00805f9b34fb


05-26 16:41:33.167: D/BluetoothGatt(31147): readCharacteristic() - uuid: 0000ff06-0000-1000-8000-00805f9b34fb													读取 REALTIME_STEPS
05-26 16:41:33.267: D/BluetoothGatt(31147): onCharacteristicRead() - Device=88:0F:10:80:A2:4A UUID=0000ff06-0000-1000-8000-00805f9b34fb Status=0


05-26 16:41:33.292: D/BluetoothGatt(31147): writeCharacteristic() - uuid: 0000ff05-0000-1000-8000-00805f9b34fb													
05-26 16:41:33.357: D/BluetoothGatt(31147): onCharacteristicWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff05-0000-1000-8000-00805f9b34fb Status=0


05-26 16:41:33.837: D/BluetoothGatt(31147): writeCharacteristic() - uuid: 0000ff04-0000-1000-8000-00805f9b34fb													写入 userinfo
05-26 16:41:33.947: D/BluetoothGatt(31147): onNotify() - Device=88:0F:10:80:A2:4A UUID=0000ff03-0000-1000-8000-00805f9b34fb
05-26 16:41:34.007: D/BluetoothGatt(31147): onCharacteristicWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff04-0000-1000-8000-00805f9b34fb Status=0


05-26 16:41:36.162: D/BluetoothGatt(31147): writeCharacteristic() - uuid: 0000ff0a-0000-1000-8000-00805f9b34fb													写入时间
05-26 16:41:36.247: D/BluetoothGatt(31147): onCharacteristicWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff0a-0000-1000-8000-00805f9b34fb Status=0

05-26 16:41:36.282: D/BluetoothGatt(31147): readCharacteristic() - uuid: 0000ff0a-0000-1000-8000-00805f9b34fb													读取时间
05-26 16:41:36.382: D/BluetoothGatt(31147): onCharacteristicRead() - Device=88:0F:10:80:A2:4A UUID=0000ff0a-0000-1000-8000-00805f9b34fb Status=0


05-26 16:41:36.487: D/BluetoothGatt(31147): readCharacteristic() - uuid: 0000ff0c-0000-1000-8000-00805f9b34fb													读取电池
05-26 16:41:36.577: D/BluetoothGatt(31147): onCharacteristicRead() - Device=88:0F:10:80:A2:4A UUID=0000ff0c-0000-1000-8000-00805f9b34fb Status=0


05-26 16:41:36.707: D/BluetoothGatt(31147): readCharacteristic() - uuid: 0000ff01-0000-1000-8000-00805f9b34fb													读取 device_info
05-26 16:41:36.772: D/BluetoothGatt(31147): onCharacteristicRead() - Device=88:0F:10:80:A2:4A UUID=0000ff01-0000-1000-8000-00805f9b34fb Status=0


05-26 16:41:37.302: D/BluetoothGatt(31147): readCharacteristic() - uuid: 0000ff09-0000-1000-8000-00805f9b34fb													读取 LE_PARAMS
05-26 16:41:37.407: D/BluetoothGatt(31147): onCharacteristicRead() - Device=88:0F:10:80:A2:4A UUID=0000ff09-0000-1000-8000-00805f9b34fb Status=0

05-26 16:41:37.892: D/BluetoothGatt(31147): readCharacteristic() - uuid: 0000ff09-0000-1000-8000-00805f9b34fb
05-26 16:41:37.987: D/BluetoothGatt(31147): onCharacteristicRead() - Device=88:0F:10:80:A2:4A UUID=0000ff09-0000-1000-8000-00805f9b34fb Status=0


05-26 16:41:38.022: D/BluetoothGatt(31147): writeCharacteristic() - uuid: 0000ff05-0000-1000-8000-00805f9b34fb
05-26 16:41:38.187: D/BluetoothGatt(31147): onNotify() - Device=88:0F:10:80:A2:4A UUID=0000ff07-0000-1000-8000-00805f9b34fb
05-26 16:41:38.212: D/BluetoothGatt(31147): onNotify() - Device=88:0F:10:80:A2:4A UUID=0000ff07-0000-1000-8000-00805f9b34fb
05-26 16:41:38.267: D/BluetoothGatt(31147): onNotify() - Device=88:0F:10:80:A2:4A UUID=0000ff07-0000-1000-8000-00805f9b34fb

05-26 16:41:38.332: D/BluetoothGatt(31147): onCharacteristicWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff05-0000-1000-8000-00805f9b34fb Status=0
05-26 16:41:38.352: D/BluetoothGatt(31147): onNotify() - Device=88:0F:10:80:A2:4A UUID=0000ff07-0000-1000-8000-00805f9b34fb
05-26 16:41:38.427: D/BluetoothGatt(31147): onNotify() - Device=88:0F:10:80:A2:4A UUID=0000ff07-0000-1000-8000-00805f9b34fb
05-26 16:41:38.462: D/BluetoothGatt(31147): onNotify() - Device=88:0F:10:80:A2:4A UUID=0000ff07-0000-1000-8000-00805f9b34fb

05-26 16:41:38.797: D/BluetoothGatt(31147): writeCharacteristic() - uuid: 0000ff05-0000-1000-8000-00805f9b34fb
05-26 16:41:38.867: D/BluetoothGatt(31147): onCharacteristicWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff05-0000-1000-8000-00805f9b34fb Status=0

05-26 16:41:38.932: D/BluetoothGatt(31147): writeCharacteristic() - uuid: 0000ff05-0000-1000-8000-00805f9b34fb
05-26 16:41:39.012: D/BluetoothGatt(31147): onCharacteristicWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff05-0000-1000-8000-00805f9b34fb Status=0

05-26 16:41:43.392: D/BluetoothGatt(31147): writeCharacteristic() - uuid: 0000ff05-0000-1000-8000-00805f9b34fb
05-26 16:41:43.507: D/BluetoothGatt(31147): onNotify() - Device=88:0F:10:80:A2:4A UUID=0000ff03-0000-1000-8000-00805f9b34fb
05-26 16:41:43.522: D/BluetoothGatt(31147): onCharacteristicWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff05-0000-1000-8000-00805f9b34fb Status=0

05-26 16:41:56.712: D/BluetoothGatt(31147): readCharacteristic() - uuid: 0000ff06-0000-1000-8000-00805f9b34fb
05-26 16:41:56.862: D/BluetoothGatt(31147): onCharacteristicRead() - Device=88:0F:10:80:A2:4A UUID=0000ff06-0000-1000-8000-00805f9b34fb Status=0

05-26 16:41:56.897: D/BluetoothGatt(31147): writeCharacteristic() - uuid: 0000ff05-0000-1000-8000-00805f9b34fb
05-26 16:41:57.082: D/BluetoothGatt(31147): onCharacteristicWrite() - Device=88:0F:10:80:A2:4A UUID=0000ff05-0000-1000-8000-00805f9b34fb Status=0




setUserInfo:uid:20279577,gender:1,age:32,height:180,weight:55,alias:胖梁,type:35,data:[25, 113, 53, 1, 1, 32, -76, 55, 1, -24, -125, -106, -26, -94, -127, 0, 0, 0, 0, 35]




04

[25, 113, 53, 1, 1, 32, -83, 55, 1, -24, -125, -106, -26, -94, -127, 0, 0, 0, 0, 35]

0a
[15, 4, 26, 17, 6, 58, -1, -1, -1, -1, -1, -1]

[5, 0, 64, 31]
05
[4, 0, 1, 15, 4, 26, 7, 0, 0, 0, 31]

05
[4, 1, 0, 15, 4, 21, 8, 0, 29, 0, 31]

[4, 2, 0, 15, 4, 21, 8, 0, 29, 0, 31]

[14, 0, 6, 6, 0]

[15, 0]


02
[0]