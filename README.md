node try.js mintip github
node try.js mintip bitbucket

var config = `Host github.com
	HostName github.com
	Port 22
	user git
	IdentityFile ~/.ssh/Home-2019-10-27

Host bitbucket.com
	HostName bitbucket.com
	Port 22
	user git
	IdentityFile ~/.ssh/Home-2019-10-27

Host pi1
	HostName 192.168.86.40
	Port 22
	User pi
	IdentityFile ~/.ssh/Home-2019-10-27

Host pi2
	HostName 192.168.86.37
	Port 22
	User pi
	IdentityFile ~/.ssh/Home-2019-10-27

Host mint
	HostName 192.168.86.37
	Port 22
	User charlie
	IdentityFile ~/.ssh/Home-2019-10-27

Host us01
	HostName 23.12.12.16
	Port 22
	User charlie
	IdentityFile ~/.ssh/Home-2019-10-27`