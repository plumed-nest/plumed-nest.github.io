**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w45-s10.812/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.000 W_STRIDE 50
Maybe a missing space or a typo?
[fv-az95-172:38344] *** Process received signal ***
[fv-az95-172:38344] Signal: Aborted (6)
[fv-az95-172:38344] Signal code:  (-6)
[fv-az95-172:38344] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fed8b53e210]
[fv-az95-172:38344] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fed8b53e18b]
[fv-az95-172:38344] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fed8b51d859]
[fv-az95-172:38344] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fed8b7a5911]
[fv-az95-172:38344] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fed8b7b138c]
[fv-az95-172:38344] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fed8b7b13f7]
[fv-az95-172:38344] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fed8b7b16a9]
[fv-az95-172:38344] [ 7] plumed(+0xf47d)[0x55697280047d]
[fv-az95-172:38344] [ 8] plumed(+0x14004)[0x556972805004]
[fv-az95-172:38344] [ 9] plumed(+0xf698)[0x556972800698]
[fv-az95-172:38344] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fed8b51f0b3]
[fv-az95-172:38344] [11] plumed(+0xf76e)[0x55697280076e]
[fv-az95-172:38344] *** End of error message ***
</pre>
{% endraw %}
