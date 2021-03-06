# Penetration Testing Study Notes

This repo contains all my penetration testing study notes, penetration testing tools, scripts, techniques, tricks and also many scripts that I found them useful from all over the internet.

## Table of Contents

 * [bookmarks.md](./bookmarks.md)
 * [buffer_overflow](./buffer_overflow)
   * [assembly](./buffer_overflow/assembly)
     * [course_notes.md](./buffer_overflow/assembly/course_notes.md)
     * [debuging.md](./buffer_overflow/assembly/debuging.md)
   * [buffer_overflows.md](./buffer_overflow/buffer_overflows.md)
   * [scripts](./buffer_overflow/scripts)
     * [disable_linux_security.sh](./buffer_overflow/scripts/disable_linux_security.sh)
     * [linux_bo_exploit.rb](./buffer_overflow/scripts/linux_bo_exploit.rb)
     * [linux_bo_poc.py](./buffer_overflow/scripts/linux_bo_poc.py)
     * [payload.py](./buffer_overflow/scripts/payload.py)
     * [windows_bo_exploit.rb](./buffer_overflow/scripts/windows_bo_exploit.rb)
     * [windows_bo_fuzzer.py](./buffer_overflow/scripts/windows_bo_fuzzer.py)
   * [win32_buffer_overflow_exploitation.md](./buffer_overflow/win32_buffer_overflow_exploitation.md)
 * [cheatSheets](./cheatSheets)
 * [client_side](./client_side)
   * [signed_applet.java](./client_side/signed_applet.java)
 * [enumeration](./enumeration)
   * [active_information_gathering.md](./enumeration/active_information_gathering.md)
   * [configuration_management.md](./enumeration/configuration_management.md)
   * [information_gathering_owasp_guide.md](./enumeration/information_gathering_owasp_guide.md)
   * [osint_recon_ng.md](./enumeration/osint_recon_ng.md)
   * [passive_information_gathering.md](./enumeration/passive_information_gathering.md)
   * [scanning.md](./enumeration/scanning.md)
   * [tools](./enumeration/tools)
     * [discover](./enumeration/tools/discover)
     * [enum4linux](./enumeration/tools/enum4linux)
     * [host_list.sh](./enumeration/tools/host_list.sh)
     * [linenumv2.sh](./enumeration/tools/linenumv2.sh)
     * [mass.sh](./enumeration/tools/mass.sh)
     * [onetwopunch](./enumeration/tools/onetwopunch)
     * [recon_scan](./enumeration/tools/recon_scan)
     * [reconscan.py](./enumeration/tools/reconscan.py)
     * [remoterecon.py](./enumeration/tools/remoterecon.py)
     * [Vanquish](./enumeration/tools/Vanquish)
     * [vulscan](./enumeration/tools/vulscan)
   * [vulnerability_scanning.md](./enumeration/vulnerability_scanning.md)
 * [exploitation](./exploitation)
   * [643-fixed](./exploitation/643-fixed)
   * [computer_network_exploits.md](./exploitation/computer_network_exploits.md)
   * [downloadproxy.ps1](./exploitation/downloadproxy.ps1)
   * [File_Transfers.md](./exploitation/File_Transfers.md)
   * [ftp-txt](./exploitation/ftp-txt)
   * [jspb64_shell.java](./exploitation/jspb64_shell.java)
   * [jsp_processbuilder_shell.java](./exploitation/jsp_processbuilder_shell.java)
   * [minimum_csharp_shell.java](./exploitation/minimum_csharp_shell.java)
   * [openfuck.c](./exploitation/openfuck.c)
   * [Post-Exploitation.md](./exploitation/Post-Exploitation.md)
   * [powershell_to_meterpreter.sh](./exploitation/powershell_to_meterpreter.sh)
   * [Public Exploits.md](./exploitation/Public Exploits.md)
   * [reverse.ps1](./exploitation/reverse.ps1)
   * [reverse_shell.py](./exploitation/reverse_shell.py)
   * [reverse_shell_with_msfvenom.md](./exploitation/reverse_shell_with_msfvenom.md)
   * [setuid.c](./exploitation/setuid.c)
   * [trans2open.c](./exploitation/trans2open.c)
   * [useradd.c](./exploitation/useradd.c)
   * [wget-ps1](./exploitation/wget-ps1)
   * [wget-vbs](./exploitation/wget-vbs)
   * [wget.vbs](./exploitation/wget.vbs)
 * [networking](./networking)
   * [bpf_syntax.md](./networking/bpf_syntax.md)
   * [networking_concept.md](./networking/networking_concept.md)
 * [os](./os)
   * [kali_linux_commands.md](./os/kali_linux_commands.md)
   * [preparing_kali.md](./os/preparing_kali.md)
   * [preparing_windows.md](./os/preparing_windows.md)
   * [useful_commands.md](./os/useful_commands.md)
 * [oscp_resources](./oscp_resources)
   * [jolly_frog.html](./oscp_resources/jolly_frog.html)
   * [oscp_course_layout.md](./oscp_resources/oscp_course_layout.md)
   * [OSCP-Survival-Guide.md](./oscp_resources/OSCP-Survival-Guide.md)
 * [password_attack](./password_attack)
 * [port_forwarding](./port_forwarding)
 * [priv_escalation](./priv_escalation)
   * [escalation_gathering.sh](./priv_escalation/escalation_gathering.sh)
   * [Privilege_Escalation.md](./priv_escalation/Privilege_Escalation.md)
   * [Privledge_Logic_Transport.md](./priv_escalation/Privledge_Logic_Transport.md)
 * [README.md](./README.md)
 * [scripts](./scripts)
   * [cred_check.py](./scripts/cred_check.py)
   * [hash_check.py](./scripts/hash_check.py)
   * [sqldeli.py](./scripts/sqldeli.py)
   * [string_decode.py](./scripts/string_decode.py)
   * [xploit_installer.py](./scripts/xploit_installer.py)
 * [social_engineering](./social_engineering)
   * [social_engineering.md](./social_engineering/social_engineering.md)
   * [tools](./social_engineering/tools)
   * [scythe](./social_engineering/tools/scythe)
 * [templates](./templates)
   * [linux-template.md](./templates/linux-template.md)
   * [pwkv1_report.doc](./templates/pwkv1_report.doc)
   * [PWKv1-REPORT.doc](./templates/PWKv1-REPORT.doc)
   * [windows-template.md](./templates/windows-template.md)
 * [useful_tricks.md](./useful_tricks.md)
 * [web_pentest](./web_pentest)
   * [auxiliary_info.md](./web_pentest/auxiliary_info.md)
   * [file_upload.md](./web_pentest/file_upload.md)
   * [scripts](./web_pentest/scripts)
     * [dir_run_gobuster.sh](./web_pentest/scripts/dir_run_gobuster.sh)
     * [lfi_infile.py](./web_pentest/scripts/lfi_infile.py)
     * [sqli_timebased.py](./web_pentest/scripts/sqli_timebased.py)
     * [xss_bmp_header.py](./web_pentest/scripts/xss_bmp_header.py)
     * [xss_gif_header.py](./web_pentest/scripts/xss_gif_header.py)
   * [sqli_cheatsheet.md](./web_pentest/sqli_cheatsheet.md)
   * [sqli.md](./web_pentest/sqli.md)
   * [web_app_security.md](./web_pentest/web_app_security.md)
   * [xss_actionscript](./web_pentest/xss_actionscript)
   * [xss.json](./web_pentest/xss.json)
   * [xss.md](./web_pentest/xss.md)
 * [wifi](./wifi)
     * [wifi_penetration_testing.md](./wifi/wifi_penetration_testing.md)
