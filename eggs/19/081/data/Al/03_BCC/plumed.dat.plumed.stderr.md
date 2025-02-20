**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.zvoAY2.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az797-511:09522] *** Process received signal ***
[fv-az797-511:09522] Signal: Aborted (6)
[fv-az797-511:09522] Signal code:  (-6)
[fv-az797-511:09522] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faac3645330]
[fv-az797-511:09522] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faac369eb2c]
[fv-az797-511:09522] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faac364527e]
[fv-az797-511:09522] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faac36288ff]
[fv-az797-511:09522] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faac3aa5ff5]
[fv-az797-511:09522] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faac3abb0da]
[fv-az797-511:09522] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faac3aa5a55]
[fv-az797-511:09522] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faac3aa5a6f]
[fv-az797-511:09522] [ 8] plumed(+0x146dd)[0x55f1473186dd]
[fv-az797-511:09522] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faac362a1ca]
[fv-az797-511:09522] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faac362a28b]
[fv-az797-511:09522] [11] plumed(+0x15365)[0x55f147319365]
[fv-az797-511:09522] *** End of error message ***
</pre>
{% endraw %}
