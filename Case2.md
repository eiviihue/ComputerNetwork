<img width="1062" height="874" alt="image" src="https://github.com/user-attachments/assets/3e54b7c1-5de1-4dbe-870c-bec132baa7db" /># Problem 2.1
## Topology
<img width="1919" height="1041" alt="image" src="https://github.com/user-attachments/assets/c19b53be-4aff-4728-9c94-852ee1c7d126" />

## IP addresses
<img width="1072" height="294" alt="image" src="https://github.com/user-attachments/assets/ec19dfe2-84a7-4579-b06f-9f61a8e9b239" />
<img width="1073" height="280" alt="image" src="https://github.com/user-attachments/assets/6a8324f3-4339-45eb-99d6-7ad8041be2aa" />
<img width="1078" height="300" alt="image" src="https://github.com/user-attachments/assets/53d14319-6d24-43fc-841b-65f60a909063" />
<img width="1073" height="287" alt="image" src="https://github.com/user-attachments/assets/aa856083-17b5-4777-be24-6fd1958e6ba3" />

## Ping Check
### PC 1 to 2,3,4
<img width="1072" height="788" alt="image" src="https://github.com/user-attachments/assets/3eb3cb58-c524-4490-93f5-1f21e2b6869c" />
### PC 2 to 3,4
<img width="1084" height="566" alt="image" src="https://github.com/user-attachments/assets/f3320af6-dc2d-4dea-833e-9761d222bd84" />
### PC 3 to 4
<img width="1088" height="492" alt="image" src="https://github.com/user-attachments/assets/c8a4eef2-001f-4b60-b796-e5e9af121ed9" />

## Add PC 5 and do network capture using termshark
## Topology
<img width="1236" height="797" alt="image" src="https://github.com/user-attachments/assets/af627275-8c5f-406b-85cb-bdffd2a6f272" />

## Send ping PC 1 to PC 2 and check in termshark PC 5
<img width="1088" height="341" alt="image" src="https://github.com/user-attachments/assets/305ac049-89c4-47f4-a109-72db441dd2b9" />
<img width="1066" height="858" alt="image" src="https://github.com/user-attachments/assets/1fb8da92-a3a5-405c-9142-7a9c1ca6ce40" />

## Do the same as before but change hub with a switch
<img width="1084" height="356" alt="image" src="https://github.com/user-attachments/assets/8ea4ac52-3056-4aba-89d3-23712765e6cb" />
<img width="1087" height="331" alt="image" src="https://github.com/user-attachments/assets/6dc62659-75f5-4337-b678-d91f1a3e1b76" />
<img width="1075" height="785" alt="image" src="https://github.com/user-attachments/assets/cf75aba9-951c-4c18-8048-2fc7adb072bc" />

As we can see, termshark in PC 5 didn't capture ping from PC 1 to PC 2


# Problem 2.2
## Topology
<img width="1908" height="847" alt="image" src="https://github.com/user-attachments/assets/00ba8435-8b2b-46c7-8d86-ea9966fc7fef" />

## Change DHCP config in PC 1-4 and then close project and open it again
<img width="1199" height="466" alt="image" src="https://github.com/user-attachments/assets/421afd10-9896-4d35-a025-b40bd3ca6b89" />
<img width="1197" height="482" alt="image" src="https://github.com/user-attachments/assets/0d543fe6-cf1b-429c-8753-2f52d6ae7cb9" />
<img width="1204" height="400" alt="image" src="https://github.com/user-attachments/assets/91bffed1-87d2-4af9-8ca3-deb75103c3b2" />
<img width="1171" height="499" alt="image" src="https://github.com/user-attachments/assets/248ec3aa-b203-421c-855c-d6f9f2f6af75" />

### After restart project
<img width="1085" height="327" alt="image" src="https://github.com/user-attachments/assets/abfa135b-fdbe-41a4-bf5b-86c1fc3c0d09" />
<img width="1084" height="318" alt="image" src="https://github.com/user-attachments/assets/abdbbc6f-7694-4340-9161-8dd0b3568e44" />
<img width="1070" height="298" alt="image" src="https://github.com/user-attachments/assets/d8bf1b23-836b-47d0-bb07-494f70c1d146" />
<img width="1097" height="354" alt="image" src="https://github.com/user-attachments/assets/1e0f5dc8-dde7-4ed7-86b4-d1bf47e85115" />

## Add PC 5 for DHCP server and connect it to the switch
<img width="1085" height="301" alt="image" src="https://github.com/user-attachments/assets/0bbc92e4-b031-4079-a370-51b4de655cfe" />
## Make leases file
<img width="1093" height="386" alt="image" src="https://github.com/user-attachments/assets/0b810374-bc06-419f-af3a-68892e28daf9" />

## Run DHCPD server 
` udhcpd -f /tmp/dhcpd.conf `
<img width="1079" height="862" alt="image" src="https://github.com/user-attachments/assets/5389813d-c89d-42bb-97fc-0dd4e76d715c" />

## Check IP in PC 1-4
<img width="1070" height="451" alt="image" src="https://github.com/user-attachments/assets/e8615980-8377-46cf-85fe-eb4735f3be99" />
<img width="1090" height="456" alt="image" src="https://github.com/user-attachments/assets/98213c06-ff40-4b78-ac1f-97a28854e173" />
<img width="1081" height="446" alt="image" src="https://github.com/user-attachments/assets/5c11a63a-a978-43bb-8270-d115538b56f1" />
<img width="1072" height="446" alt="image" src="https://github.com/user-attachments/assets/0197523f-b125-4d7c-98a2-301920454bee" />

# Problem 2.3
## Add new PC 6
<img width="1919" height="924" alt="image" src="https://github.com/user-attachments/assets/8f5b6ad2-a4f8-4ba9-9ead-ecee547beec3" />

## Check IP for PC 6
<img width="1078" height="316" alt="image" src="https://github.com/user-attachments/assets/558a2c50-dc6c-4771-a742-816637518240" />

## Run a command
` udhcpc -i eth0 -b `
<img width="1079" height="491" alt="image" src="https://github.com/user-attachments/assets/4fe450c2-ccdc-4bbe-a665-6e0da135dbf0" />

# Problem 2.4
## Add new PC 7
<img width="1836" height="794" alt="image" src="https://github.com/user-attachments/assets/8cdc0179-747b-4498-b719-790b24fc42e6" />

## Do termshark for capturing network activities that involve DHCP (restart PC 4)
<img width="1073" height="262" alt="image" src="https://github.com/user-attachments/assets/b17910c2-da1b-45dd-b4b2-8483e77e48d6" />
<img width="1073" height="262" alt="image" src="https://github.com/user-attachments/assets/52b24123-0e96-4686-965a-894d972c9459" />




