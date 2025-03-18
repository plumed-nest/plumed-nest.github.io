**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.EBg2uH/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az790-36:65835] *** Process received signal ***
[fv-az790-36:65835] Signal: Aborted (6)
[fv-az790-36:65835] Signal code:  (-6)
[fv-az790-36:65835] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f392ce45330]
[fv-az790-36:65835] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f392ce9eb2c]
[fv-az790-36:65835] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f392ce4527e]
[fv-az790-36:65835] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f392ce288ff]
[fv-az790-36:65835] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f392d2a5ff5]
[fv-az790-36:65835] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f392d2bb0da]
[fv-az790-36:65835] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f392d2a5a55]
[fv-az790-36:65835] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f392d2a5a6f]
[fv-az790-36:65835] [ 8] plumed_master(+0x146dd)[0x560ac5f9e6dd]
[fv-az790-36:65835] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f392ce2a1ca]
[fv-az790-36:65835] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f392ce2a28b]
[fv-az790-36:65835] [11] plumed_master(+0x15365)[0x560ac5f9f365]
[fv-az790-36:65835] *** End of error message ***
</pre>
{% endraw %}
