# Configuration du switch

int f0/1
switchport mode trunk
switchport trunk allowed Vlan all
exit

int f0/13
switchport mode trunk
switchport trunk allowed Vlan all
exit

int f0/25
switchport mode trunk
switchport trunk allowed Vlan all
exit

vlan 10
vlan 20
vlan 30
vlan 40
vlan 50
vlan 60
vlan 70
vlan 80
vlan 90
vlan 240
