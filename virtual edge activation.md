A checklist to get a VeloCloud Virtual Edge up and running:

- On VeloCloud Orchstrator, check whether Edge profile supports Virtual Edge model:
  
  <img width="358" alt="image" src="https://github.com/user-attachments/assets/6605762f-87fe-4904-a899-82a3f623754e" />

- On VeloCloud Orchestrator, check Software images for Virtual Edge model:

  <img width="569" alt="image" src="https://github.com/user-attachments/assets/0b0daa2f-2607-43ba-9f7a-5e59c86a6a3f" />

- On VeloCloud Orchstrator, check Operator profile supports Virtual Edge model:

  <img width="739" alt="image" src="https://github.com/user-attachments/assets/6241116c-ef40-4778-8d5f-552c2a615910" />

- On VeloCloud Orchstrator, provision an Edge with Virtual Edge model:

  <img width="639" alt="image" src="https://github.com/user-attachments/assets/667cd61d-fb78-45fe-beba-7c53c4ce728b" />

- Activate the Virtual Edge with following command:
  ```
  activate.py -p -s [velocloud_orchestrator] -i [activation-key]
  ```
  `-p` option to display activaction progress.
  
  `-s` option to indicate the VeloCloud server/orchestrator.
  
  `[velocloud_orchestrator]` the IP address or FQDN or VeloCloud Orchestrator such as 11.22.33.44 or vco.fake.com.
  
  `-i` option to ignore certificate error.
  
  `[activation-key]` the activation key such as AAAA-BBBB-CCCC-DDDD for the Virtual Edge.

