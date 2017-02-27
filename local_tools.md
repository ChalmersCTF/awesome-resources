Tools tagged "GOOD" I can recommend.

I have not tried all tools mentioned
    especially those for windows

### OS / bootable:
    remnux		(linux distro for malware and reversing)    GOOD
  
    santoku     (linux distro for malware and forensics)
    
    cuckoo		(sandbox)
    
    sandboxie	(sandbox)


### Windows only:
sysinternals                GOOD
    
#### File info & div:
        trid         (file info)            GOOD
        PPEE         (PE analyzer)
        hackers-grep (PE analyzer)
        de4dot       (.NET deobfuscator)
        WinDbg       (Windows debugger)
        Immunity Debugger
[unpacker](https://github.com/malwaremusings/unpacker/)    (malware analysis with WinDbg) 

#### Forensics & memory: 
        AChoir       (Windows -live- forensics)
        RegRipper    (Windows registry)
        RegShot      (comparing registry dumps)     GOOD
        Fibratus     (Windows kernel activity)
    
#### Web related:
	burpsuite    (HTTP/HTTPS debugging and security testing)    GOOD
        fiddler      (HTTP/HTTPS debugging)     GOOD
#### Div:
        cygwin	     (terminal)
        cmder        (terminal)     GOOD
        universal extraction tool   GOOD
        pafish       (sandbox detection tool)
	

### Linux (or cross-platform):

#### File info
        Balbuzard       	 (bruteforce XOR, ROL .. and find patterns)
        strings         	 (strings)
        flare-floss     	 (strings from malware)  GOOD
        xxd		        	 (hex editor)            GOOD
        Image-exiftool  	 (images)
        Detect-it-easy  	 (file info)
        file            	 (file info)
        byteforce       	 (file info)
        pescanner       	 (file info)             GOOD
        binwalk        		 (file info)             GOOD

        MaltegoVT       	 (Domain, IP or file info) uses virustotal API
        TekDefense-Automater (online lookup: IP, domain, HASH)
   
#### Web related: 
        dig             (DNS lookup)    
        whois               
        fakedns
        machinae        (pip3 install machinae , info from site)
        inetsim         (simulate internet services in a lab environment)
        IPinfo
        Firebug         (browser plugin - debugger and more)
                        Better tools for javascript exists, spidermonkey?
#### Memory related:
        Rekall
        Volatility   (memory forensics)
        VolDiff      (compare win7 dumps with volatility)
        
#### Debug & reverse:
        vivisect/vdb/vtrace  (static analysis, debugger)
        IDA-pro              (freeware alternative exists on Windows, disassembler)    GOOD
        Radare2              (similar to IDA-pro, free)
        GDB                  (GNU Project Debugger)
        PINCE                (GDB front-end/reverse engineering)	
        pyelftools           (Python library for parsing ELF and DWARF)	
        capstone 			 (disassembler) 


### To consider:
http://www.kitploit.com/2016/07/limon-sandbox-for-analyzing-linux.html 		(linux malware analysis)
	
https://www.blackhat.com/us-16/briefings.html#augmenting-static-analysis-using-pintool-ablation		(static analysis)
	
### Assorted:
http://www.keystone-engine.org/		(assembler framework)
  
SMRT            (Sublime plugin for malware research)
