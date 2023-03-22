HI , I Use the Win10 PowerShell can connect the aliyun servers with windows system server 08 .
But , when i use the vs code to connect the server , can not work.

i have install the Remote ssh on the stroe . 
the follow information is by vscode ：
=================================================


[18:14:59.560] Log Level: 2
[18:14:59.574] SSH Resolver called for "ssh-remote+47.98.232.27", attempt 1
[18:14:59.575] "remote.SSH.useLocalServer": false
[18:14:59.575] "remote.SSH.showLoginTerminal": true
[18:14:59.575] "remote.SSH.remotePlatform": {}
[18:14:59.575] "remote.SSH.path": undefined
[18:14:59.576] "remote.SSH.configFile": undefined
[18:14:59.576] "remote.SSH.useFlock": true
[18:14:59.576] "remote.SSH.lockfilesInTmp": false
[18:14:59.576] "remote.SSH.localServerDownload": auto
[18:14:59.576] "remote.SSH.remoteServerListenOnSocket": false
[18:14:59.576] "remote.SSH.showLoginTerminal": true
[18:14:59.577] "remote.SSH.defaultExtensions": []
[18:14:59.579] "remote.SSH.loglevel": 2
[18:14:59.579] "remote.SSH.enableDynamicForwarding": true
[18:14:59.579] "remote.SSH.enableRemoteCommand": false
[18:14:59.580] "remote.SSH.serverPickPortsFromRange": {}
[18:14:59.580] "remote.SSH.serverInstallPath": {}
[18:14:59.587] VS Code version: 1.76.2
[18:14:59.587] Remote-SSH version: remote-ssh@0.98.0
[18:14:59.588] win32 x64
[18:14:59.589] SSH Resolver called for host: 47.98.232.27
[18:14:59.590] Setting up SSH remote "47.98.232.27"
[18:14:59.597] Using commit id "ee2b180d582a7f601fa6ecfdad8d9fd269ab1884" and quality "stable" for server
[18:14:59.604] Install and start server if needed
[18:15:01.068] Checking ssh with "C:\WINDOWS\system32\ssh.exe -V"
[18:15:01.071] Got error from ssh: spawn C:\WINDOWS\system32\ssh.exe ENOENT
[18:15:01.071] Checking ssh with "C:\WINDOWS\ssh.exe -V"
[18:15:01.072] Got error from ssh: spawn C:\WINDOWS\ssh.exe ENOENT
[18:15:01.073] Checking ssh with "C:\WINDOWS\System32\Wbem\ssh.exe -V"
[18:15:01.074] Got error from ssh: spawn C:\WINDOWS\System32\Wbem\ssh.exe ENOENT
[18:15:01.074] Checking ssh with "C:\WINDOWS\System32\WindowsPowerShell\v1.0\ssh.exe -V"
[18:15:01.076] Got error from ssh: spawn C:\WINDOWS\System32\WindowsPowerShell\v1.0\ssh.exe ENOENT
[18:15:01.076] Checking ssh with "C:\WINDOWS\System32\OpenSSH\ssh.exe -V"
[18:15:01.106] > OpenSSH_for_Windows_8.1p1, LibreSSL 3.0.2

