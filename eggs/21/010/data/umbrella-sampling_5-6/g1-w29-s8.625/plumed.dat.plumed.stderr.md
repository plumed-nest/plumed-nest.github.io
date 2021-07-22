**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w29-s8.625/plumed.dat   
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
[fv-az95-172:43723] *** Process received signal ***
[fv-az95-172:43723] Signal: Aborted (6)
[fv-az95-172:43723] Signal code:  (-6)
[fv-az95-172:43723] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f01995a0210]
[fv-az95-172:43723] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f01995a018b]
[fv-az95-172:43723] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f019957f859]
[fv-az95-172:43723] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0199807911]
[fv-az95-172:43723] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f019981338c]
[fv-az95-172:43723] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f01998133f7]
[fv-az95-172:43723] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f01998136a9]
[fv-az95-172:43723] [ 7] plumed(+0xf47d)[0x55bb6de1b47d]
[fv-az95-172:43723] [ 8] plumed(+0x14004)[0x55bb6de20004]
[fv-az95-172:43723] [ 9] plumed(+0xf698)[0x55bb6de1b698]
[fv-az95-172:43723] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f01995810b3]
[fv-az95-172:43723] [11] plumed(+0xf76e)[0x55bb6de1b76e]
[fv-az95-172:43723] *** End of error message ***
</pre>
{% endraw %}
