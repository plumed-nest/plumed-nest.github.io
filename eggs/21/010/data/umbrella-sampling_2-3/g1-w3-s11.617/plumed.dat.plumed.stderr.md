**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w3-s11.617/plumed.dat   
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
[fv-az95-172:39256] *** Process received signal ***
[fv-az95-172:39256] Signal: Aborted (6)
[fv-az95-172:39256] Signal code:  (-6)
[fv-az95-172:39256] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8624355210]
[fv-az95-172:39256] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f862435518b]
[fv-az95-172:39256] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8624334859]
[fv-az95-172:39256] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f86245bc911]
[fv-az95-172:39256] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f86245c838c]
[fv-az95-172:39256] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f86245c83f7]
[fv-az95-172:39256] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f86245c86a9]
[fv-az95-172:39256] [ 7] plumed(+0xf47d)[0x55f2189e247d]
[fv-az95-172:39256] [ 8] plumed(+0x14004)[0x55f2189e7004]
[fv-az95-172:39256] [ 9] plumed(+0xf698)[0x55f2189e2698]
[fv-az95-172:39256] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f86243360b3]
[fv-az95-172:39256] [11] plumed(+0xf76e)[0x55f2189e276e]
[fv-az95-172:39256] *** End of error message ***
</pre>
{% endraw %}
