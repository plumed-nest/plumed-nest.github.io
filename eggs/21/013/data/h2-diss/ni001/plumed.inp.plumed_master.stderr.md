**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-diss/ni001/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.UtE8l0/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az1947-163:64868] *** Process received signal ***
[fv-az1947-163:64868] Signal: Aborted (6)
[fv-az1947-163:64868] Signal code:  (-6)
[fv-az1947-163:64868] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f43efc45330]
[fv-az1947-163:64868] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f43efc9eb2c]
[fv-az1947-163:64868] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f43efc4527e]
[fv-az1947-163:64868] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f43efc288ff]
[fv-az1947-163:64868] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f43f00a5ff5]
[fv-az1947-163:64868] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f43f00bb0da]
[fv-az1947-163:64868] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f43f00a5a55]
[fv-az1947-163:64868] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f43f00a5a6f]
[fv-az1947-163:64868] [ 8] plumed_master(+0x146dd)[0x55a79034f6dd]
[fv-az1947-163:64868] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f43efc2a1ca]
[fv-az1947-163:64868] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f43efc2a28b]
[fv-az1947-163:64868] [11] plumed_master(+0x15365)[0x55a790350365]
[fv-az1947-163:64868] *** End of error message ***
</pre>
{% endraw %}
