# React-Native-RHDeviceInfo[![npm version](https://badge.fury.io/js/react-native-rhdevice-info.svg)](http://badge.fury.io/js/react-native-rhdevice-info)

## **瑞昊RN项目获取工程信息工具**

## Install 安装
* npm install react-native-rhdevice-info --save


## link
* react-native link react-native-rhdevice-info 


## API

| Method                                            | Return Type         |  iOS | Android | Windows | 
| ------------------------------------------------- | ------------------- | :--: | :-----: | :-----: | ------ |
| [getAPILevel()](#getapilevel)                     | `number`            |  ❌  |   ✅    |   ❌    | 
| [getApplicationName()](#getapplicationname)       | `string`            |  ✅  |   ✅    |   ✅    |
| [getBrand()](#getbrand)                           | `string`            |  ✅  |   ✅    |   ✅    | 
| [getBuildNumber()](#getbuildnumber)               | `string`            |  ✅  |   ✅    |   ✅    | 
| [getBundleId()](#getbundleid)                     | `string`            |  ✅  |   ✅    |   ✅    | 
| [getCarrier()](#getcarrier)                       | `string`            |  ✅  |   ✅    |   ❌    | 
| [getDeviceCountry()](#getdevicecountry)           | `string`            |  ✅  |   ✅    |   ✅    | 
| [getDeviceId()](#getdeviceid)                     | `string`            |  ✅  |   ✅    |   ✅    | 
| [getDeviceLocale()](#getdevicelocale)             | `string`            |  ✅  |   ✅    |   ✅    | 
| [getDeviceName()](#getdevicename)                 | `string`            |  ✅  |   ✅    |   ✅    | 
| [getAppName()](#getappname)                 | `string`            |  ✅  |   ✅    |    ❌    | 
| [getFirstInstallTime()](#getfirstinstalltime)     | `number`            |  ❌  |   ✅    |   ❌    | 
| [getFontScale()](#getfontscale)                   | `number`            |  ✅  |   ✅    |   ❌    |
| [getFreeDiskStorage()](#getfreediskstorage)       | `number`            |  ✅  |   ✅    |   ❌    | 
| [getIPAddress()](#getipaddress)                   | `Promise<string>`   |  ❌  |   ✅    |   ❌    | 
| [getInstanceID()](#getinstanceid)                 | `string`            |  ❌  |   ✅    |   ❌    | 
| [getLastUpdateTime()](#getlastupdatetime)         | `number`            |  ❌  |   ✅    |   ❌    | 
| [getMACAddress()](#getmacaddress)                 | `Promise<string>`   |  ❌  |   ✅    |   ❌    | 
| [getManufacturer()](#getmanufacturer)             | `string`            |  ✅  |   ✅    |   ✅    | 
| [getMaxMemory()](#getmaxmemory)                   | `number`            |  ❌  |   ✅    |   ❌    | 
| [getModel()](#getmodel)                           | `string`            |  ✅  |   ✅    |   ✅    | 
| [getPhoneNumber()](#getphonenumber)               | `string`            |  ❌  |   ✅    |   ❌    | 
| [getReadableVersion()](#getreadableversion)       | `string`            |  ✅  |   ✅    |   ✅    | 
| [getSerialNumber()](#getserialnumber)             | `string`            |  ❌  |   ✅    |   ❌    | 
| [getSystemName()](#getsystemname)                 | `string`            |  ✅  |   ✅    |   ✅    | 
| [getSystemVersion()](#getsystemversion)           | `string`            |  ✅  |   ✅    |   ✅    | 
| [getTimezone()](#gettimezone)                     | `string`            |  ✅  |   ✅    |   ✅    |
| [getTotalDiskCapacity()](#gettotaldiskcapacity)   | `number`            |  ✅  |   ✅    |   ❌    | 
| [getTotalMemory()](#gettotalmemory)               | `number`            |  ✅  |   ✅    |   ❌    | 
| [getUniqueID()](#getuniqueid)                     | `string`            |  ✅  |   ✅    |   ✅    | 
| [getUserAgent()](#getuseragent)                   | `string`            |  ✅  |   ✅    |   ❌    | 
| [getVersion()](#getversion)                       | `string`            |  ✅  |   ✅    |   ✅    | 
| [is24Hour()](#is24hour)                           | `boolean`           |  ✅  |   ✅    |   ✅    | 
| [isEmulator()](#isemulator)                       | `boolean`           |  ✅  |   ✅    |   ✅    | 
| [isPinOrFingerprintSet()](#ispinorfingerprintset) | (callback)`boolean` |  ✅  |   ✅    |   ❌    | 
| [isTablet()](#istablet)                           | `boolean`           |  ✅  |   ✅    |   ✅    | 

---


