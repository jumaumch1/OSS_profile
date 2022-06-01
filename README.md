# OSS_profile

#### Application attributes

* `VideoStreamServer`

| Attribute name | Type | Default | Description |
| ----------- | ------ | ------ | ------------- |
| `Interval` | TimeValue | Seconds(0.15) | The time to wait between packets |
| `Port` | UintegerValue | 5000 | Port on which we listen for incoming packets. |
| `MaxPacketSize` | UintegerValue | 1400 | The maximum size of a packet |
| `FrameFile` | StringValue | None | The file that contains the video frame sizes |
| `VideoLength` | UintegerValue | 60 | The length of the video in seconds |

* `VideoStreamClient`

| Attribute name | Type | Default | Description |
| ----------- | ------ | ------ | ------------- |
| `RemoteAddress` | AddressValue | None | The destination address of the outbound packets |
| `RemotePort` | UintegerValue | 5000 | The destination port of the outbound packets |
| `IsRTP` | BooleanValue | True | True if the client wants to use RTP |



#### Log Component

| Log Component | Application |
| ----------- | ------ |
| VideoStreamServerApplication | video-steram-server |
| VideoStreamClientApplication | video-steram-client |


`[LICENSE]`(https://github.com/nsnam/ns-3-dev-git/blob/master/LICENSE)
