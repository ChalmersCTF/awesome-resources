General terminal commands and e.g. nmap examples https://github.com/Eliot-Roxbergh/dotFIles/blob/master/text_files/example_commands.txt

### OS / bootable:
    remnux    (linux distro for malware and reversing)    Recommended
    santoku   (linux distro for malware and forensics)
    Matriux   (-||- debian-based)
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
        pompem          (Exploit/vuln search)
        yara            (malware classification)

#### File / domain info
        Balbuzard       (bruteforce XOR, ROL .. and find patterns)
        strings         (strings)
        flare-floss     (strings deobfuscation) Recommended
        xxd             (hex editor)            Recommended
        hexdump         (hex viewer)
        Image-exiftool  (image metadata tool)
        Detect-it-easy  (file info)
        file            (file info)
        byteforce       (file info)
        binwalk         (file info)             Recommended
        AnalyzePE       (tools for PE file)
            pescanner   (PE information, contained in AnalyzePE) Recommended


###### Uses online resources
        IPinfo                (IP, domain info) uses virustotal, google, urlvoid APIs
        MaltegoVT             (Domain, IP or file info) uses virustotal API 
        TekDefense-Automater  (lookups: IP, domain, HASH)
        machinae              (info gathering from sites) 
        rblcheck              (IP blocklist, available in terminal and web)
   
#### Internet related:          
        masscan    (mass port scanning)
        nmap       (port/vuln scanner +service detection)
        whois      (domain info)
        Firebug    (browser plugin - debugger and more)
        ( Better tools for javascript exists, spidermonkey? )
        sqlmap     (SQL injection bruteforce)

###### Manipulate / Handle / MITM local traffic
        burpsuite  (e.g. MITM local traffic)   Recommended
        fiddler    (e.g. MITM local traffic)   Recommended
        wireshark  (traffic analyzis)          Recommended 
        tcpdump    (display TCP/IP traffic live, searchable)
        tcpreplay  (replay captured network traffic)

        inetsim    (simulate internet services in a lab environment)
        sslstrip   (HTTPS -> HTTP, mitm)
        thc-ipv6   (IPv6 attack tool)
        fakedns    (fake DNS responses) 
        dnstop     (display local dns traffic)
        tcpflow    (TCP/IP session reassembler)

###### DNS
        dig        (DNS lookup)  
        DNSviz     (analyzing & visualizing  DNS/DNSSEC behavior)
        Unbound    (validating recursive caching resolver)
        dns-browse (dig front-end, DNS browsing)
        dnstracer  (trace dns traffic)
        dnswalk    (dns debugger)

[more tools](https://www.verisign.com/en_US/company-information/verisign-labs/internet-security-tools/index.xhtml)


###### general linux
        iftop      (live network traffic on system)
        ntop       (live network traffic on system)
        netcat     (TCP/IP tool, send/receive traffic)
        netstat    (local connections etc.)
        traceroute (route to host)
        route      (local routing table)
        arp        (local arp cache)
        psutils    (process and system utils)
        pexpect    (spawn and control children, automation)

#### Memory related
        Rekall
        Volatility   (memory forensics)
            VolDiff      (compare win7 dumps with Volatility)
            VolUtility   (Volatility webUI)
#### Forensics     
        (Debian package forensics-all contains a lot of relevant, not limited to bruteforcing archives)


#### Analysis (debuggers, reversing, fuzzing, static code analysis, ..)
###### Reversing
        Radare2   (binary analyzis, disassembler)         Recommended
        IDA-pro   (-||- however free version is limited)  Recommended
        capstone  (disassembler) 
        nasm      (disassembler) 
        plasma-disassembler
        x86dis    (disassembler x86)

###### Debuggers
        vivisect/vdb/vtrace  (static analysis, debugger)
        GDB                  (GNU Project Debugger)
        PINCE                (GDB front-end/reverse engineering)  
        strace               (simple debugger)
        valgrind             (C memory leaks etc.)
###### Fuzzing
        afl                  (american fuzzy lop, on binary or source) 
###### Other
        pyelftools           (Python library for parsing ELF and DWARF)  
            readelf          (ELF information, contained in pyelftools)

[Malicious JS Analyser](https://github.com/CapacitorSet/box-js/)
        


### To consider:
http://www.kitploit.com/2016/07/limon-sandbox-for-analyzing-linux.html     (linux malware analysis)
  
https://www.blackhat.com/us-16/briefings.html#augmenting-static-analysis-using-pintool-ablation    (static analysis)
  
### Assorted:
http://www.keystone-engine.org/    (assembler framework)
  
SMRT            (Sublime plugin for malware research)

https://github.com/gchq/CyberChef
