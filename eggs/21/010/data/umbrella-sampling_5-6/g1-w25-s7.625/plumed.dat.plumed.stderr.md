**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w25-s7.625/plumed.dat   
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
[fv-az95-172:43626] *** Process received signal ***
[fv-az95-172:43626] Signal: Aborted (6)
[fv-az95-172:43626] Signal code:  (-6)
[fv-az95-172:43626] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb4738dd210]
[fv-az95-172:43626] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb4738dd18b]
[fv-az95-172:43626] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb4738bc859]
[fv-az95-172:43626] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb473b44911]
[fv-az95-172:43626] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb473b5038c]
[fv-az95-172:43626] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb473b503f7]
[fv-az95-172:43626] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb473b506a9]
[fv-az95-172:43626] [ 7] plumed(+0xf47d)[0x55c1046c447d]
[fv-az95-172:43626] [ 8] plumed(+0x14004)[0x55c1046c9004]
[fv-az95-172:43626] [ 9] plumed(+0xf698)[0x55c1046c4698]
[fv-az95-172:43626] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb4738be0b3]
[fv-az95-172:43626] [11] plumed(+0xf76e)[0x55c1046c476e]
[fv-az95-172:43626] *** End of error message ***
</pre>
{% endraw %}
