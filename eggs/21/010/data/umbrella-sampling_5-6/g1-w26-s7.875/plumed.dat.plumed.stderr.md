**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w26-s7.875/plumed.dat   
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
[fv-az95-172:43650] *** Process received signal ***
[fv-az95-172:43650] Signal: Aborted (6)
[fv-az95-172:43650] Signal code:  (-6)
[fv-az95-172:43650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc98821d210]
[fv-az95-172:43650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc98821d18b]
[fv-az95-172:43650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc9881fc859]
[fv-az95-172:43650] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc988484911]
[fv-az95-172:43650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc98849038c]
[fv-az95-172:43650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc9884903f7]
[fv-az95-172:43650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc9884906a9]
[fv-az95-172:43650] [ 7] plumed(+0xf47d)[0x557bc066c47d]
[fv-az95-172:43650] [ 8] plumed(+0x14004)[0x557bc0671004]
[fv-az95-172:43650] [ 9] plumed(+0xf698)[0x557bc066c698]
[fv-az95-172:43650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc9881fe0b3]
[fv-az95-172:43650] [11] plumed(+0xf76e)[0x557bc066c76e]
[fv-az95-172:43650] *** End of error message ***
</pre>
{% endraw %}
