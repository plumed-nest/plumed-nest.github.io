**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w30-s6.374/plumed.dat   
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
[fv-az95-172:42175] *** Process received signal ***
[fv-az95-172:42175] Signal: Aborted (6)
[fv-az95-172:42175] Signal code:  (-6)
[fv-az95-172:42175] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f76bc79d210]
[fv-az95-172:42175] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f76bc79d18b]
[fv-az95-172:42175] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f76bc77c859]
[fv-az95-172:42175] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f76bca04911]
[fv-az95-172:42175] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f76bca1038c]
[fv-az95-172:42175] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f76bca103f7]
[fv-az95-172:42175] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f76bca106a9]
[fv-az95-172:42175] [ 7] plumed(+0xf47d)[0x55aa1bfbc47d]
[fv-az95-172:42175] [ 8] plumed(+0x14004)[0x55aa1bfc1004]
[fv-az95-172:42175] [ 9] plumed(+0xf698)[0x55aa1bfbc698]
[fv-az95-172:42175] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f76bc77e0b3]
[fv-az95-172:42175] [11] plumed(+0xf76e)[0x55aa1bfbc76e]
[fv-az95-172:42175] *** End of error message ***
</pre>
{% endraw %}
