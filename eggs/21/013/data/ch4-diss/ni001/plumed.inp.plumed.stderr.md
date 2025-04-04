**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.2wVkyi/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.10b.so ../../data/ReweightGeomFES.cpp

[fv-az1360-658:08844] *** Process received signal ***
[fv-az1360-658:08844] Signal: Aborted (6)
[fv-az1360-658:08844] Signal code:  (-6)
[fv-az1360-658:08844] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9200045330]
[fv-az1360-658:08844] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f920009eb2c]
[fv-az1360-658:08844] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f920004527e]
[fv-az1360-658:08844] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f92000288ff]
[fv-az1360-658:08844] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f92004a5ff5]
[fv-az1360-658:08844] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f92004bb0da]
[fv-az1360-658:08844] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f92004a5a55]
[fv-az1360-658:08844] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f92004a5a6f]
[fv-az1360-658:08844] [ 8] plumed(+0x146dd)[0x55a2706786dd]
[fv-az1360-658:08844] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f920002a1ca]
[fv-az1360-658:08844] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f920002a28b]
[fv-az1360-658:08844] [11] plumed(+0x15365)[0x55a270679365]
[fv-az1360-658:08844] *** End of error message ***
</pre>
{% endraw %}
