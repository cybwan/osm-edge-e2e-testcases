# E2E TEST REPORT FOR TAG:v1.2.0-arm

| No   | Context                                                      | ARM64 Result | AMD64 Result |
| ---- | ------------------------------------------------------------ | ------------ | ------------ |
| 01	| CertManagerSimpleClientServer |	Passed |	Passed |
| 02	| SimpleClientServer traffic test involving osm-controller restart: HTTP |	Passed |	Passed |
| 03	| DebugServer |	Passed |	Passed |
| 04	| DeploymentsClientServer |	Passed |	Passed |
| 05	| HTTP egress policy without route matches |	Passed |	Passed |
| 06	| HTTP egress policy with route match |	Passed |	Passed |
| 07	| HTTPS egress policy |	Passed |	Passed |
| 08	| TCP egress policy |	Passed |	Passed |
| 09	| Egress |	Passed |	Passed |
| 10	| Fluent Bit deployment |	Passed |	Passed |
| 11	| Fluent Bit output |	Passed |	Passed |
| 12	| Garbage Collection |	Passed |	Passed |
| 13	| gRPC insecure traffic origination over HTTP2 with SMI HTTP routes |	Passed |	Passed |
| 14	| gRPC secure traffic origination over HTTP2 with SMI TCP routes |	Passed |	Passed |
| 15	| HashivaultSimpleClientServer |	Passed |	Passed |
| 16	| Test health probes can succeed |	Passed |	Passed |
| 17	| Helm install using default values |	Passed |	Passed |
| 18	| Ignore Label |	Passed |	Passed |
| 19	| HTTP ingress with IngressBackend |	Passed |	Passed |
| 20	| When OSM is Installed |	Passed |	Passed |
| 21	| Test IP range exclusion |	Passed |	Passed |
| 22	| Version v1.23.6 |	Passed |	Passed |
| 23	| Version v1.22.9 |	Passed |	Passed |
| 24	| Version v1.21.12 |	Passed |	Passed |
| 25	| Version v1.20.15 |	Passed |	Passed |
| 26	| Version v1.19.16 |	Passed |	Passed |
| 27	| Custom WASM metrics between one client pod and one server |	Skip	| Skip |
| 28	| Multiple service ports |	Passed |	Passed |
| 29	| Multiple services matching same pod |	Passed |	Passed |
| 30	| Becomes ready after being reinstalled |	Passed |	Passed |
| 31	| PermissiveToSmiSwitching |	Passed |	Passed |
| 32	| Permissive mode HTTP test with a Kubernetes Service for the Source |	Passed |	Passed |
| 33	| Permissive mode HTTP test without a Kubernetes Service for the Source |	Passed |	Passed |
| 34	| Test traffic flowing from client to server with a Kubernetes Service for the Source: HTTP |	Passed |	Passed |
| 35	| Test traffic flowing from client to server without a Kubernetes Service for the Source: HTTP |	Passed |	Passed |
| 36	| Test global port exclusion |	Passed |	Passed |
| 37	| Test pod level port exclusion |	Passed |	Passed |
| 38	| proxy resources |	Passed |	Passed |
| 39	| Enable Reconciler |	Passed |	Passed |
| 40	| SMI TrafficTarget is set up properly |	Passed |	Passed |
| 41	| SMI Traffic Target is not in the same namespace as the destination |	Passed |	Passed |
| 42	| SimpleClientServer TCP with SMI policies |	Passed |	Passed |
| 43	| SimpleClientServer TCP in permissive mode |	Passed |	Passed |
| 44	| SimpleClientServer egress TCP |	Passed |	Passed |
| 45	| TCP server-first traffic |	Passed |	Passed |
| 46	| HTTP recursive traffic splitting with SMI |	Passed |	Passed |
| 47	| TCP recursive traffic splitting with SMI |	Passed |	Passed |
| 48	| ClientServerTrafficSplitSameSA |	Passed |	Passed |
| 49	| HTTP traffic splitting - root service selector matches backends |	Passed |	Passed |
| 50	| HTTP traffic splitting with SMI |	Passed |	Passed |
| 51	| TCP traffic splitting with SMI |	Passed |	Passed |
| 52	| HTTP traffic splitting with Permissive mode |	Passed |	Passed |
| 53	| Tests upgrading the control plane |	Passed |	Passed |
| 51	| With SMI Traffic Target validation enabled |	Passed |	Passed |
| 52	| With SMI validation disabled |	Passed |	Passed |


Read more about [test.e2e.xlsx](test.e2e.xlsx)