**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w17-s7.463/plumed.dat   
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
[fv-az95-172:39847] *** Process received signal ***
[fv-az95-172:39847] Signal: Aborted (6)
[fv-az95-172:39847] Signal code:  (-6)
[fv-az95-172:39847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f98d50ff210]
[fv-az95-172:39847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f98d50ff18b]
[fv-az95-172:39847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f98d50de859]
[fv-az95-172:39847] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f98d5366911]
[fv-az95-172:39847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f98d537238c]
[fv-az95-172:39847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f98d53723f7]
[fv-az95-172:39847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f98d53726a9]
[fv-az95-172:39847] [ 7] plumed(+0xf47d)[0x564951c5647d]
[fv-az95-172:39847] [ 8] plumed(+0x14004)[0x564951c5b004]
[fv-az95-172:39847] [ 9] plumed(+0xf698)[0x564951c56698]
[fv-az95-172:39847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f98d50e00b3]
[fv-az95-172:39847] [11] plumed(+0xf76e)[0x564951c5676e]
[fv-az95-172:39847] *** End of error message ***
</pre>
{% endraw %}