[18:15:01.111] Remote command length: 6211/8192 characters
[18:15:01.111] Running script with connection command: "C:\WINDOWS\System32\OpenSSH\ssh.exe" -T -D 50008 "47.98.232.27" powershell
[18:15:01.114] Terminal shell path: C:\WINDOWS\System32\cmd.exe
[18:15:02.525] > administrator@47.98.232.27's password:]0;C:\WINDOWS\System32\cmd.exe
[18:15:02.526] Got some output, clearing connection timeout
[18:15:02.552] > [8;12;216tadministrator@47.98.232.27's password:
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
[18:15:07.287] > 
[18:15:07.340] > Permission denied, please try again.
[18:15:07.348] > administrator@47.98.232.27's password: 
[18:15:10.911] > 
[18:15:10.964] > Permission denied, please try again.
[18:15:10.984] > administrator@47.98.232.27's password: 
[18:15:14.193] > 
[18:15:15.922] > Windows PowerShell 
> Copyright (C) 2016 Microsoft Corporation. All rights reserved.PS C:\Users\Administrator> 
> PS C:\Users\Administrator> $uuid="3231e8089136"
> PS C:\Users\Administrator> "${uuid}: running"
> 3231e8089136: running
> PS C:\Users\Administrator> "3231e8089136: pauseLog"
> 3231e8089136: pauseLog
[18:15:17.026] > 
[18:15:17.046] > 3231e8089136: resumeLog
[18:15:17.062] > 
> PS C:\Users\Administrator> main
[18:15:17.077] > 
[18:15:17.872] > Acquiring lock on C:\Users\Administrator\.vscode-server\bin\ee2b180d582a7f601fa6ecfdad8d9fd269ab1884\vscode-remote-lock.ee2b180d582a7f601fa6ecfdad8d9fd269ab1884
[18:15:17.894] > 
> Looking for existing server in C:\Users\Administrator\.vscode-server\bin\ee2b180d582a7f601fa6ecfdad8d9fd269ab1884
[18:15:17.910] > 
> Found installed server
[18:15:17.915] > 
[18:15:17.958] > 
[18:15:17.976] > 
>     Directory: C:\Users\Administrator\.vscode-server
[18:15:17.988] > 
> 
[18:15:18.012] > 
> Mode                LastWriteTime         Length Name
> ----                -------------         ------ ----
> -a----        2023/3/22     18:15              0 .ee2b180d582a7f601fa6ecfdad8d9
>                                                  fd269ab1884.token
[18:15:18.031] > 
[18:15:18.059] > �ѳɹ����� 1 ���ļ�; ���� 0 ���ļ�ʱʧ��
[18:15:18.209] > �ѳɹ����� 1 ���ļ�; ���� 0 ���ļ�ʱʧ��
[18:15:18.315] > �ѳɹ����� 1 ���ļ�; ���� 0 ���ļ�ʱʧ��
[18:15:18.365] > �ѳɹ����� 1 ���ļ�; ���� 0 ���ļ�ʱʧ��
[18:15:18.432] > Starting server: & 'C:\Users\Administrator\.vscode-server\bin\ee2b180d582a7f601fa6ecfdad8d9fd269ab1884\bin\code-server.cmd' --start-server --host=127.0.0.1 --accept-server-license-terms --enable-remote-auto-shutdown 
>  --port=0 --connection-token-file 'C:\Users\Administrator\.vscode-server\.ee2b180d582a7f601fa6ecfdad8d9fd269ab1884.token' --telemetry-level all  *> 'C:\Users\Administrator\.vscode-server\.ee2b180d582a7f601fa6ecfdad8d9
> 9fd269ab1884.log'
[18:15:18.446] > 
[18:15:22.530] > Server did not start successfully. Full server log at C:\Users\Administrator\.vscode-server\.ee2b180d582a7f601fa6ecfdad8d9fd269ab1884.log >>>
> C:\Users\Administrator\.vscode-server\bin\ee2b180d582a7f601fa6ecfdad8d9fd269ab1
> 884\bin\code-server.cmd : Node.js is only supported on Windows 8.1, Windows Ser
[18:15:22.540] > 
> ver 2012 R2, or higher.
> At line:1 char:1
> + C:\Users\Administrator\.vscode-server\bin\ee2b180d582a7f601fa6ecfdad8 ...
[18:15:22.557] > 
> + ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
>     + CategoryInfo          : NotSpecified: (Node.js is only... R2, or higher.
>    :String) [], RemoteException
>     + FullyQualifiedErrorId : NativeCommandError
[18:15:22.589] > 
>  
> Setting the NODE_SKIP_PLATFORM_CHECK environment variable to 1 skips this
[18:15:22.595] > 
> check, but Node.js might not execute correctly. Any issues encountered on
> unsupported platforms will not be fixed.
[18:15:22.608] > <<< End of server log
[18:15:22.618] > 
> 3231e8089136: start
[18:15:22.624] > 
> exitCode==32==
[18:15:22.635] > listeningOn====
> osReleaseId==windows==
[18:15:22.644] > 
> osVersion====
[18:15:22.651] > 
> arch==x64==
> platform==windows==
[18:15:22.660] > 
> unpackResult====
[18:15:22.701] > didLocalDownload==False==
> downloadTime====
> installTime====
[18:15:22.708] > 
> extInstallTime====
> serverStartTime==600==
> 3231e8089136: end
[18:15:22.708] Received install output: 
exitCode==32==
listeningOn====
osReleaseId==windows==
osVersion====
arch==x64==
platform==windows==
unpackResult====
didLocalDownload==False==
downloadTime====
installTime====
extInstallTime====
serverStartTime==600==

[18:15:22.712] Resolver error: Error: The VS Code Server failed to start
	at m.ServerInstallError (c:\Users\US-2\.vscode\extensions\ms-vscode-remote.remote-ssh-0.98.0\out\extension.js:1:584322)
	at f (c:\Users\US-2\.vscode\extensions\ms-vscode-remote.remote-ssh-0.98.0\out\extension.js:1:578379)
	at t.handleInstallOutput (c:\Users\US-2\.vscode\extensions\ms-vscode-remote.remote-ssh-0.98.0\out\extension.js:1:581404)
	at t.tryInstall (c:\Users\US-2\.vscode\extensions\ms-vscode-remote.remote-ssh-0.98.0\out\extension.js:1:681793)
	at async c:\Users\US-2\.vscode\extensions\ms-vscode-remote.remote-ssh-0.98.0\out\extension.js:1:644041
	at async t.withShowDetailsEvent (c:\Users\US-2\.vscode\extensions\ms-vscode-remote.remote-ssh-0.98.0\out\extension.js:1:647359)
	at async t.resolve (c:\Users\US-2\.vscode\extensions\ms-vscode-remote.remote-ssh-0.98.0\out\extension.js:1:645091)
	at async c:\Users\US-2\.vscode\extensions\ms-vscode-remote.remote-ssh-0.98.0\out\extension.js:1:720839
[18:15:22.726] ------




[18:15:23.045] > 
[18:15:23.334] > 3231e8089136: start
> SSH_AUTH_SOCK====
> listeningOn====
> osReleaseId==windows==
> osVersion==6.1.7601==
> arch==x64==
> platform==windows==
> unpackResult====
> didLocalDownload==False==
> downloadTime====
> installTime====
> extInstallTime====
> serverStartTime==600==
> connectionToken==a1aaa111-1111-11aa-a11a-11111aa11111==
> 3231e8089136: end
> 760, watching 1992
> gps : Cannot find a process with the process identifier 2956.
> At line:3 char:7
> + if (!(gps -Id $v_)) {
> +       ~~~~~~~~~~~
>     + CategoryInfo          : ObjectNotFound: (2956:Int32) [Get-Process], Proc
>    essCommandException
>     + FullyQualifiedErrorId : NoProcessFoundForGivenId,Microsoft.PowerShell.Co
>    mmands.GetProcessCommand
>  
> server died, exit
[18:15:24.589] "install" terminal command done
[18:15:24.591] Install terminal quit with output: server died, exit
