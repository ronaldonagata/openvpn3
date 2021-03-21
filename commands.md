openvpn3 config-import --config <name_config>.ovpn  --name "<name>" 
  
openvpn3 configs-list 

openvpn3 sessions-list 

openvpn3 session-start --config <name> 

openvpn3 session-manage --config <name>  --disconnect 

openvpn3 config-remove --config "<name>" 
