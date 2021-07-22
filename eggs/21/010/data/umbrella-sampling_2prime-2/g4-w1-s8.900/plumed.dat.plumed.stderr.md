**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g4-w1-s8.900/plumed.dat   
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
[fv-az95-172:40483] *** Process received signal ***
[fv-az95-172:40483] Signal: Aborted (6)
[fv-az95-172:40483] Signal code:  (-6)
[fv-az95-172:40483] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f98380c9210]
[fv-az95-172:40483] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f98380c918b]
[fv-az95-172:40483] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f98380a8859]
[fv-az95-172:40483] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9838330911]
[fv-az95-172:40483] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f983833c38c]
[fv-az95-172:40483] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f983833c3f7]
[fv-az95-172:40483] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f983833c6a9]
[fv-az95-172:40483] [ 7] plumed(+0xf47d)[0x564c2a80d47d]
[fv-az95-172:40483] [ 8] plumed(+0x14004)[0x564c2a812004]
[fv-az95-172:40483] [ 9] plumed(+0xf698)[0x564c2a80d698]
[fv-az95-172:40483] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f98380aa0b3]
[fv-az95-172:40483] [11] plumed(+0xf76e)[0x564c2a80d76e]
[fv-az95-172:40483] *** End of error message ***
</pre>
{% endraw %}
