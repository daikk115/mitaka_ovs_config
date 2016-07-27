- Some errors that I faced:
 + NoSuchOptError: no such option in group neutron: auth_plugin
   https://github.com/openstack/keystoneauth/commit/a56ed4218aef5a2e528aa682cea967e767dca923

- Some tips:
 + May be, we don't need config br-ex and eth0 <public NIC> by:
	sudo ifconfig eth0 0
	dhclient br-ex
   every times we restart system. But it's so stupid!!!
