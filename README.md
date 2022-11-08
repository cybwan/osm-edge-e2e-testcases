# E2E TEST REPORT FOR TAG:v1.2.+

| No  | Context                                                      | ARM64 Result | AMD64 Result |
|-----| ------------------------------------------------------------ | ------------ | ------------ |
| 01  |CertManagerSimpleClientServer|Passed|Passed|
| 02  |Test traffic flowing from client to server with a Kubernetes Service for the Source: HTTP|Passed|Passed|
| 03  |Test traffic flowing from client to server without a Kubernetes Service for the Source: HTTP|Passed|Passed|
| 04  |Test traffic flowing from client to a server with a podIP bind|Passed|Passed|
| 05  |SimpleClientServer traffic test involving osm-controller restart: HTTP|Passed|Passed|
| 06  |DebugServer|Passed|Passed|
| 07  |DeploymentsClientServer|Passed|Passed|
| 08  |HTTP egress policy without route matches|Passed|Passed|
| 09  | HTTP egress policy with route match                                   |Passed|Passed|
| 10  | HTTPS egress policy                                                   |Passed|Passed|
| 11  | TCP egress policy                                                     |Passed|Passed|
| 12  |Egress|Passed|Passed|
| 13  |Fluent Bit deployment|Passed|Passed|
| 14  |Fluent Bit output|Passed|Passed|
| 15  |Garbage Collection|Passed|Passed|
| 16  |gRPC insecure traffic origination over HTTP2 with SMI HTTP routes|Passed|Passed|
| 17  |gRPC secure traffic origination over HTTP2 with SMI TCP routes|Passed|Passed|
| 18  |HashivaultSimpleClientServer|Passed|Passed|
| 19  |Test health probes can succeed|Passed|Passed|
| 20  |Helm install using default values|Passed|Passed|
| 21  |Ignore Label|Passed|Passed|
| 22  |HTTP ingress with IngressBackend|Passed|Passed|
| 23  |When OSM is Installed|Passed|Passed|
| 24  |Test IP range exclusion|Passed|Passed|
| 25  |HTTP request rate limiting|Passed|Passed|
| 26  |Custom WASM metrics between one client pod and one server|Skip|Skip|
| 27  |Multiple service ports|Passed|Passed|
| 28  |Multiple services matching same pod|Passed|Passed|
| 29  |Test reinstalling OSM in the same namespace with the same mesh name|Passed|Passed|
| 30  |PermissiveToSmiSwitching|Passed|Passed|
| 31  |Permissive mode HTTP test with a Kubernetes Service for the Source|Passed|Passed|
| 32  | Permissive mode HTTP test without a Kubernetes Service for the Source |Passed|Passed|
| 33  |Test global port exclusion|Passed|Passed|
| 34  | Test pod level port exclusion               |Passed|Passed|
| 35  |proxy resources|Passed|Passed|
| 36  |Enable Reconciler|Passed|Passed|
| 37  |Retry policy disabled|Passed|Passed|
| 38  | Retry policy enabled                        |Passed|Passed|
| 39  |SMI Traffic Target is not in the same namespace as the destination|Passed|Passed|
| 40  | SMI TrafficTarget is set up properly        |Passed|Passed|
| 41  |Statefulsets|Passed|Passed|
| 42  |SimpleClientServer TCP with SMI policies|Skip|Skip|
| 43  | SimpleClientServer TCP in permissive mode   |Skip|Skip|
| 44  |SimpleClientServer egress TCP|Passed|Passed|
| 45  |TCP server-first traffic|Skip|Skip|
| 46  |HTTP recursive traffic splitting with SMI|Passed|Passed|
| 47  | TCP recursive traffic splitting with SMI    |Passed|Passed|
| 48  |ClientServerTrafficSplitSameSA|Passed|Passed|
| 49  |HTTP traffic splitting with SMI|Passed|Passed|
| 50  | TCP traffic splitting with SMI              |Passed|Passed|
| 51  | HTTP traffic splitting with Permissive mode |Passed|Passed|
| 52  |Upgrade from latest|Passed|Passed|
| 53  |With SMI Traffic Target validation enabled |Passed|Passed|
| 54  |  With SMI validation disabled |Passed|Passed|


Read more about [test.e2e.xlsx](test.e2e.xlsx)