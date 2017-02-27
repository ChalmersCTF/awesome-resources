### OS / bootable:
    remnux		(linux distro for malware and reversing)    Recommended
    santoku     (linux distro for malware and forensics) 
    cuckoo		(sandbox)   
    sandboxie	(sandbox)


### Windows only:
sysinternals                	   Recommended
    
#### File info & div:
        trid         (file info)            Recommended
        PPEE         (PE analyzer)
        hackers-grep (PE analyzer)
        de4dot       (.NET deobfuscator)
        WinDbg       (Windows debugger)
        Immunity Debugger
[unpacker](https://github.com/malwaremusings/unpacker/)    (malware analysis with WinDbg) 

#### Forensics & memory: 
        AChoir       (Windows -live- forensics)
        RegRipper    (Windows registry)
        RegShot      (comparing registry dumps)     Recommended
        Fibratus     (Windows kernel activity)
    
#### Web related:
        burpsuite    (HTTP/HTTPS debugging and security testing)    Recommended
        fiddler      (HTTP/HTTPS debugging)     Recommended
#### Div:
        cygwin	     (terminal)
        cmder        (terminal)     Recommended
        universal extraction tool   Recommended
        pafish       (sandbox detection tool)
	

### Linux (or cross-platform):

#### File info
        Balbuzard       	 (bruteforce XOR, ROL .. and find patterns)
        strings         	 (strings)
        flare-floss     	 (strings from malware)  Recommended
        xxd		        	 (hex editor)            Recommended
        Image-exiftool  	 (images)
        Detect-it-easy  	 (file info)
        file            	 (file info)
        byteforce       	 (file info)
        pescanner       	 (file info)             Recommended
        binwalk        		 (file info)             Recommended
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
        IDA-pro              (freeware alternative exists on Windows, disassembler)    Recommended
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
