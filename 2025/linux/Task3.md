# **3️⃣ Log File Analysis with AWK, Grep & Sed**

- Logs are crucial in DevOps! You’ll analyze logs using the **Linux_2k.log** file from **LogHub** ([GitHub Repo](https://github.com/logpai/loghub/blob/master/Linux/Linux_2k.log)).

## clonning the github file

### `git clone https://github.com/logapi/loghub.git`

- navigate to linux_2k.log

  ### `cd loghub/Linux_2k.log`

  - verify that file exists or not

  ### `ls -l`

  1.- Use `grep` to find all occurrences of the word **"error"**.<br>

  `grep -i "error" Linux_2k.log `

  2.Use `awk` to extract **timestamps and log levels**.<br>
