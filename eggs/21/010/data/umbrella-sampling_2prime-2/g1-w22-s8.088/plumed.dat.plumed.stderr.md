**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w22-s8.088/plumed.dat   
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
[fv-az95-172:39995] *** Process received signal ***
[fv-az95-172:39995] Signal: Aborted (6)
[fv-az95-172:39995] Signal code:  (-6)
[fv-az95-172:39995] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6b17d9f210]
[fv-az95-172:39995] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6b17d9f18b]
[fv-az95-172:39995] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6b17d7e859]
[fv-az95-172:39995] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6b18006911]
[fv-az95-172:39995] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6b1801238c]
[fv-az95-172:39995] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6b180123f7]
[fv-az95-172:39995] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6b180126a9]
[fv-az95-172:39995] [ 7] plumed(+0xf47d)[0x562fe0c8b47d]
[fv-az95-172:39995] [ 8] plumed(+0x14004)[0x562fe0c90004]
[fv-az95-172:39995] [ 9] plumed(+0xf698)[0x562fe0c8b698]
[fv-az95-172:39995] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6b17d800b3]
[fv-az95-172:39995] [11] plumed(+0xf76e)[0x562fe0c8b76e]
[fv-az95-172:39995] *** End of error message ***
</pre>
{% endraw %}
