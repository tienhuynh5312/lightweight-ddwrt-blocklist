## Lightweight DD-WRT Blocklist

This is an **intentionally small** list of advertising and analytic domains for blocking in custom router firmware, such as DD-WRT and Tomato. The list is in DNSMasq configuration format.

The intention of this list is to block common advertising and analytics domains without overwhelming consumer routers with lists containing 5000+ lines.

### Installation

Copy the contents of **list.txt** into `Additional DNSMasq Options` under `Services > Services > DNSMasq` in the DD-WRT Control Panel. Instructions vary for other firmware.

Ensure DNSMasq is enabled, and client devices are using **only** the IP address of the router for DNS.

---

#### Privacy

This list is solely a text file, and is not capable of collecting user data. 

All blocked domains are redirected to the invalid IP address `0.0.0.0`.

#### License

Copyright 2017 Aaron Horler

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
