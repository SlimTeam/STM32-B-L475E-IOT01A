# STM32-B-L475E-IOT01A Scriptr.io connectivity
This is an update to the [X-CUBE-CLD-GEN Expansion Package](https://www.st.com/en/embedded-software/x-cube-cld-gen.html) in order to allow for pub/sub topic customization.

## Connection string format
Default connection string: HostName=xxx;HostPort=xxx;ConnSecurity=x;MQClientId=xxx;MQUserName=xxx;MQUserPwd=xxx;
Updated connection string: HostName=xxx;HostPort=xxx;ConnSecurity=x;MQClientId=xxx;MQUserName=xxx;MQUserPwd=xxx;PublicationTopic=xxx;SubscriptionTopic=xxx;

## Code updates


## Installation
For step by step instructions, check out our [blog entry](https://blog.scriptr.io/[missing-blog-entry])

### Binary
The binary folder contains the builts package based on the modified code.
For testing purposes, you will only need to paste the provided bin (B-L475E-IOT01_GenericMQTT.bin) on your device.
Once the device restarts, you can configure all parameters from the terminal.

### Compilation 
The updated files are provided in this repository. 
Before compiling, you will need to replace the files by the provided ones. The easiest would be to paste the full directory structure as-is on top of the unzipped [X-CUBE-CLD-GEN Expansion Package](https://www.st.com/en/embedded-software/x-cube-cld-gen.html)

You can also use the provided diffs under the diff folder.








