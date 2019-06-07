SSH Client
====================

In order to do anything on the Shared Computing Cluster (SCC) from your local computer, you first need to connect to the SCC using an SSH (**S**ecure **SH**ell) client. This task varies greatly based on your local operating system. Follow the SSH client installation instructions below depending on your operating system.

Windows
--------------------

Option 1: MobaXterm
***********************

SSH client with x-forwarding capabilities for graphic sharing

1. Download and install MobaXterm from `here <http://mobaxterm.mobatek.net/>`
2. Launch MobaXterm and start a new session
    |ssh_1|
3. Select SSH as the session type
    |ssh_2|
4. Specify ``ssc1.bu.edu`` as the remote host and click “OK”
    |ssh_3|
5. Your connection will be saved on the left sidebar, so the next time you can start your session by clicking the “scc1.bu.edu [SSH]” link. In the terminal window you will get a prompt to enter your BU login information and password
    |ssh_4|

Option 2 - PuTTY
***********************

1. Download and install `PuTTY <https://www.putty.org/>`
2. Enter your connection settings
    - Host name: ``scc1.bu.edu``
    - Port: 22 (leave as default)
    - Connection type: SSH (leave as default)

    |ssh_5|
3. Click ``Open`` to start SSH session
4. If this is your first time connecting to the server from this computer, you will see the following output. Accept the connection by clicking ``Yes``
    |ssh_6|
5. Once the SSH connection is open, you should see a terminal prompt asking for your username (``username@scc1.bu.edu``) and then your password

.. |ssh_1| image:: images/ssh_1.png
.. |ssh_2| image:: images/ssh_2.png
.. |ssh_3| image:: images/ssh_3.png
.. |ssh_4| image:: images/ssh_4.png
.. |ssh_5| image:: images/ssh_5.png
.. |ssh_6| image:: images/ssh_6.png


Mac & Linux
--------------------

1. Use built-in terminal for both
2. *Mac option*: for X11-forwarding download `XQuartz <https://www.xquartz.org/>`
3. To sign into the scc for Mac and linux, open a terminal
	- Use ssh to connect to the SCC with your login credentials in the terminal:  ``your_local_machine% ssh username@scc1.bu.edu``
	- Enter BU kerberos password when prompted
	- Type ``exit`` to close session
