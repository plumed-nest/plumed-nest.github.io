**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
Stderr for source:  npt-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.L83UHK/../codes/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../codes/ReweightGeomFES.2.10b.so ../codes/ReweightGeomFES.cpp

[fv-az1781-652:65470] *** Process received signal ***
[fv-az1781-652:65470] Signal: Aborted (6)
[fv-az1781-652:65470] Signal code:  (-6)
[fv-az1781-652:65470] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f9e845330]
[fv-az1781-652:65470] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f9e89eb2c]
[fv-az1781-652:65470] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f9e84527e]
[fv-az1781-652:65470] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f9e8288ff]
[fv-az1781-652:65470] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f9eca5ff5]
[fv-az1781-652:65470] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f9ecbb0da]
[fv-az1781-652:65470] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f9eca5a55]
[fv-az1781-652:65470] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f9eca5a6f]
[fv-az1781-652:65470] [ 8] plumed(+0x146dd)[0x563303da86dd]
[fv-az1781-652:65470] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f9e82a1ca]
[fv-az1781-652:65470] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f9e82a28b]
[fv-az1781-652:65470] [11] plumed(+0x15365)[0x563303da9365]
[fv-az1781-652:65470] *** End of error message ***
</pre>
{% endraw %}
