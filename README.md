My local ipfs.
Install syncthing on 2 computers.
Install tail scale.
Enter tailscale's ips in syncthing.
Changes the config of your ipfs. enter your tailscale ips here.
Use your own made swarm key.

Install Netbird
Use Head Scale.
Add registry keys
To make the Windows client behave as expected and to run well with headscale, two registry keys must be set:

HKLM:\SOFTWARE\Tailscale IPN\UnattendedMode must be set to always as a string type, to allow Tailscale to run properly in the background
HKLM:\SOFTWARE\Tailscale IPN\LoginURL must be set to <YOUR HEADSCALE URL> as a string type, to ensure Tailscale contacts the correct control server.
