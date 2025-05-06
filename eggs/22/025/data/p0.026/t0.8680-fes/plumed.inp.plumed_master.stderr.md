**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8680-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
Assembler messages:
Fatal error: can't create plumed_mklib.hHHxmt/../../code/ReweightGeomFES.o: No such file or directory
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../code/ReweightGeomFES.2.11.0-dev.so ../../code/ReweightGeomFES.cpp

[fv-az1392-321:62489] *** Process received signal ***
[fv-az1392-321:62489] Signal: Aborted (6)
[fv-az1392-321:62489] Signal code:  (-6)
[fv-az1392-321:62489] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f299de45330]
[fv-az1392-321:62489] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f299de9eb2c]
[fv-az1392-321:62489] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f299de4527e]
[fv-az1392-321:62489] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f299de288ff]
[fv-az1392-321:62489] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f299e2a5ff5]
[fv-az1392-321:62489] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f299e2bb0da]
[fv-az1392-321:62489] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f299e2a5a55]
[fv-az1392-321:62489] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f299e2a5a6f]
[fv-az1392-321:62489] [ 8] plumed_master(+0x146dd)[0x564bbac756dd]
[fv-az1392-321:62489] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f299de2a1ca]
[fv-az1392-321:62489] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f299de2a28b]
[fv-az1392-321:62489] [11] plumed_master(+0x15365)[0x564bbac76365]
[fv-az1392-321:62489] *** End of error message ***
</pre>
{% endraw %}
