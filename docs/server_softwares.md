# Softwares on Climet Server

| Software     | Discription   | Version    |
| ------------ | ------------- | ------------ |
| [**VNC**](#vnc)| Virtual Network Computing| TigerVNC 1.13.0 |
| [**Matlab**](#matlab)| [HKUST acadamic license](https://download.ust.hk/apps/site/info/matlab2023a.html)  | Matlab 2023a |
| [**Miniconda**](#miniconda)| Python Env. Manager | V23.5.0 |

## [Virtual Network Computing (VNC)](#vnc)

### Configuration at Server Point
1. Log in the server using ***ssh*** command on your local computer: <br>
    `ssh [username]@[xxx.xxx.xxx.xxx server ip address]`

2. Set the password for the vnc connection on your local computer: <br>
    `vncpasswd`

3. Start the vnc server: <br>
    `vncserver -localhost no`

4. Check the vnc server status and the port # (DISPLAY #): <br>
    `vncserver -list`

### Configuration at Client Point

You can use the vnc viewer client to connect the vnc server created as above. <br>
vnc viewer clients <br>

+ [TigerVNC viewer](https://tigervnc.org)
+ [RealVNC viewer](https://www.realvnc.com/en/)

### Stop the vnc Server
If you want to stop vnc server, you just kill the server via terminal command on your local computer. <br>
`vncserver -kill:*` <br>
'*' is for all vnc servers; you can use number to kill a specific port.

        
## [Matlab](#matlab)

## [Miniconda](#miniconda)
