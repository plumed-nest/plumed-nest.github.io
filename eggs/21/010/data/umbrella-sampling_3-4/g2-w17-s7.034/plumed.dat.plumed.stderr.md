**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w17-s7.034/plumed.dat   
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
[fv-az95-172:40875] *** Process received signal ***
[fv-az95-172:40875] Signal: Aborted (6)
[fv-az95-172:40875] Signal code:  (-6)
[fv-az95-172:40875] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5414d6d210]
[fv-az95-172:40875] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5414d6d18b]
[fv-az95-172:40875] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5414d4c859]
[fv-az95-172:40875] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5414fd4911]
[fv-az95-172:40875] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f5414fe038c]
[fv-az95-172:40875] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f5414fe03f7]
[fv-az95-172:40875] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f5414fe06a9]
[fv-az95-172:40875] [ 7] plumed(+0xf47d)[0x55d5ff80447d]
[fv-az95-172:40875] [ 8] plumed(+0x14004)[0x55d5ff809004]
[fv-az95-172:40875] [ 9] plumed(+0xf698)[0x55d5ff804698]
[fv-az95-172:40875] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5414d4e0b3]
[fv-az95-172:40875] [11] plumed(+0xf76e)[0x55d5ff80476e]
[fv-az95-172:40875] *** End of error message ***
</pre>
{% endraw %}
