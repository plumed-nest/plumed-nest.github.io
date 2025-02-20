**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-diss/ni111-symm/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.pmMDBc/../../data/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../data/ReweightGeomFES.2.11.0-dev.so ../../data/ReweightGeomFES.cpp

[fv-az1691-811:10629] *** Process received signal ***
[fv-az1691-811:10629] Signal: Aborted (6)
[fv-az1691-811:10629] Signal code:  (-6)
[fv-az1691-811:10629] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6906445330]
[fv-az1691-811:10629] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f690649eb2c]
[fv-az1691-811:10629] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f690644527e]
[fv-az1691-811:10629] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f69064288ff]
[fv-az1691-811:10629] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69068a5ff5]
[fv-az1691-811:10629] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69068bb0da]
[fv-az1691-811:10629] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69068a5a55]
[fv-az1691-811:10629] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69068a5a6f]
[fv-az1691-811:10629] [ 8] plumed_master(+0x146dd)[0x5593b3c796dd]
[fv-az1691-811:10629] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f690642a1ca]
[fv-az1691-811:10629] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f690642a28b]
[fv-az1691-811:10629] [11] plumed_master(+0x15365)[0x5593b3c7a365]
[fv-az1691-811:10629] *** End of error message ***
</pre>
{% endraw %}
