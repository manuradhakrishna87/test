# test
This is used for testing only
from netmiko import ConnectHandler
net_connect = ConnectHandler(device_type="cisco_xe", ip= "10.222.72.120", username="mradhakrishna",
                                 password="Gm!WelC0mE", secret = "netv1Shn!")
output = net_connect.enable()
net_connect.send_command("ping \n")
net_connect.send_command("\n")
net_connect.send_command("8.8.8.8")
net_connect.send_command("100")
net_connect.send_command("\n")
net_connect.send_command("n")
net_connect.send_command("\n")
