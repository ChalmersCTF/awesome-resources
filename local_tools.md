### OS / bootable:
    remnux    (linux distro for malware and reversing)    Recommended
    santoku   (linux distro for malware and forensics) 
    cuckoo    (sandbox)   
    sandboxie (sandbox)


### Windows only:
sysinternals      [Recommended]
    
#### File info & div:
        trid             (file info)            Recommended
        PPEE             (PE analyzer)
        hackers-grep     (PE analyzer)
        de4dot           (.NET deobfuscator)
        WinDbg           (Windows debugger)
        Immunity Debugger
[unpacker](https://github.com/malwaremusings/unpacker/)      (malware analysis with WinDbg) 

#### Forensics & memory: 
        AChoir       (Windows -live- forensics)
        RegRipper    (Windows registry)
        RegShot      (comparing registry dumps)     Recommended
        Fibratus     (Windows kernel activity)
    
#### Div:
        cygwin       (terminal)
        cmder        (terminal)       Recommended
        pafish       (sandbox detection tool)
        universal extraction tool     Recommended
  

### Linux (or cross-platform):

#### File info
        Balbuzard       (bruteforce XOR, ROL .. and find patterns)
        strings         (strings)
        flare-floss     (strings from malware)  Recommended
        xxd             (hex editor)            Recommended
        Image-exiftool  (images)
        Detect-it-easy  (file info)
        file            (file info)
        byteforce       (file info)
        pescanner       (file info)             Recommended
        binwalk         (file info)             Recommended

###### Uses online resources
        MaltegoVT             (Domain, IP or file info) uses virustotal API 
        TekDefense-Automater  (lookups: IP, domain, HASH)
        machinae              (info gathering from sites) 
   
#### Web related: 
        burpsuite  (HTTP/HTTPS debugging and security testing)       Recommended
        fiddler    (HTTP/HTTPS debugging)                            Recommended
        inetsim    (simulate internet services in a lab environment)
        
        whois
        IPinfo
        Firebug    (browser plugin - debugger and more)
        ( Better tools for javascript exists, spidermonkey? )
#### Memory related:
        Rekall
        Volatility   (memory forensics)
        VolDiff      (compare win7 dumps with volatility)
        
#### DNS:
        dig       (DNS lookup)  
        DNSviz    (analyzing & visualizing  DNS/DNSSEC behavior)
        Unbound   (validating recursive caching resolver)
        fakedns
        
        [more tools](https://www.verisign.com/en_US/company-information/verisign-labs/internet-security-tools/index.xhtml)



#### Analysis (debuggers, reversing, fuzzing, static code analysis, ..)
###### Reversing
        Radare2   (binary analyzis, disassembler)         Recommended
        IDA-pro   (-||- however free version is limited)  Recommended
        capstone  (disassembler) 
        nasm      (disassembler) 
        x86dis    (disassembler x86)
###### Debuggers
        vivisect/vdb/vtrace  (static analysis, debugger)
        GDB                  (GNU Project Debugger)
        PINCE                (GDB front-end/reverse engineering)  
        strace               (simple debugger)
###### Other
        pyelftools           (Python library for parsing ELF and DWARF)  
        
        [Malicious JS Analyser](https://github.com/CapacitorSet/box-js)


### To consider:
http://www.kitploit.com/2016/07/limon-sandbox-for-analyzing-linux.html     (linux malware analysis)
  
https://www.blackhat.com/us-16/briefings.html#augmenting-static-analysis-using-pintool-ablation    (static analysis)
  
### Assorted:
http://www.keystone-engine.org/    (assembler framework)
  
SMRT            (Sublime plugin for malware research)

https://github.com/gchq/CyberChef
