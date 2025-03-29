**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.VqYHjM.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az1344-582:66821] *** Process received signal ***
[fv-az1344-582:66821] Signal: Aborted (6)
[fv-az1344-582:66821] Signal code:  (-6)
[fv-az1344-582:66821] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1029045330]
[fv-az1344-582:66821] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f102909eb2c]
[fv-az1344-582:66821] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f102904527e]
[fv-az1344-582:66821] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10290288ff]
[fv-az1344-582:66821] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10294a5ff5]
[fv-az1344-582:66821] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10294bb0da]
[fv-az1344-582:66821] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10294a5a55]
[fv-az1344-582:66821] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10294a5a6f]
[fv-az1344-582:66821] [ 8] plumed(+0x146dd)[0x556f410db6dd]
[fv-az1344-582:66821] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f102902a1ca]
[fv-az1344-582:66821] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f102902a28b]
[fv-az1344-582:66821] [11] plumed(+0x15365)[0x556f410dc365]
[fv-az1344-582:66821] *** End of error message ***
</pre>
{% endraw %}
