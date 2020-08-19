Navicat Premium12的激活方法一.前期准备    
1.移步官网下载安装文件    
2.安装，假设安装路径为 D:\Navicat\Navicat Premium 12    
3.移步github下载最新版激活所需的.exe文件压缩包，解压之后有两个.exe文件（navicat-keygen.exe,navicat-patcher.exe）, 假设安装位置为 D:\Navicat\navicat-keygen-for-x64    
4.安装结束后，以管理员的身份（右键有这个选项）打开cmd,       


二.命令行输入
	1. D: （按回车）
	2. cd Navicat\navicat-keygen-for-x64（按回车）
	3. navicat-patcher.exe "D:\Navicat\Navicat Premium 12"，（按回车）接下来会输出一堆东西
  ***************************************************
  * Navicat Patcher by @DoubleLabyrinth *
  * Version: 4.0 
  ****************************************************
  Press Enter to continue or Ctrl + C to abort.
  
  [+] Try to open Navicat.exe ... Ok!
  [+] Try to open libcc.dll ... Ok!
  [+] PatchSolution0 ...... Ready to apply
  [*] Patch offset = +0x029bccd8
  [+] PatchSolution1 ...... Ready to apply
  [*] [0] Patch offset = +0x02206c00
  [*] [1] Patch offset = +0x0074c489
  [*] [2] Patch offset = +0x02206910
  [*] [3] Patch offset = +0x0074c46f
  [*] [4] Patch offset = +0x02206904
  [-] PatchSolution2 ...... Omitted
  [+] PatchSolution3 ...... Ready to apply
  [*] [ 0] Instruction RVA = 0x016539c8, Patch Offset = +0x023e64d4
  [*] [ 1] Instruction RVA = 0x01653a1f, Patch Offset = +0x01652e23
  [*] [ 2] Instruction RVA = 0x01653a25, Patch Offset = +0x01652e28
  [*] [ 3] Instruction RVA = 0x01653a8c, Patch Offset = +0x01652e8e
  ...
  ...
  ...
  [*] [108] Instruction RVA = 0x016604e1, Patch Offset = +0x023e66d8
  [*] [109] Instruction RVA = 0x01660518, Patch Offset = +0x0165f91c
  [*] [110] Instruction RVA = 0x0166051e, Patch Offset = +0x0165f921
  [*] PatchSolution0 is suppressed in order to keep digital signature valid.
  [*] Generating new RSA private key, it may take a long time...
  [*] Your RSA public key:
  -----BEGIN PUBLIC KEY-----
  MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEA1hV66HgU4LrKXWW6O7bKAN6ZTr5W+Mq8ClTQ+Pc+BdhLu6rww55kVq7OXKGpvx0G4eTafYMGrrBETgDSTaMqBx+8bZbGBWh2LtNfqU+xUrpHHBSz0ByBc3iTEzzthJl+Fzf8suDX2lWYIc/Ym/eWYtxdJ7xOzLb68z4N0zVmA0jFX2FOm75DRYgKqy4SGixapfucL9dVaWVLTUdbrVdj4LX78t4t5ykbYoThrat4yuLvj/BxLaQ6ivKD+ScfHdtCoY+NA5jmBoUfBq3Q1SXBiNaoXctbi0/H3MiPu0cRojryAocooF89yFm5/mNnzWGAYPr6DvBI8CDTZmjaQ4oCaQIDAQAB
  -----END PUBLIC KEY-----
  *******************************************************
  * PatchSolution1 *
  *******************************************************
  [*] Previous:
  +0x0000000002206c00 44 37 35 31 32 35 42 37 30 37 36 37 42 39 34 31 D75125B70767B941
  +0x0000000002206c10 34 35 42 34 37 43 31 43 42 33 43 30 37 35 35 45 45B47C1CB3C0755E
  +0x0000000002206c20 37 43 43 42 38 38 32 35 43 35 44 43 45 30 43 35 7CCB8825C5DCE0C5
  ...
  ...
  [*] After:
  +0x0000000002206c00 33 43 32 39 30 39 35 38 33 34 38 41 42 43 35 39 3C290958348ABC59
  +0x0000000002206c10 36 44 39 30 43 45 45 38 31 36 42 36 39 38 34 44 6D90CEE816B6984D
  +0x0000000002206c20 35 32 35 34 37 45 30 32 34 31 42 36 42 43 31 41 52547E0241B6BC1A
  ...
  ...
  [*] Previous:+0x000000000074c480 fe ea bc 01 ....
  [*] After:+0x000000000074c480 08 00 00 00 ....
  [*] Previous:
  +0x0000000002206910 45 31 43 45 44 30 39 42 39 43 32 31 38 36 42 46 E1CED09B9C2186BF
  +0x0000000002206920 37 31 41 37 30 43 30 46 45 32 46 31 45 30 41 45 71A70C0FE2F1E0AE
  +0x0000000002206930 46 33 42 44 36 42 37 35 32 37 37 41 41 42 32 30 F3BD6B75277AAB20
  ...
  ...
  [*] After:
  +0x0000000002206910 41 33 39 42 41 36 43 34 31 36 33 32 35 30 46 45 A39BA6C4163250FE
  +0x0000000002206920 42 32 41 39 31 41 34 32 46 44 42 46 30 41 32 31 B2A91A42FDBF0A21
  +0x0000000002206930 33 34 46 34 36 44 43 45 34 30 42 46 41 42 33 35 34F46DCE40BFAB35
  ...
  ...
  [*] Previous:+0x000000000074c460 59 Y+0x000000000074c470 08 01 00 ...
  [*] After:+0x000000000074c460 06 .+0x000000000074c470 00 00 00 ...
  [*] Previous:+0x0000000002206900 39 32 39 33 33 92933
  [*] After:+0x0000000002206900 42 34 34 33 38 B4438
  *******************************************************
  * PatchSolution3 *
  *******************************************************
  [*] +023e64d4: 4d 49 49 ---> 4d 49 49
  [*] +01652e23: 42 49 ---> 42 49
  [*] +01652e28: 6a ---> 6a.........
  [*] +023e66d8: 77 49 44 41 ---> 51 49 44 41
  [*] +0165f91c: 51 41 ---> 51 41
  [*] +0165f921: 42 ---> 42
  [*] New RSA-2048 private key has been saved to
  C:\Users\DoubleSine\github.com\navicat-keygen\bin\x64-Release\RegPrivateKey.pem
  *******************************************************
  * PATCH HAS BEEN DONE SUCCESSFULLY! *
  * HAVE FUN AND ENJOY~ *
  *******************************************************
	4. 再输入navicat-keygen.exe -text .\RegPrivateKey.pem（按回车）下面会生成Serial number:NAVO-2ORP-IN5A-GQEE（每个人不一样）
  Select Navicat product:
  0. DataModeler
  1. Premium
  2. MySQL
  3. PostgreSQL
  4. Oracle
  5. SQLServer
  6. SQLite
  7. MariaDB
  8. MongoDB
  9. ReportViewer
  (Input index)> 1
  Select product language:
  0. English
  1. Simplified Chinese
  2. Traditional Chinese
  3. Japanese
  4. Polish
  5. Spanish
  6. French
  7. German
  8. Korean
  9. Russian
  10. Portuguese
  (Input index)> 1
  (Input major version number, range: 0 ~ 15, default: 12)> 12
  Serial number:
  NAVN-IDRP-IJLA-DHBC
  Your name:
	5. 接下来输入用户名(your name)和组织名(your organization)；随便写，不要太长。
  Your name: helloworldYour 
  organization: helloworldInput 
  request code (in Base64), 
  input empty line to end:
	6. 这里要求填入请求码，不要关闭cmd，断开网络打开刚安装的navicat，找到注册窗口
7. 点击输入上面生成的Serial number，点击激活，在线激活失败，这时候Navicat会询问你是否手动激活，点击是，        
在手动激活窗口你会得到一个请求码，复制它并把它粘贴到keygen里（即上面停留的位置：Input request code        
(in Base64), input empty line to end:）下面。最后连按两下回车结束输入。    
8. 你会得到一串激活码。复制，并把它粘贴到Navicat的手动激活窗口，最后点激活按钮。     
9. 激活成功。        注意：激活之后别更新navicat了，不然又要重新激活一次。
