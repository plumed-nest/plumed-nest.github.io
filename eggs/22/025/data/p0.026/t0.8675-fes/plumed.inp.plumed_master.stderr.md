**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8675-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.CKJOMV/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1392-321:62312] *** Process received signal ***
[fv-az1392-321:62312] Signal: Aborted (6)
[fv-az1392-321:62312] Signal code:  (-6)
[fv-az1392-321:62312] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f158a045330]
[fv-az1392-321:62312] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f158a09eb2c]
[fv-az1392-321:62312] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f158a04527e]
[fv-az1392-321:62312] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f158a0288ff]
[fv-az1392-321:62312] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f158a4a5ff5]
[fv-az1392-321:62312] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f158a4bb0da]
[fv-az1392-321:62312] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f158a4a5a55]
[fv-az1392-321:62312] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f158a4a5a6f]
[fv-az1392-321:62312] [ 8] plumed_master(+0x146dd)[0x55e4f3dec6dd]
[fv-az1392-321:62312] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f158a02a1ca]
[fv-az1392-321:62312] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f158a02a28b]
[fv-az1392-321:62312] [11] plumed_master(+0x15365)[0x55e4f3ded365]
[fv-az1392-321:62312] *** End of error message ***
</pre>
{% endraw %}
