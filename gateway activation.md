- To activate the VeloCloud Gateway (VCG), use the following command:
  
  ```
  sudo /opt/vc/bin/activate.py -p -s [velocloud_orchestrator] -i [activation-key]
  ```
  - Options:
    - `-p` option to display activaction progress
  
    - `-s` option to indicate the VeloCloud server/orchestrator
  
    - `[velocloud_orchestrator]` the IP address or FQDN or VeloCloud Orchestrator such as `11.22.33.44` or `vco.fake.com`
  
    - `-i` option to ignore SSL certificate error
  
    - `[activation-key]` the activation key such as `AAAA-BBBB-CCCC-DDDD` for the VeloCloud Gateway
