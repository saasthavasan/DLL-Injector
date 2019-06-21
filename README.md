# DLL-Injector

## **About:**

### **DLL-Injection:**
DLL injection refers to the technique of inserting code in the form of a DLL either by inserting the address of the DLL or the entire code of the DLL in the address space of a process and that process is made to execute that injected code.

DLL injection can be helpful in many ways like it can be used for patching a process without actually terminating the process or it can be used to add extra features to a process like themes. At the same time DLL injection can also be used for malicious practices. A malware can perform DLL injection on a legitimate process for acquiring passwords from a text box or it can read and access sensitive data present on the system.




## **How to Use**:
In cmd type the following command:
```cmd
Dllinjector.exe -[option]
```
Various options that are currently available:
```
[-h] ---> help
[-il] ---> inject the DLL using the loadLibraryA() API
[-im] ---> inject the DLL by executing its code in the process.
```

## **Todo**:
- Make LoadLibraryA() injector.
- Make Memory injector.


## **Warning**:
As this software is **PROVIDED WITH ABSOLUTELY NO WARRANTY OF ANY KIND,YOU USE THIS TOOL AT YOUR OWN RISK!**
