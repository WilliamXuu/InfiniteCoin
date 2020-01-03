Infinitecoin
---
Infinitecoin is a fork of Litecoin version. Like Litecoin it uses scrypt as a proof of work scheme.

	- Total coins will be about 90,600 millions 
	- 30 sec block target
	- Difficulty retargets once every hour
	- initially 524,288 (2^19) coins per block, halves every 1 month (86,400 blocks).
	- The default ports are 9321(connect) and 9322(json rpc).


Development process
===================
2020-1-3  1.9.8.0
-- 
1. Delete access checkip.dyndns.org and www.showmyip.com (since 1.9.8.0)
2. Test network failed to open issue has been fixed (since 1.9.8.0)
3. Maximum number of restored nodes is 16 (reverted to 1.8.8.0)


2019-10-03  1.9.1.9  
--
1. Fix the problem which the reward overflows after the 64th time block reward halving.
Refer to the Bitcoin 0.9.2 rc1 revision method on June 1, 2014.


2019-8-20  1.9.1.8  
--
1. Remove the inner web links
2. Fix 1.9.1.4 and 1.9.1.6 versions as nodes, mobile wallet can not connect these versions of node synchronization problem.


2018-8-16 1.9.1.0
--
1. Beautify the startup page, more concise, more contemporary
2. The modification fee is changed from the original package size to 0.2% according to the transfer amount, up to 10,000 IFC, and the minimum 0.01 IFC charge.
3. Wallet home page to increase navigation station, block browser, mine pool list, source code download address
4. Add the version number in the lower right corner, click to link to the wallet download page
5. Chinese translation is more accurate
6. Add a fee calculation tool on the transfer page, and calculate the commission required for the transfer based on the input amount.
7. When adding or modifying the wallet password, the input password behavior is changed to: it is visible in the plain text when input, and the mask is added after the input is completed,effectively preventing the password input error.
8. Add a fee collection rule prompt on the transaction page
9. The maximum number of input words in the debug window has been changed from 65535 to 6553500, which is convenient for sending a large amount of transaction raw data.
10. Each block of data can reach about 10,000 transfer transactions


2018-04-10
--
1. Fix the problem that IFC can't start after Linux system is turned off IPv6.


2018-03-22
--
community official version 1.8.8.2, this version is modified and compiled based on the original 1.8.8.0 source code.
1. increased direct click transactions in transaction records, ID can jump to block browser query transaction records.
2. repair the receiving currency form, modify the first label in the address book form, cause the second tags to be modified bug.
3. about page image replacement, and increased the community's official website link.
4. repair of the lower right corner in the state of typos "kind" correct "clock"
5. improve the mining state of the lower right corner of Chinese display
6. verify that all English in the message window is translated into Chinese.
7. perfect the Chinese tray right click menu language display
8. improve the Chinese language display page.
9. The options page improves the Chinese language display
10. Improve the Chinese language display in the rest of the warning box
11. increase the number of connections to the default network nodes to 32, improve the block synchronization speed.
12. Upgrade the QT version to 4.8.7 to improve security
13. modify the default location of block data, which is the Infinitecoin folder under the current software running directory.
14. there will be vc++ rumtime error error when repairing json-rpc and console.

2018-3-15
--
1. increase the number of connections to the default network nodes to 32, improve the block synchronization speed.
2. perfect Chinese Translation
3. Upgrade the QT version to 4.8.7 to improve security
4. modify the default location of block data, which is the Infinitecoin folder under the current software running directory.


(Older)2015-4
---
Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 
