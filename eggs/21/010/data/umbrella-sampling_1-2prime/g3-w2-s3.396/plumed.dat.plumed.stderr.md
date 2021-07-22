**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g3-w2-s3.396/plumed.dat   
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
[fv-az95-172:38668] *** Process received signal ***
[fv-az95-172:38668] Signal: Aborted (6)
[fv-az95-172:38668] Signal code:  (-6)
[fv-az95-172:38668] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2f7c9ef210]
[fv-az95-172:38668] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2f7c9ef18b]
[fv-az95-172:38668] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2f7c9ce859]
[fv-az95-172:38668] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2f7cc56911]
[fv-az95-172:38668] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2f7cc6238c]
[fv-az95-172:38668] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2f7cc623f7]
[fv-az95-172:38668] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2f7cc626a9]
[fv-az95-172:38668] [ 7] plumed(+0xf47d)[0x5630f448947d]
[fv-az95-172:38668] [ 8] plumed(+0x14004)[0x5630f448e004]
[fv-az95-172:38668] [ 9] plumed(+0xf698)[0x5630f4489698]
[fv-az95-172:38668] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2f7c9d00b3]
[fv-az95-172:38668] [11] plumed(+0xf76e)[0x5630f448976e]
[fv-az95-172:38668] *** End of error message ***
</pre>
{% endraw %}
