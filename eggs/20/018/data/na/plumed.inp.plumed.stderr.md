**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
Stderr for source:  na/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.qwDvKe/../src/bias/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../src/bias/ReweightGeomFES.2.10.0.so ../src/bias/ReweightGeomFES.cpp

[pkrvm7jw40e0xgp:12188] *** Process received signal ***
[pkrvm7jw40e0xgp:12188] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12188] Signal code:  (-6)
[pkrvm7jw40e0xgp:12188] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f37b2845330]
[pkrvm7jw40e0xgp:12188] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f37b289eb2c]
[pkrvm7jw40e0xgp:12188] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f37b284527e]
[pkrvm7jw40e0xgp:12188] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f37b28288ff]
[pkrvm7jw40e0xgp:12188] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37b2ca5ff5]
[pkrvm7jw40e0xgp:12188] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37b2cbb0da]
[pkrvm7jw40e0xgp:12188] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37b2ca5a55]
[pkrvm7jw40e0xgp:12188] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37b2ca5a6f]
[pkrvm7jw40e0xgp:12188] [ 8] plumed(+0x146dd)[0x5649390a86dd]
[pkrvm7jw40e0xgp:12188] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f37b282a1ca]
[pkrvm7jw40e0xgp:12188] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f37b282a28b]
[pkrvm7jw40e0xgp:12188] [11] plumed(+0x15365)[0x5649390a9365]
[pkrvm7jw40e0xgp:12188] *** End of error message ***
</pre>
{% endraw %}
