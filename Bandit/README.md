# Bandit 
The Bandit wargame is aimed at absolute beginners. It will teach the basics needed to be able to play other wargames. <b>If you notice something essential is missing or have ideas for new levels, please let us know!</b> [OverTheWire Contact](https://overthewire.org/information/chat.html)

### Note for beginners
This game, like most other games, is organised in levels. You start at Level 0 and try to “beat” or “finish” it. Finishing a level results in information on how to start the next level. The pages on this website for “Level <X>” contain information on how to start level X from the previous level. E.g. The page for <em>[Level 1](./Level0-Level1/)</em> has information on how to gain access from <em>[Level 0](./README.md)</em> to <em>[Level 1](./Level0-Level1/README.md/)</em>. All levels in this game have a page on this website, and they are all linked to from the sidemenu on the left of this page.

You will encounter many situations in which you have no idea what you are supposed to do. <b>Don’t panic! Don’t give up!</b> The purpose of this game is for you to learn the basics. Part of learning the basics, is reading a lot of new information. If you’ve never used the command line before, a good first read is this [introduction to user commands](https://man7.org/linux/man-pages/man1/intro.1.html).

There are several things you can try when you are unsure how to continue:
- First, if you know a command, but don’t know how to use it, try the <b>manual</b> ([man page](https://en.wikipedia.org/wiki/Man_page)) by entering <b>man {command}</b>. For example, <b>man ls</b> to learn about the “ls” command. The “man” command also has a manual, try it! When using <b>man</b>, press <b>q</b> to quit (you can also use <b>/</b> and <b>n</b> and <b>N</b> to search).

- Second, if there is no man page, the command might be a <b>shell built-in</b>. In that case use the “<b>help <X></b>” command. E.g. help cd

- Also, your favorite <b>search-engine</b> is your friend. Learn how to use it! I recommend [Google](https://www.google.com/).

- Lastly, if you are still stuck, you can [join OverTheWire via chat](https://overthewire.org/information/chat.html)
You’re ready to start! Begin with Level 0, linked at the left of this page. Good luck!

<b>Note for VMs:</b> You may fail to connect to overthewire.org via SSH with a “<em>broken pipe error</em>” when the network adapter for the VM is configured to use NAT mode. Adding the setting <b>IPQoS throughput</b> to <b>/etc/ssh/ssh_config</b> should resolve the issue. If this does not solve your issue, the only option then is to change the adapter to Bridged mode.