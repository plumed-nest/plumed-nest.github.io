**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w3-s4.583/plumed.dat   
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
[fv-az95-172:39280] *** Process received signal ***
[fv-az95-172:39280] Signal: Aborted (6)
[fv-az95-172:39280] Signal code:  (-6)
[fv-az95-172:39280] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f335c86f210]
[fv-az95-172:39280] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f335c86f18b]
[fv-az95-172:39280] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f335c84e859]
[fv-az95-172:39280] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f335cad6911]
[fv-az95-172:39280] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f335cae238c]
[fv-az95-172:39280] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f335cae23f7]
[fv-az95-172:39280] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f335cae26a9]
[fv-az95-172:39280] [ 7] plumed(+0xf47d)[0x55ec7bb5947d]
[fv-az95-172:39280] [ 8] plumed(+0x14004)[0x55ec7bb5e004]
[fv-az95-172:39280] [ 9] plumed(+0xf698)[0x55ec7bb59698]
[fv-az95-172:39280] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f335c8500b3]
[fv-az95-172:39280] [11] plumed(+0xf76e)[0x55ec7bb5976e]
[fv-az95-172:39280] *** End of error message ***
</pre>
{% endraw %}
